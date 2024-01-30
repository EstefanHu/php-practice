# php-practice

### LAMP
1. Linux
2. Apache
3. MySQL
4. PHP

### PHP Install
sudo apt install php-common libapache2-mod-php php-cli

### SYS ADMIN
Ton on port `80`
option 1:
- sudo /etc/init.d/apache2 start
- sudo /etc/init.d/apache2 stop 

option 2:
- sudo apachectl start       [Start Apache web server]
- sudo apachectl stop        [Stop Apache web server]
- sudo apachectl restart     [Restart Apache web server]
- sudo apachectl graceful    [Gracefully Restart Apache web server]
- sudo apachectl configtest  [Check Apache Configuration]
- sudo apachectl -V          [Check Apache Version]
- sudo apachectl status      [Check Apache Status]

option 3:
- ps -eo comm,etime,user | grep apache2
- ps -eo comm,etime,user | grep root | grep apache2
OR
- ps -eo comm,etime,user | grep httpd
- ps -eo comm,etime,user | grep root | grep httpd

option 4:
- sudo systemctl start apache2
- sudo systemctl stop apache2
- sudo systemctl status apache2

