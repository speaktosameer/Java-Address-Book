# Java-Address-Book
This Java Address book contains my sql server you need to setup.
After the complete setup of mysql open workbench and enter the following query.

create database MJProject
use MJProject
create table login(
username varchar(20),
password varchar(10)
);
create table AddressBook
(
Name varchar(20),
CellNumber varchar(20),
Email varchar(20),
Residence varchar(20)
);
insert into login values('admin','admin');

Note: If you are using NETBEANS for this project please download MYSQL Connector 
from the official page of MYSQL and add to the library folder and then u need to run the project.
Hope  u like the Work.

#Thank you!!!!
