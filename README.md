# E-commerce Back End

## Description
A back-end for an online retail company that manages e-commerce using Express.js and configured using Sequelize to connect with a MySQL database. The user can view, add, update, and delete various products, categories, and tags.

## Built With
* MySQL
* JavaScript
* Node.js
* Express.js
* Sequelize
* Dotenv

## Installation
The user must have MySQL installed along with an account. After downloading the code, the user must install the npm packages by typing in 'npm i' in the terminal and update the '.env' file with their MySQL credentials and the name of the database (ecommerce_db). The user must go into MySQL and source the schema.sql file, if they wish to seed the databases, run 'npm run seed', and then start the server by running 'npm start'.

## Usage
After turning on the server with 'npm start' the console will inform the user that it is listening to a local port 3001. Using Insomnia (or any other similar software), the user can then test the any of the four routes: GET, POST, PUT, and DELETE.

![screenshot of insomnia](./assets/images/insomnia-ss.png?raw=true "Insomnia GET request example")
Screenshot of Insomnia using a GET request.

Video Demo: https://drive.google.com/file/d/1KgPcjkiIOS2LNevApQ64yKG4mdVL0yRa/view?usp=sharing

## Test
There are no tests for this application.

## Credits
Made by Andrew Kim