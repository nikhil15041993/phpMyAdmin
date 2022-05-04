# phpMyAdmin


phpMyAdmin is a free web application that provides a convenient GUI for working with the MySQL database management system

### Prerequisites

* An Ubuntu 20.04 server. This server should have a non-root user with administrative privileges and a firewall configured with ufw. To set this up, follow our initial server setup guide for Ubuntu 20.04.
* A LAMP (Linux, Apache, MySQL, and PHP) stack installed on your Ubuntu 20.04 server. If this is not completed yet, you can follow this guide on installing a LAMP stack on Ubuntu 20.04.


## Step 1 — Installing phpMyAdmin

### 1. First install apache2  
```
sudo apt-get install apache2
```
### 2. moving to the root directory type the command : 
```
Sudo su 

sudo apt-get update && sudo apt-get upgrade
```
### 3. Now to install the lamp server type the command:
```
apt-get install lamp-server^
```
### 4. install phpmyadmin type the command as 
```
apt-get install phpmyadmin –y
```
One dialog box will appear and select the ‘apache2’ by pressing spacebar.
Now configuring phpmyadmin dialog box will appear and select ‘yes’ after that give the password in my case it’s  ‘admin’ 🡪 This password is of ‘root   password’ 

Now, goto the php directory as:-
    ```
    cd /var/www/html/
    ```
To see the php version you are using create info.php using command as:-
      ```nano info.php```
 after that type the code as:-
 ```
   phpinfo();    
 ```
 
 Now goto the browser and type ‘localhost/info.php’ and phpmyadmin for <ip address/phpmyadmin>
 
 ## Step 2 — Adjusting User Authentication and Privileges
 
 
