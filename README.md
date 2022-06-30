# OccupancyDetectionSystem
Software needed to run the app:

Any software which supports java and swing (eg. Eclipse, netbeans) and My SQL workbench.


In order to run the program follow these steps:

Step 1 Extract the zipped folder .
Step 2 Open the folder in any IDE which you are using(eg. Eclipse , netbeans)
Step 3 Create three databases in your My SQL workbench. The details of the databases are given below

1st database


create database udetail;
use udetail;
create table totalSeats(
	capa int default null,
    aval int default null
    );
create table udetails(
uname varchar(30) ,pword varchar(60),checkin time,checkout time);

2nd database

create database usportal;
use usportal;
create table usdetails(
	usName varchar(30),
    usPhone bigint,
    usAddress varchar(100),
    usEmail varchar(30),
    usPassword varchar(300) DEFAULT NULL
);

3rd database

create database adportal;
use adportal;
create table addetails(
	adName varchar(30),
    adPhone int,
    adAddress varchar(100),
    adEmail varchar(30),
    adPassword varchar(300) DEFAULT NULL
);

Step 4 Now click on the run button.


There is no preset user id and password in this project . If the user is not already present in the database he/she must first register into the database by clicking on the signup button.


						   *********
