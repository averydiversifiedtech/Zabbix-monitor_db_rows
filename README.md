# Zabbix-monitor_db_rows
Zabbix template and script to monitor the number of rows in a db (alert on a significant change).

Template to come - scripts are in place.  In our situation we have one very critical database with 18000+ rows.  We have backups, monitoring of mysql, monitoring of replication and routine consistency checks.  However if someone deleted 5000 rows we wanted an alert if the number of rows dropped below a certain threshold so we could look to our backups and restore the deleted data quickly.
