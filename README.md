# S_Tasks

#______________________________________________Task1 :Deploy a PHP Application using Azure Virtual Machine on Apache Server______________________________________________

sudo apt-get update
sudo apt-get install apache2
sudo apt-get install php libapache2-mod-php
sudo apt install php-dev libmcrypt-dev php-pear
sudo pecl channel-update pecl.php.net

# yha pe latest dalna hei otw error 1.0.1 xxx
sudo pecl install mcrypt-1.0.5

sudo service apache2 restart
cd /var/www/html
sudo rm index.html
sudo nano test.php


https://medium.com/analytics-vidhya/learn-to-deploy-a-php-application-using-amazon-ec2-instance-cb0c212e6362



#___________________________________________Task2 Deploy django application on Azure Virtual Machine in apache and nginx server__________________________________________

# Link simply apache se kiya django ka rocket aara (Koi hello wrold application nhi banaye)
https://www.digitalocean.com/community/tutorials/how-to-serve-django-applications-with-apache-and-mod_wsgi-on-ubuntu-14-04


