# POCProxy
POCProxy is a Multi-Ming tool for POC like chains which derived from BURSTCOIN.


About
=====
POCProxy is a Multi-Ming tool for POC like chains which derived from BURSTCOIN.


Features
========
windows, linux, macOS support

x86 64bit, arm

avx512f, avx2, avx, sse

opencl


Configuration directives
========================
POCProxy
--------
Miners need to modify the pool config in the jar file, winzip or winrar will be ok:
POCProxy.jar\BOOT-INF\classes\poolInfos.xml

scavenger
---------
set url to the proxy address in config.yaml:
url: 'http://127.0.0.1:8080'


Usage
=====
Linux:
/bin/bash POCProxy-start.sh &
cd scavenger/linux ; nohup ./scavenger &

Win:
run POCProxy-start.bat by double click
entering into scavenger\win ,run scavenger by double click scavenger.exe
Notice: DO NOT CLOSE ANY CMD WINDOW!


Status
======
This version is pre-release, fully tested and verified for the following chains:
BSH,BSN,BURST

and ready to test for the following chains:
BHD,BOOM,DISC,LHD


Sponsors
========
Work on the original was fully funded by BSH project (http://www.bitsh.io/).


See also
========
ddProxy: http://www.ddproxy.sg/
