# dbatools
Unix database tools for Oracle database admin tasks

This is a set of shell and perl script to aid in the general day to day DBA tasks for an Oracle database

The tools must be installed on each database server as the same user account as the oracle server software.

There are a number of utilities split up into the type of task you wish to perform. The overview is

|Script|Description|
|------|-----------|
| dbinfo  | General database information (read only)|
| dbuser  | View and update database user details|
| dbtbs   | View and update database table space details|
| dbrman  | Automate RMAN tasks (chrosscheck, register, list, validate, restore Point in time)|
| dbsql   | Run a variety of reports about SQL code (sql report, explain plan, bind hist, sql tune)|
| dbreport | Allow user/project provided sql reports to be run in a controlled way|

