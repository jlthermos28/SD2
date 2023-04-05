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

## SETTING UP MYSQL

MySQL is what we used to create and manage our databases using the built in commmand line interface. 

### DOWNLOAD LINKS
First, download and install MySQL. below are the download pages/documentation for MacOS, Windows, and Linux:

[MacOS](https://dev.mysql.com/doc/refman/8.0/en/macos-installation-pkg.html)

[Windows](https://dev.mysql.com/doc/refman/8.0/en/windows-installation.html)

[Linux](https://dev.mysql.com/doc/refman/8.0/en/linux-installation.html)


Once installed, follow the on screen instructions with respect to the installer of the OS that you use. 
(NOTE FOR WINDOWS USERS: YOU ONLY NEED "DEVELOPER DEFAULT", HOWEVER YOU MAY DOWNLOAD THE ENTIRE SQL SUITE IF YOU SO DESIRE.)

### EXAMPLE USING WINDOWS
Since all three of us were on Windows, and since I do not own a Mac or Linux machine, the example I will provide will be with the windows installer. The MacOS and Linux installers may and will be different.

Launch the installer, you will be greeted with this page. Keep the default option and click next.

![Alt text](/mysqlss1.PNG "")

You may be shown this page next, if you are make sure the circle is unchecked and click next. 

![Alt text](/mysqlss2.PNG "")

Then, click yes to this pop up.

![Alt text](/mysqlss3.PNG "")

Click execute here. You should see percentage status indicators under the "Progress" tab for each item as they download. Once done, click next.

![Alt text](/mysqlss4.PNG "")

After clicking next when the downloads have completed, this page will show up. Click execute once more. This will install them. 

![Alt text](/mysqlss5.PNG "")

Once the installation is complete, click next. On the "Product Configuration" page, click next again. You will see the "Type and Networking" page, keep the defaults and click next, the same goes for the following "Athentication Method" page, keep defaults and click next. 

![Alt text](/mysqlss6.PNG "")

On this page, create a strong, yet memorable password. This will be used to log you in to the CLI when you want to interface with MySQL. Once you have typed and retyped your desired password, click on "Add User".

![Alt text](/mysqlss7.png "")

Here, create a user name and MySQL password. Then click "OK". Then  click "Next". 

![Alt text](/mysqlss8.PNG "")

In the "Windows Service" page, keep the defaults and click next.

In the "Server File Permissions" page, keep the defalts and click next.

Once you've made it to this page, click execute. 

![Alt text](/mysqlss9.png "")

Once done, click "Finish", then click "Next".

On this page, keep the defaults and click "Finish", then click "Next".

![Alt text](/mysqlss10.png "")

On this page, enter in the username and password that you created a few steps prior. Make sure to click "check" to esnure that the credentials are correct. If you get the green check mark, like shown in the screenshot, then you have successfully input the correct credentials. Click "Next", then click "Excute".

![Alt text](/mysqlss11.png "")

At this point, you should be here. Click "Finish".

![Alt text](/mysqlss12.PNG "")

Here, click "Finish".

![Alt text](/mysqlss13.png "")

From here it should launch two different windows, you can close out of them both, as we are mainly going to be using the CLI. Press the Windows button and type "command line client" and launch the MySQL 8.0 Command Line Client. Enter the local password that you created. If done successfully, you should see a screen like this:

![Alt text](/mysqlss14.png "")

Congratulations! You have successfully set up MySQL. I know that was quite a bit so take a breath.



