README
================
SQLi-Labs by AUDI-1 has been our friend since the days of backtrack and it has helped us learn the basics of sql injection since then. Earlier, these labs used to work on backtrack and as the time changed, we got our hands on Kali 2.0 where we were unable to run SQLi-Labs due to the point that SQLi-Labs are old to run on Kali 2.0.

I have updated the code so as to make it run on Kali 2.0 so that all of us can use the same labs once again and continue to learn sql injection on Kali 2.0

============================================================================
Install Instructions:

1. Unzip the contents inside the apache folder, for example under /var/www/html
2. This will create a folder sql-labs under it. else you can use git command from within /var/www/html folder.
/var/www/html folder and then use following command> https://github.com/mukkul007/sqli-labs-kali2.git sqli-labs
3. Open the file "db-creds.inc" which is under sql-connections folder inside the sql-labs folder.
4. Update your MYSQL database username and password.(default for Kali are used root:<no password>)
* 5. Since, there is no password on mysql/mariaDB on kali linux you can use below link to change your mysql password in order to use it in the 4th step. (https://www.digitalocean.com/community/tutorials/how-to-reset-your-mysql-or-mariadb-root-password)
6. From your browser access the sql-labs folder to load index.html
7. Click on the link setup/resetDB to create database, create tables and populate Data.
8. Labs ready to be used, click on lesson number to open the lesson page.
9. Enjoy the labs

============================================================================
SQLI-LABS is a platform to learn SQLI 
Following labs are covered for GET and POST scenarios:

1. Error Based Injections (Union Select)
	1. String
	2. Intiger
2. Error Based Injections (Double Injection Based)

3. BLIND Injections:
	1.Boolian Based
	2.Time Based
4. Update Query Injection.
5. Insert Query Injections.
6. Header Injections.
	1.Referer based.
	2.UserAgent based.
	3.Cookie based.
7. Second Order Injections
8. Bypassing WAF
	1. Bypassing Blacklist filters
		Stripping comments
		Stripping OR & AND
		Stripping SPACES and COMMENTS
		Stripping UNION & SELECT
	2. Impidence mismatch
9. Bypass addslashes()
10. Bypassing mysql_real_escape_string. (under special conditions)
11. Stacked SQL injections.
12. Secondary channel extraction

and many more have been covered. Have a look at all the sections by using the labs.


============================================================================
