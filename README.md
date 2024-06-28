Login Details
Username: admin
Password: admin123
How To Run Project?
To run this project, you must have installed a virtual server i.e XAMPP on your PC (for 
After Starting Apache and MySQL in XAMPP, follow the following steps
1st Step: Extract file
2nd Step: Copy the main project folder
3rd Step: Paste in xampp/htdocs/
Now Connecting  DB 
4th Step: Open a browser and go to URL “http://localhost/phpmyadmin/”
5th Step: Then, click on the DB tab
6th Step: Create a DB naming “pharmacy” and then click on the import tab
7th Step: Click on browse file and select “pharmacy.sql” file
8th Step: Click on go.
After Creating Database,
9th Step: Open a browser and go to URL http://localhost/Pharmacy-Management/
NB
 The SQL export is missing IS_LOGGED_IN column from the admin_credentials table.
To get around this, add IS_LOGGED_IN column to admin_credentials table
