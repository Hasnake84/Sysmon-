# Sysmon-

Installing System monitor add on for Windows (Sysmon)

Steps

- Got to https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon
- Press Download sysmon
- Extract folder
- Download a configuration file from https://github.com/olafhartong/sysmon-modular/blob/master/sysmonconfig.xml
- To download configuration file, right click on Raw code data and save xml file in the same folder as extracted Sysmon tool installation files
- Open Windows power shell as an admistartor
- Change directory to the Sysmon install folder, C:\Users\sahlu\Downloads\Sysmon>
- Type: .\Sysmon64.exe -accepteula -i .\sysmonconfig.xml
Sysmon64 is to install the 64bit for windows 64 bit machine
-accepteula is to agree to the terms of service
sysmonconfig contains rules in capturing events in the system
Go to Start > Event Viewer > Applications and Services Logs > Microsoft > Windows > Sysmon > Operational
