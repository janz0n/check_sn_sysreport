# check_sn_sysreport
Nagios/Naemon/OP5 Plugin for fetching blocked threats from Cisco Umbrella API (Reporting API - Security Activity Report)
https://hi.service-now.com/kb_view.do?sysparm_article=KB0727099

## Installation
pip install -r requirements.txt

## Usage
```
usage: check_sn_sysreport [-h] -o ORG -i ID [-l LABEL] [-w RANGE] [-c RANGE]
                          [-v] [-V] [-t TIMEOUT]

check_sn_sysreport

Options:
  -h, --help            show this help message and exit
  -o ORG, --org ORG     INSTANCE_NAME - https://<Instance_Name>.service-now.co
                        m/sys_report_display.do?sysparm_report_id=<SYS_ID>
  -i ID, --id ID        SYS_ID - https://<Instance_Name>.service-now.com/sys_r
                        eport_display.do?sysparm_report_id=<SYS_ID>
  -l LABEL, --label LABEL
                        Optional label
  -w RANGE, --warning RANGE
  -c RANGE, --critical RANGE
  -v, --verbose         increase output verbosity (use up to 3 times)
  -V, --version         show program's version number and exit
  -t TIMEOUT, --timeout TIMEOUT
                        timeout

https://hi.service-now.com/kb_view.do?sysparm_article=KB0727099
```
