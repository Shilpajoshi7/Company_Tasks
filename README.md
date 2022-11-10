# S_Tasks

#Task1 :Deploy a PHP Application using Azure Virtual Machine on Apache Server
sudo apt-get update
sudo apt-get install apache2
sudo apt-get install php libapache2-mod-php
sudo apt install php-dev libmcrypt-dev php-pear
sudo pecl channel-update pecl.php.net
sudo pecl install mcrypt-1.0.1
sudo service apache2 restart
/var/www/html
sudo rm index.html
sudo nano test.php
