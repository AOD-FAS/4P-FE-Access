# 4P-FE-Access
Public Repo to host Front End Access Controls / Messaging


This repository controls access to the 4P Front End.

***Active Versions***
Only active versions of 4P are allowed to launch. Update file "4P_ActiveVersions.txt" with version numbers that are compatible with current PDI backend.

Each active version is listed in "4P_ActiveVersions.txt", and are separated by a line feed. The 4P front end (2018.01.05) recognizes Windows line endings (CrLf) as the delimiter. IMPORTANT: Do not update this file via the browser, this will add Linux-style line feeds (Lf) and will cause the FE to detect the version as out-of-date. <<<TODO: fix this so it works both ways! 

***Active System Status and Messaging***

Controled by  "4P_ActiveStatus-Messaging.txt", delim = "--"
1--Normal Operations 
2--4P / XSB Service Degradation. [Application Loads / Optional Website Redirect ]
3--4P / XSB Service is Down. [Application Shut Down / Optional Website Redirect]

NOTE: see "4P_SAMPLE-Status-Messaging.txt" for samples / detail.
