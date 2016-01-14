# dbatools
Unix database tools for Oracle database admin tasks

This is a set of shell and perl script to aid in the general day to day DBA tasks for an Oracle database

The tools must be installed on each database server as the same user account as the oracle server software.

There are a number of utilities split up into the type of task you wish to perform. The overview is

dbinfo  - general database information (read only)
dbuser  - view and update database user details
dbtbs   - view and update database table space details
dbrman  - automate RMAN tasks (chrosscheck, register, list, validate, restore Point in time)
dbsql   - run a variety of reports about SQL code (sql report, explain plan, bind hist, sql tune)
dbreport - allow user/project sql reports to be run in a controlled way

