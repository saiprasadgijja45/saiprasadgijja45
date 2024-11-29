## Hi there 👋
Web Based Graphical Password Authentication System
In this project we are authenticating users via images and this images will be uploaded at signup time and then ask user to click on image 4 times to select 4 different spots and user has to remember those points.
It’s difficult for user’s to select correct pixel X and Y location from mouse click so we provide region based authentication for example
If user select X = 120 and Y = 240 from mouse click then while authentication I deducted 10 pixels from X value and added 10 more pixels to X values which means
If user select X value between 110 to 130 and Y value between 230 and 250 then user get authenticated as actual or original X value 120 and Y value 240 falls between 110 to 130 and 230 to 250
To run project install python 3.7 and MYSQL and then copy content from DB.txt file and paste in MYSQL to create database
To implement this project we have designed following modules
1)	Admin Login: using this module admin can login to application using username and password as admin and then after login can view all registered user details 
2)	New User Signup: using this module user can signup with the application and has to upload image in place of password and then select 4 spots and all this details will saved in database
3)	User Login: using this module user can login to application by entering USERNAME and then image will be displayed and user has to select correct spots to get authenticated
4)	Reset Password: after login user can update password image and can enter new spots to reset password
SCREEN SHOTS
To run project double click on ‘run.bat’ file to start DJANGO server like below screen



