# Bitcoin Lightning Node Windows 10
## Installation notes from creating a Bitcoing Ligtning Node on a Windows 10 Home PC

* Tor as a service
* Lnd local user
* lnd.exe and lncli.exe
* rtl.js using node.exe
* Task Scheduler to run lnd and rtl on boot, as lnd user
* GPEdit.msc to give lnd user rights to run as batch 
* https://www.itechtics.com/enable-gpedit-windows-10-home/
* Group Policy shutdown script to do lncli stop before shutting down
* NAT forwarding on router to expose 7395
* externalip with a dynamic dns name


