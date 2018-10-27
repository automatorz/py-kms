# History
_py-kms_ is a port of node-kms created by [cyrozap](http://forums.mydigitallife.info/members/183074-markedsword), which is a port of either the C#, C++, or .NET implementations of KMS Emulator. The original version was written by [CODYQX4](http://forums.mydigitallife.info/members/89933-CODYQX4) and is derived from the reverse-engineered code of Microsoft's official KMS.
 
# Features
- Responds to V4, V5, and V6 KMS requests.
- Supports activating:
	- Windows Vista 
	- Windows 7 
	- Windows 8
	- Windows 8.1
	- Windows 10 ( 1511 / 1607 / 1703 / 1709 )
	- Windows Server 2008
	- Windows Server 2008 R2
	- Windows Server 2012
	- Windows Server 2012 R2
	- Windows Server 2016
	- Microsoft Office 2010 ( Volume License )
	- Microsoft Office 2013 ( Volume License )
	- Microsoft Office 2016 ( Volume License )

# Usage
```docker run -d -p 1688:1688 --restart=always automatorz/py-kms```

# Windows
- ```slmgr.vbs -upk```
- ```slmgr.vbs -ipk XXXXX-XXXXX-XXXXX-XXXXX-XXXXX```
- ```slmgr.vbs -skms DOCKER_IP```
- ```slmgr.vbs -ato```
- ```slmgr.vbs -dlv```

# GVLK keys
- Windows: https://technet.microsoft.com/en-us/library/jj612867(v=ws.11).aspx  
- Office 2013: https://technet.microsoft.com/en-us/library/dn385360.aspx  
- Office 2016: https://technet.microsoft.com/en-us/library/dn385360(v=office.16).aspx

# License
   [![License](https://img.shields.io/badge/license-unlicense-lightgray.svg)](https://github.com/SystemRage/py-kms/blob/master/LICENSE)

