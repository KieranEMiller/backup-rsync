# backup-rsync
a set of BASH scripts that wrap and leverage the rsync utility to backup one or more directories on a filesystem

## prerequisites:
1. rsync utility
1. if you are on a windows system you will need cygwin

## setup:
1. set paths in backup.conf
1. update backup-includes.txt to target the directories you want to back up

## execution
does not accept any arguments, configuration is run entirely from the backup.conf file
