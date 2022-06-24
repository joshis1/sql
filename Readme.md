# Getting Started 

## Install Oracle database version - XE ( express edition) 18c -> Free

* https://www.oracle.com/au/database/technologies/xe-downloads.html
* https://www.oracle.com/database/technologies/xe18c-downloads.html
* Extract the zip 
* Run the installer.
* Change the location to install at C:\Users\shrey\AppData\18.0.0
* Give password that will be used by SYS, SYSTEM and PDBADMIN.
* In the end, it tells it will be running on localhost and port number 1521.

## Test the basic connnection using windows.
* sqlplus / as sysdba

# SQL Developer 
* Write SQL 
* PL/SQL IDE 
* Database administration

## Install SQL Developer 
* https://www.oracle.com/tools/downloads/sqldev-downloads.html
* Extract it, it simply contains the executable - sqldeveloper.exe

## Test the connection using SQL Developer 
* Create a connection 
* username  - sys as sysdba 
* password - the one you gave during installation.


# Don't use sysdba user for playing around.
* use a separate account for playing with sql db.



