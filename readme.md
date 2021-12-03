# NodeJs-Express-MySQL App

Just an app to understand the use of NodeJS and Express. 

The app is client-side based which will make requests to the server side and will be equipped with a REST CRUD API. The function will be to read a list of names in the database, to then be able to add others or modify or delete them. There will also be a search by name. The application has a very basic graphic interface, the main purpose is to be able to understand how it works.

# Built With

  - [NodeJs](https://nodejs.org/it/)
  - [Express](https://expressjs.com/it/)
  - [MySQL](https://www.mysql.com/it/)

# How to use
 
To use the app you need to have

- [Node](https://nodejs.org/it/download/)
- [MySQL](https://dev.mysql.com/downloads/installer/)

1. Clone the repo and cd to its root directory
   ```sh
   git clone https://github.com/francescoparra/react-redux-ts

   cd nodejs-express-mysql
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
   
3. Create a Database (With your DBMS)
   ```sh
   CREATE DATABASE databasename;
   ```
4. Create a table names 
   ```sh
   CREATE TABLE names (
    id int NOT NULL,
    name varchar(255) NOT NULL,
    date_added datetime,
    PRIMARY KEY (id)
    );
    ```