# Ecommerce App using ASP.NET Core and Angular

An ecommerce app for selling Skiing equipments list used Stripe for payment processing.

**Team Members**
---
* Piyush Jagtap
* Omkar Dedge
* Sanket Auti
* Umesh Ugale
* Every contributed to all the parts of the project

**Client side technologies used are**:
* Angular 9
* Bootstrap 4
* ngx-bootstrap
* Font Awesome
* RXJS
* Material-ui

**Server side technologies used are**:
* .Net Core
* Generic Repository Patterns
* Redis Cache
* Sqlite
* AutoMapper
* Entity Famework

Steps to run

**Client**:
---
This project was generated with Angular CLI version 9.0.1. You can cd into client folder and 
use command `npm i` to install the required packages.
Use ng serve to start the front-end application.

**Backend**:
---
* In the root folder use the command
* dotnet restore
* docker compose up -d
* cd API
* dotnet run
* This will start the backend server

**Backend Architecture**
---
We have have Repository and Unit of Work Pattern along with Singleton and Dependency Injection to ensure separation of concerns and scalability and reusability of the code.

**Database Architecture**
---
We are using SQLite as the database. We are using code first approach to create the database where we will write the code for the tables and our database and later 
construct the database using migrations provided by Entity Framework.
In an e-commerce application built with .NET Core and Angular, the architecture typically consists of three primary layers: API, Infrastructure, and Core.

API Layer: This layer is responsible for handling HTTP requests and responses. It acts as the communication interface between the client and the back-end services.

Infrastructure Layer: This layer manages interactions with external systems. It communicates with the database to perform CRUD operations and handles any data access logic. It contains repositories, which help in decoupling the data access logic from the business logic.

Core Layer: The core layer houses the business entities and contains all the business logic. It is independent of external dependencies, making it easier to test and maintain. The classes in this layer define the properties of the business objects, such as products for an e-commerce site.

**Different Data Types**
---
![image](https://github.com/user-attachments/assets/c5062649-d202-49b1-84e5-ae6d521d4c66)
![image](https://github.com/user-attachments/assets/9f93ea98-6023-40fd-b691-29cbba6894dd)
![image](https://github.com/user-attachments/assets/6993e6df-e8d0-4d30-83e4-136d0bff5a3b)

**Different Interfaces used for Dependency Injection**
---
![image](https://github.com/user-attachments/assets/8320c152-2191-4dee-acba-98bd3aa6185d)

**Different API Endpoints**
---
![image](https://github.com/user-attachments/assets/fcaaaf31-a420-4901-8a2d-7ec6cd616b5c)


**To serve the application**: 
---
Use command   `ng serve`

**Development server**:
---
This project is built using asp.net core 3.1. you can cd into API directory and say dotnet restore and then dotnet watch run.


**Some snapshots of the project**:
---


![shop-page](https://user-images.githubusercontent.com/49496878/137600664-4233056f-94bd-4415-8e7f-3af0dd914ebb.png)
![product-description](https://user-images.githubusercontent.com/49496878/137600676-926b9116-6c95-4bd7-986b-f69c353588ac.png)
![basket](https://user-images.githubusercontent.com/49496878/137600680-7934ec04-b721-4b1a-8878-945fd6c82637.png)
![address](https://user-images.githubusercontent.com/49496878/137600686-bbf40cc9-5fd9-424d-8289-ef4d2a5ffe90.png)
![delivery](http![payment](https://user-images.githubusercontent.com/49496878/137600694-4881cb67-1810-41b4-be16-26ec4c497284.png)
s://user-images.gi![confirm](https://user-images.githubusercontent.com/49496878/137600696-a5448ec1-3d66-4e53-a2be-7d31c07229f8.png)


