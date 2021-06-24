# INRESTÒ 

| <img src=https://user-images.githubusercontent.com/57553824/121926835-ff11b280-cd5b-11eb-99eb-b96fc95cdeed.png width="100" height="100">  | <img src=https://user-images.githubusercontent.com/57553824/121927109-4e57e300-cd5c-11eb-812b-8211564be535.png width="100" height="100"> | <img src=https://user-images.githubusercontent.com/57553824/121928589-eb674b80-cd5d-11eb-9860-1a70a97ef1f0.png width="100" height="100"> |
|:---:|:---:|:---:|
| INRESTÒ_ADMIN | INRESTÒ_KITCHEN |INRESTÒ_STAFF | 

INRESTÒ is a set of 3 android applications adeals with the problems of managing the restaurant and avoids problems that occur when carried out manually. INRESTÒ will improve its services for all the customers of the restaurant. The admin will have access to employee details, employee attendance. He can receive orders from customers and send the takeaway orders to the kitchen supervisor. The waiter will have access to the inmate details, bills. The supervisor in the kitchen view’s the orders sent by the waiter and the admin and specifies the orders to the respective cook.



### Product Features

*	Multiple orders can be taken by the waiter.
*	Employee details and new employee registration.
*	Admin can control the menu and disable the item which is out of stock and also to change the menu contents by adding or deleting an item or changing its price.	
*	Catering information can be stored and helps to remember.
*	The monthly report can be generated  by entering electricity bill, water bill, miscellaneous expenses we can generate a monthly  report of hotel 
*	Each employee will be provided with a unique QR code which will scanned by the admin manually in order to provide attendance.
*	Salary will be calculated according to the attendance of the employee

### Assumptions and Dependencies

*	We assume Admin, waiter and kitchen supervisor devices should be connected to the same configured Wi-Fi network.
*	An assumption is that a order given cannot not be cancelled.
*	Xampp server should be started. 
*	For client needs we have created only 10 tables in the Staff App.
*	We presume the admin generates the QR code using the Admin app and attaches it to employees' physical ID cards.
*	Bills are generated in the mobile and no paper copy will be provided; the customer can pay the bill amount in cash or using UPI payments available at the cash counter.

	

#### Product Perspective

It is a standalone system. It is responsible for managing the entire functioning of the restaurant and details of the employee. Reports can be generated at the end of the month and daily expense and remains are tallied. Bills are calculated according to the orders given by the customer which are placed by the waiter.

![image](https://user-images.githubusercontent.com/57553824/120515123-a18c7600-c3eb-11eb-8779-96f86fca6ae7.png)



 
### Software Interfaces
* Backend: PHP 7.1
* Frontend: XML, Java
*	Database:  My SQL
*	Coding platform: Android Studio v3.5
*	Web server: XXAMP local host.
* Database: MySQLi

## Installation
*	Installing xampp to the system
*	Copying PHP files to the htdocs folder.
*	Importing the SQL file to PHP Myadmin.
*	Configuring the IP address of Wi-Fi network to all the three apps in the utility file as shown in the screen shot below.
*	Installing the apps to the android phone.
*	Connecting the mobile phone to the configured Wi-Fi network(we assume apache and MySQL is started).
*	App is ready to operate.

![image](https://user-images.githubusercontent.com/57553824/120513279-bbc55480-c3e9-11eb-87c0-bfa1101d3e0a.png)


# Use case diagram
![image](https://user-images.githubusercontent.com/57553824/120513797-3db57d80-c3ea-11eb-9f36-9eb9f5f6f72b.png)
 
 # Flow Chart
 ![image](https://user-images.githubusercontent.com/57553824/120513923-5c1b7900-c3ea-11eb-9cba-1604667da26e.png)

