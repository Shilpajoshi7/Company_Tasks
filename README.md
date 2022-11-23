# My_Company_Tasks

#___________________________________________Task1 :Deploy a PHP Application using Azure Virtual Machine on Apache Server______________________________________________

sudo apt-get update
sudo apt-get install apache2
sudo apt-get install php libapache2-mod-php
sudo apt install php-dev libmcrypt-dev php-pear
sudo pecl channel-update pecl.php.net

->> yha pe latest dalna hei otw error 1.0.1 xxx
sudo pecl install mcrypt-1.0.5

sudo service apache2 restart
cd /var/www/html
sudo rm index.html
sudo nano test.php


https://medium.com/analytics-vidhya/learn-to-deploy-a-php-application-using-amazon-ec2-instance-cb0c212e6362



#_________________________________________Task2 Deploy django application on Azure Virtual Machine in apache and nginx server__________________________________________

->> Link simply apache se kiya django ka rocket aara (Koi hello wrold application nhi banaye)
https://www.digitalocean.com/community/tutorials/how-to-serve-django-applications-with-apache-and-mod_wsgi-on-ubuntu-14-04


#___________________________________________________________Task3 Load Balancer_______________________________________________________________________________________

-->> Task1) Load Balancing This is VM1 refresh This is VM2 
-->> Task2) Autoscaling 

_____Task1_____

1) VM1 mei ssh karke  VM2 mei bhi same karna hei  
cd downloads --->>key downloads mei save hoti hai
ssh ka link key daal ke ex ssh -i key1.pem azureuser@20.168.231.212

2) Apache daala aur page moify karna 
sudo apt update
sudo apt install apache2
sudo service apache2 start
cd /var/www/html
sudo rm index.html
sudo vi index.html
<h1> This is VM1 </h1>

__________Task2_________
Take help from 
https://www.youtube.com/watch?v=xD9MVGY216o

 yes >/dev/null &
 top

#___________Task4 Deploy Reactjs Application on Azure App Service and distribute traffic through AZ Traffic manager  __________

xxxxxxx https://websitebeaver.com/deploy-create-react-app-to-azure-app-services If u want ot try it using github pipeline xxxxxxx

correct way deploy reactjs application on azure app service from vs code   (VS codeko use karke)

https://medium.com/geekculture/easiest-way-to-host-your-react-app-azure-vs-code-8046f9f7fb0b
https://medium.com/ms-club-of-sliit/deploy-a-react-app-using-azure-app-service-from-vs-code-57643313f53c


create a folder open it on VS Code
Now go to vs code terminal 

npx create-react-app shilpa    (Folder ka naam shilpa de re mei)
cd shilpa
npm start




->> agar aysa eroe ayega toh 
Error  npm ERR! code ERR_SOCKET_TIMEOUT    ( I Think yeh sirf network connectivity issue hei Internet problem )
Soln   npm cache clear --force

Add Custom Domain to Traffic Manager
https://www.youtube.com/watch?v=1ggz9qZpVHo







