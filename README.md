# Sysmon

## Installing System monitor add on for Windows (Sysmon)

# Steps

- Got to https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon
- Press Download sysmon
- Extract folder
- Download a configuration file from https://github.com/olafhartong/sysmon-modular/blob/master/sysmonconfig.xml
- To download configuration file, right click on Raw code data and save xml file in the same folder as extracted Sysmon tool installation files
- Open Windows power shell as an admistartor
- Change directory to the Sysmon install folder, C:\Users\sahlu\Downloads\Sysmon>
  
  <a href="https://imgur.com/HH9N4Cp"><img src="https://i.imgur.com//HH9N4Cp.png" title="source: imgur.com" /></a>
  
- Type: .\Sysmon64.exe -accepteula -i .\sysmonconfig.xml
  - Sysmon64 is to install the 64bit for windows 64 bit machine
  - accepteula is to agree to the terms of service
  - sysmonconfig contains rules in capturing events in the system

  <a href="https://imgur.com/3MldZQp"><img src="https://i.imgur.com//3MldZQp.png" title="source: imgur.com" /></a>
  
- Go to Start > Event Viewer > Applications and Services Logs > Microsoft > Windows > Sysmon > Operational
  
  <a href="https://imgur.com/g6rolJX"><img src="https://i.imgur.com//g6rolJX.png" title="source: imgur.com" /></a>

 ## security teams can build a more robust defense that provides deeper insight into system activity and helps detect more sophisticated attacks. With the correct configuration and analysis, Sysmon logs can be an invaluable tool in the fight against cyber threats.
