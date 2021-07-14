# Uot Coding Challenge 13: E-commerce Back End

## Description: 
Back end for an e-commerce site using a working Express.js API configured with Sequelize to interact with a MySQL database.

Done as a challenge for UoT's Coding Bootcamp.
___

## Talbe of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Links](#links)
* [Tools](#tools)
* [Credits](#credits)
* [License](#license)
* [Challenge Guidelines](#challenge-guidelines)
___

## Installation
First clone the repository from GitHub. This app uses Node.js, Express.js, and Sequelize. Once cloned, open your terminal and npm install the dependencies as found in the package.json file (dotenv, express, mysql2, and sequelize). You will need to create a .env file to hide your password.

To connect to the database, run `mysql -u root -p`, then ensure the schema.sql file is sourced by running `source db/schema.sql`. Quit mysql and open the terminal again. Seed the file by running `npm run seed` and to connect to the server run `npm start`. From there you can test routes with Insomnia Core if you'd like.
___

## Usage
This app allows users to get, create, update, and delete categories, tags, and products. 

![screenshotHere](/assets/images/ch13_ss.png)
___

## Links
### Walkthrough of app:
* [MySQL Video Walkthrough](https://drive.google.com/file/d/1FGFB4AX-3sj51Vu0KjhcLpWe5Z7MtrsQ/view)
* [API Routes Video Walkthrough](https://drive.google.com/file/d/1ZcBnB4BCqmGEpZ8K2cIg9oiPARM1Ev9s/view)

___

## Tools
* JavaScript
* node.js
* MySQL
* Express.js
* Sequelize
* dotenv
___

## Credits
* Completed by: [Nell-GitHub](https://github.com/ShannonNell)
___

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License](https://choosealicense.com/licenses/mit/)    
___

## Challenge Guidelines
### User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
### Criteria: 
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```