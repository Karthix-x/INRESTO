# INRESTÒ 

INRESTÒ is an android application adeals with the problems of managing the restaurant and avoids problems that occur when carried out manually. E-POPINA will improve its services for all the customers of the restaurant. The admin will have access to employee details, employee attendance. He can receive orders from customers and send the takeaway orders to the kitchen supervisor. The waiter will have access to the inmate details, bills. The supervisor in the kitchen view’s the orders sent by the waiter and the admin and specifies the orders to the respective cook.

# Features
#### Admin Features:
 An Administrator provides administrative support to either a team or individual. This role is vital for the smooth-running of a business.

*	Scan QR code: A unique QR code will be assigned for each employee, admin will scan the QR code for attendance purpose.
*	View attendance: The attendance of each employee can be viewed.
*	Menu management: The menu can be completely modified and new items can be added, deleted and update price also. This updated menu will be displayed on the waiter’s device also.
*	Catering: The customer’s details and respective orders are stored along with the date of delivery. 
*	Takeaway: The takeaway orders will be taken by the admin which will be sent to the kitchen supervisor and admin will generate bills of takeaway ordes.
*	Report: The report can be generated of two types daily report and monthly report 
*	The daily report consist of the total of all the bills table orders and takeaway orders of each day
*	The monthly report admin have to enter the cost like electricity bill, water bill, etc. and the total report will be generated and the admin have to take screenshot manually in order to save the report.
*	Employee management: Admin has control over the employees he can add new employee,  and also view details of them 


#### Waiter Features:
	 
  Waiters are responsible for taking orders and serving food and beverages to guests. They play an important role in guest satisfaction as they are also responsible for checking on customers to ensure that they are enjoying their meals and take action to correct any problems.
*	Orders: The table orders are accepted by the customer and confirmed by the waiter the order list containing table number will be sent to kitchen supervisor app.
*	Update orders: If the customer needs to update order can be done.
*	Bill: The bill will be generated according to the table number and displayed to the customer from the waiter’s device, the customer later pays the bill.

#### Kitchen Features:
A kitchen is a room or part of a room used for cooking and food preparation in a dwelling or in a commercial establishment. 

*	The orders placed by the waiter and admin will be displayed in the device placed in the kitchen.
*	The supervisor assigns orders to the cook, the cook prepares the order and the waiter serves the order to the respective table.
*	Food ready: When the food is ready the supervisor taps the button and the waiter will be notified by the table number.  

#### Product Features

*	Multiple orders can be taken by the waiter.
*	Employee details and new employee registration.
*	Admin can control the menu and disable the item which is out of stock and also to change the menu contents by adding or deleting an item or changing its price.	
*	Catering information can be stored and helps to remember.
*	The monthly report can be generated  by entering electricity bill, water bill, miscellaneous expenses we can generate a monthly  report of hotel 
*	Each employee will be provided with a unique QR code which will scanned by the admin manually in order to provide attendance.
*	Salary will be calculated according to the attendance of the employee
#### Product Perspective

It is a standalone system. It is responsible for managing the entire functioning of the restaurant and details of the employee. Reports can be generated at the end of the month and daily expense and remains are tallied. Bills are calculated according to the orders given by the customer which are placed by the waiter.

![image](https://user-images.githubusercontent.com/57553824/120515123-a18c7600-c3eb-11eb-8779-96f86fca6ae7.png)


### Assumptions and Dependencies

*	We assume Admin, waiter and kitchen supervisor devices should be connected to the same configured Wi-Fi network.
*An assumption is that a order given cannot not be cancelled.
*	Xampp server should be started. 
 
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

