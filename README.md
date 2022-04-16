# 👨‍🍳 Restaurant Management System

## Project Description
DineOut is an **Android based Restaurant Management System** that aims to digitalize the process of various restaurant operations including **ordering, billing kitchen, hall and inventory management**. This project is made by using MVC pattern. In the app file you will be able to see all the java file and also MVC pattern.
This will help to maintain a digital restaurant management system. 


## User Classes and Characteristics
There are **five** types of users for my system. 

### 1. Customer Class
Customers interact with our system directly in order to place order, modify order, get bill and give feedback. We do not store any information related to customers in our system. The process of order taking starts from customers placing order and then the other series of events begin.

### 2. Head Chef/Kitchen Manager
Head Chef can mark a dish as prepared when a chef tells him to do so. He can approve the cancellation of an order whenever a customer edits or removes a dish from his order. He can also assign a dish to a particular chef based on the specialty of the chef.

### 3. Chef
Chefs don’t interact with the system. They just have to look at the dishes present in their queues and prepare the dishes accordingly. Chef’s name, address and specialty etc. are stored in the database.

### 4. Admin
Admin’s job is to manage the inventory and other information related to menu and chefs in the system.

### 5. Hall Manager
Hall Managers will provide its input when he marks the bill as paid when customers pay for their order or get the bill printed. Moreover, he gets a notification whenever a particular order is complete, or some customer asks for help through the system. Hall manager can also see tables in the hall and their status i.e. empty or filled.


## How to Run

In order to have a look at the code files and understand the working, simply download this repository and open Android Studio and browse to the downloaded project and open it. It will load the project files and the code will be ready to run. 

Before running the app, use your Google Account to register this Application on Firebase Console, with any name you want. Using your Google Account, login to Android Studio. Then you can run the project.

The login credentials for Admin, Hall and Kitchen Manager's interfaces are:
- admin@gmail.com
- chef@gmail.com
- hallmanager@gmail.com

All have the password: 123456


