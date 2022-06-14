# Hospital-Management-System

## Project Background
As technology continue to advance, many systems have now involved automation and high tecnology to solve real-life problem, so does medical field. Thus, we were given a chance to build a Hospital Management System Project in C++. It is a simple console application to store Patients' information which will be stored as text files.
Our Hospital Management System have the following features:
- Maintain Patients' Medical Records
- Assign doctors for the patients
- Update patients' medical treatment and condition
- Display Patients' information to doctor

*Mutiple folder and text files must be created to run this application and be discussed in the System Design*
## Objective of This Project
- To store the details of patient to make a convenient and swift access for later references.
- To keep track of patient medical records for the appropriate specialization doctor or emergency services.
- To provide an interface for data management system.

## System Design

### HMS Flowchart


### GUI's
We have used components from Swing and AWT Libraries to design the GUI.

#### 1. Login GUI
![loginGUI](https://user-images.githubusercontent.com/107078925/173621876-15a31249-4079-4f12-8963-7b8aac0baca9.jpg)

Login GUI is the first GUI that user will be seeing when he/she runs the application. If the user is an employee, he/she can proceed to check the salary slip provided administrator has updated their salary. If the user is an administrator, he/she shall enter the username and password. If you want to change the password and user, you will need to change it at LoginGUI.java at following lines:

`if (stradmin.equals("admin") && strpass.equals("admin")) {`

'admin' is the username and password in our employee payroll management system

#### 2. Admin GUI
![Admin_GUI](https://user-images.githubusercontent.com/107078925/173625287-9f1493db-551e-4eb2-968e-841a06ed5751.jpg)

Admin GUI consists of the following features:
- Add New Employees
- Display Employee Information
- Salary Calculation based on Days and Rate Per Day

#### 3. Salary Slip GUI
![Salary Slip GUI](https://user-images.githubusercontent.com/107078925/173625323-59b84938-32c0-4e66-bcf9-12ba8b7e25a8.jpg)

This GUI is used to display Salary to employee after user key in his/her ID in the Login GUI. It has the 'print' button that allow user to print the salary slip to PDF.

### Database
All the functions that used to manipulate data in the database are defined in Database.java, change the username and password in the source code to your database's username and password.

`this.connect_db = DriverManager.getConnection(url, "root", "password");`

### Requirements
In order to run this application, you will need to install MySQL and its workbench to create a database to store employees' information. You can use other method to create the database and table, but MySQL workbench is the most convienient to do so. Following picture shows the column name in the employee table.

![column_name](https://user-images.githubusercontent.com/107078925/173625358-01df2941-6d8a-40d4-b436-5898c797b375.png)

## :clap: Project Members
- Bryan Keane
- Lim Zhi Min
- Ahmed Rafat
- Kong Ping Hao
