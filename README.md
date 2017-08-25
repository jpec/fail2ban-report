# fail2ban-report
This tool generate a simple report of fail2ban activity.

[Example PDF report](report.pdf)

## Extract fail2ban logs in a CSV file

```bash
$ ./fail2ban-getlog log.csv
```
You should create a cron task to regulary run `fail2ban-getlog log.csv` and populate CSV file.

## Generate the PDF report using the CSV data and GeoLite2-Country database

```bash
./fail2ban-report log.csv GeoLite2-Country.mmdb report.pdf
```

Link to GeoLite2-Country database [HERE](http://geolite.maxmind.com/download/geoip/database/GeoLite2-Country.tar.gz).
