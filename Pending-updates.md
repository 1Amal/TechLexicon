Place to add all updates to the reference database before they are entered into the database. Use this document as an Draft. 

**************** Pending updates ****************

*** JavaScript ****


**** Git *****

*** VS Code ****


***React***

***** Linux *****


***** Microsoft Windows *****


***** Raspberri Pi ***** 

****  VS Code *****

*******************
Programming Concepts

*****Ubuntu*****
Restart the desktop portal to free up memory due to bug in Ubuntu
systemctl restart --user xdg-desktop-portal-gnome.service

Force Update Google chrome that cannot be upgraded automatically
Fist download the deb file and run this command on the deb file
sudo apt update && sudo apt upgrade && sudo apt install ./google-chrome-stable_current_amd64.deb



*****NodeJs****
npm init -y  to start the package.json file 

npm install express express-session pg passport passport-local ejs express-validator bcryptjs

Enter the PostgreSQL shell by running psql in your terminal. You can view the current dbs using the \l command. To create a new db by running the following SQL statement:

CREATE DATABASE top_users;
\l again to see if the db was created. 

To connect to the db:

\c top_users

Verify that the psql prompt should be:
top_users=#

Now create a table and its columns to store username data:

CREATE TABLE usernames (
   id INTEGER PRIMARY KEY GENERATED ALWAYS AS IDENTITY,
   username VARCHAR ( 255 ) 
);

Verify that the table has been created by running \d. You should see the following two tables in the output (we’ve skipped some output details for brevity):

use psql to create a table using following SQL
CREATE TABLE users (
   id INTEGER PRIMARY KEY GENERATED ALWAYS AS IDENTITY,
   username VARCHAR ( 255 ),
   password VARCHAR ( 255 )
);






