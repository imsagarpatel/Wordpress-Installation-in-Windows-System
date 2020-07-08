# Wordpress-Installation-in-Windows-System

## 1. System Requirements for WordPress:
#### WAMP SERVER: MySQL 5.0+	
#### WAMP SERVER:
WAMPSERVER 64 BITS (X64) 3.2.0: https://www.wampserver.com/en/#wampserver-64-bits-php-5-6-25-php-7

WAMPSERVER 64 BITS (X64) 3.2.0: https://www.wampserver.com/en/#wampserver-32-bits-php-5-6-25

#### OPERATING SYSTEM: Windows-platform	
#### Browser Support: IE (Internet Explorer 8+), Firefox, Google chrome, Safari, Opera


## 2. Download and Install WampServer:

WAMPSERVER 64 BITS (X64) 3.2.0: https://www.wampserver.com/en/#wampserver-64-bits-php-5-6-25-php-7

WAMPSERVER 32 BITS (X86) 3.2.0: https://www.wampserver.com/en/#wampserver-32-bits-php-5-6-25

Step 1: Click on .exe to install wampserver

Step 2: Accept agreement and click on NEXT

Step 3: Click on NEXT 

Step 4: Browse and select destination location
  
Step 5: Choose default installation components and click on NEXT
 
Step 6: Browse Start Menu Folder location 
  
Step 7: Click on INSTALL to complete installation process 

Step 8: Click on FINISH after installation process complete
 
## 3. Download WordPress:

Open the link https://wordpress.org/download/ Download the WordPress 5.4.2 zip file from the official site

## 4. Create Database into PhpMyAdmin:

Step 1: Open WampServer from start menu
 
Step 2: 
In case of error download & install Microsoft Visual C++ 2010 Redistributable Package (x64) – https://download.microsoft.com/download/3/2/2/3224B87F-CFA0-4E70-BDA3-3DE650EFEBA5/vcredist_x64.exe

Step 3: Wait until green logo appear on the bottom right task bar 

Step 4: 
Open any of the supported browser and type localhost/phpMyAdmin to create database. Click on Go button. 

Step 5: Click on database tab and then enter name of the database.
 
	Database Name: Test

## 5. Set Up WordPress Locally

Step 1: Extract the downloaded WordPress folder and upload it into your web server or localhost. Extract here: C:\wamp64\www
-	Here www is the root folder of the localhost server 

Step 2: Open your browser and navigate to your WordPress file path, then you will get the first screen of the WordPress installer as shown in the following screen. In our case, the path is localhost/< Your_WordPress_folder >. Example: Localhost/wordpress
 
Step 3: Select your language for the WordPress and click on Continue.
 
Step 4: In this step, you can view the information needed for the database before proceeding with WordPress installation. Click on Let's go!

Step 5: Enter the information about the MySQL database as described in the following screen.
 
- Database Name: Enter the database name which you have created in MySQL database for WordPress.

-	Username: Enter the user name of your MySQL database.

-	Password: Enter the password which you had set for MySQL database.

-	Database Host: Write the host name, by default it will be localhost.

-	Table Prefix: It is used to add prefix in the database tables which helps to run multiple sites on the same database. It takes the default value. 

After filling all information, click on Submit button.

Step 6: WordPress checks the database setting and gives you the confirmation screen as shown in the following snapshot. Click on Run the install

Step 7: Enter administrative information.

-	Site Title: Enter the name of the site which you are going to create in WordPress.

-	Username: Enter the username as per your choice while logging in the WordPress.

-	Password: Enter password to protect your site.

-	Your E-mail: Enter your e-mail address which helps to recover the password or any update.

-	Search Engine Visibility: It allows the search engine to index this site after checking the checkbox

After filling all the information, click on the Install WordPress button.

Step 8: After installation being successful, you will get a screen of the stating success as seen in the following screen. You can view your username and password detail added in WordPress. Click on Log In button.

Step 9: After clicking on login, you will get a WordPress Admin Panel as depicted in the following screen.

#### Enter the username and password which you had mentioned during installation as shown in step 6 and click on the Log In button.
