# MTB
website for MTB
issues:
=-----------------
Problem1:-----------
ImportError: Couldn't import Django. Are you sure it's installed and available on your PYTHONPATH environment variable? Did you forget to activate a virtual enviro
nment?

 Solution1:
 ------------------------
 1.Need to activate virtual environment
	try to upgrade pip
 2.Check all the required libraries are installed or not
 
 
 
 Problem2:
 -------------------------------
 SQL db connection related :
	Ex:- 	1.For password expaired 
			2.For new connection
 Solution2:
 ------------------------
 Need to alter user for system and follow the steps below.
 
	1.Open cmd prompt from windows
	2.Execute sqlplus /nolog
	3.Execute conn /as sysdba
	4.Alter the user by using the following command
		 ALTER USER system IDENTIFIED BY tiger;  --> for system(user name) user 
 
 For hrms Project:
 -------------------------
 if set DJANGO_SETTINGS_MODULE=HRMSPROJECT.
settings
For other Project:---
-----------------------
set DJANGO_SETTINGS_MODULE=

For git :;
-------------
open git bash 
go to your work project location 
git init

create git repo in git hub

go to pycharm 
go to project location 
git clone repository
git add files 
git push 
note: if face any issues then update git 
        windows: git update-git-for-windows
        Linux/Unix: git update