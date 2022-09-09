# PWEB STACK IMPLEMENTATION (LEMP STACK)
### for PBLProject-2

*sudo apt update*
![sudo apt update](./images/Launched%20an%20instance.png)
*sudo apt install nginx*
![sudo apt install nginx](./images/sudo%20apt%20install%20nginx.png)

*sudo systemctl status nginx*
![sudo systemctl status nginx](./images/sudo%20systemctl%20status%20nginx.png)

*curl http://localhost:80
![curl http://localhost:80](./images/curl%20httplocalhost80.png)

*http://<Public-IP-Address>:80*
![http://<Public-IP-Address>:80](./images/curl%20httplocalhost80.png)

*STEP 2 — INSTALLING MYSQL*
![sudo apt install mysql-server](./images/sudo%20apt%20install%20mysql-server.png)

**sudo mysql**
![sudo mysql](./images/sudo%20mysql.png)

**setting up mysql**
![setting up mysql](./images/setting%20up%20mysql.png)

**Step 3: Installing PHP**
![sudo apt install php-fpm php-mysql](./images/sudo%20apt%20install%20php-fmp%20php-mysql.png)

**STEP 4 — CONFIGURING NGINX TO USE PHP PROCESSOR**
![installing & testing the nginx](./images/testing%20nginx%20config%20for%20errors.png)

![opening the website via IP address](./images/Opening%20website%20URL%20using%20IP%20address.png)
**STEP 5 – TESTING PHP WITH NGINX**
***Create the file either using nano or vi :<?php
phpinfo();
![http://3.84.52.1/info.php](./images/php%20server%20domain.png)
**STEP 6 – RETRIEVING DATA FROM MYSQL DATABASE WITH PHP (CONTINUED)**
![CREATE DATABASE SamDB](./images/Creating%20and%20viewing%20a%20datatbase.png)
![CREATE USER and Populate the todo.lisst table](./images/Inserting%20into%20the%20table.png)

![connecting .todo_lisst.php to Mysql server](./images/PHP%20environment%20connected%20to%20Mysql%20server.png)