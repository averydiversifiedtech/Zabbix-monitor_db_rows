#!/bin/bash
databaseandtable="$1"
result=`mysql --defaults-extra-file=/etc/zabbix/.my.cnf -e "select count(*) from $databaseandtable"`
cleanresult=`echo $result | sed 's/^.*count(\*) //'`
echo $cleanresult
