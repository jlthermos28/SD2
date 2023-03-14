## BOOK BUYERS Fictional Company Website 

Marist College CMPT 221 - Software Development II Final Project  
  Development Team: jlthermos28, MarcusVesio, rvarca22.

Designed webpages using HTML, CSS, and PHP for a fictional book retailer company, Book Buyers as a final project. These HTML files were run locally using
  a MAMP server, and eventually were run on an AWS EC2 instance so they could be accessed from anywhere. 
  
Using SQL, we created tables of the company's users, products, and suppliers; each table had a unique login, product, or supplier id code as the table's primary key.
  The user table held information on the company's users, including their active/inactive status, username, password, email, etc. The products table held 
  information regarding the products the company sells (in this case books), including its publication date, price, serial number, etc. Finally, the suppliers table
  held information about the various suppliers the company buys its products from. In the case of book buyers, the suppliers were companies like Amazon, and Barnes 
  and Noble. The supplier table held information such as the supplier's name, address, phone number, etc. 
  
MySQL was used in conjunction with PHP to display the contents of these tables on the webpages. Suppliers and Producer tables can be accessed by any users of the site, while the table of users and explanation of each table was made available only to users with admin access.  

## Using the Book Buyers Site 
 Admin Login Information:  
  username: ryanv  
  password: ryanv1


## HOW TO TEST AND LAUNCH WEBSITE (MAMP/MAMP PRO)

The first thing you'll want to do is to download MAMP/MAMP Pro. The link for this is [here](https://www.mamp.info/en/downloads/).
MAMP allows you to host a local server on your device, and allows other devices on the your network to view your webpage by simply using your IP address.

### SETTING UP MAMP
Once you have installed MAMP/MAMP PRO, open the application (The one with the grey icon, the pro version will prompt you to purchase a license) and hover over the tab that says "MAMP". 

![Alt text](/mampstep1.png "")

Then, click on preferences.

![Alt text](/mampstep2.png "")

Navigate over to Web Server and make sure that the document root is set to the file path where you cloned this repo

![Alt text](/mampstep3.png "")
