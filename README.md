# fail2ban-report
Fail2ban report

Example :

Extract fail2ban logs in log.csv :

./fail2ban-getlog log.csv

Generate report.pdf from log.csv data using GeoLite2-Country.mmdb database :

./fail2ban-report log.csv GeoLite2-Country.mmdb report.pdf

You can download GeoLite2-Country database here : 
