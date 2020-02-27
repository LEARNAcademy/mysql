# mysql

use homebrew to install mysql on mac
https://gist.github.com/nrollr/3f57fc15ded7dddddcc4e82fe137b58e

download and install mysql workbench
https://downloads.mysql.com/archives/workbench/

download and install mysql community server (write down the password!)
https://dev.mysql.com/downloads/file/?id=492026


mysql -u root -p
CREATE DATABASE database_name
CREATE USER 'root'@'%' IDENTIFIED BY 'root';
GRANT ALL PRIVILEGES ON *.* TO 'root'@'%'

ALTER USER 'yourusername'@'localhost' IDENTIFIED WITH mysql_native_password BY 'youpassword';

https://dev.mysql.com/doc/refman/8.0/en/resetting-permissions.html

