# NET2FTP

**NET2FTP INSTALLATION INSTRUCTIONS**

(For upgrade instructions read below.)

To view the detailed installation instructions, open the /files_to_upload/help.html 
file in a browser, and click on Administrator.

In a few words:

1. Unzip all the files on your computer, and upload them to your web server.
1. The /temp directory should be chmodded to 777. 
1. Set your settings in the settings.inc.php file.
1. A database is only required if you want to log the actions of the users, or  if you want to enable the daily consumption limit. To create the tables, execute the SQL queries in the "create_tables.sql" file. This can be done easily in PhpMyAdmin, the popular front-end to MySQL.

To integrate net2ftp with Mambo, Drupal or Xoops, follow the instructions in 
the readme.txt files in the respective directories under */integration_in_other_PHP_applications*.

Enjoy!

***

**UPGRADE**

net2ftp cannot really be "upgraded" - simply delete the old files on your web 
server, and follow the installation instructions above.

If you are using a database for logging, drop the old tables and create new 
ones following the installation instructions. This will delete the existing 
statistics.

Enjoy!

***

[Official Website](http://www.net2ftp.com/index.php?state=login "Visit Official Website of net2ftp!")
