# Windows Network Checkup Script

### Checks windows users(7 or above) internal network &amp; internet connectivity status (using ping) 

### Quick Start

- 	Download ZIP file.
- 	Extract on your individual windows desktop folder.
- 	After extracting go into extracted folder & **run mastercheck.bat** file & leave it **(*Do not close this file*)**, this file will run till timeout defined in 	*mastercheck.bat* file **(*For eg timeout /t 60 >NUL*)**
- 	For 1 minute continuosly this *mastercheck.bat* file will run and log output in txt file in individual folders,
	***For eg.. "ping_remote","ping_google","ping_gateway".***
- 	After completion of 1 minute(60s) this script will automatically stop get & log all the contents in **finalreport.txt** file in main folder.
