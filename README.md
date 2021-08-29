# E-commerce Backend
![license](https://img.shields.io/github/license/rpgarde/ecommerce-backend)

## Description
This is an e-commerce backend built using Node.JS, Express, Sequelize, and MySQL. See video demos [Part 1](https://drive.google.com/file/d/1ajSgI8dSkMNp08XDrcCPdwZ-D5acjBvl/view) and [Part 2](https://drive.google.com/file/d/1IEMlkfmRPaQir67V2wuAtZAojPsCMwmT/view) demonstrating its functionality.
![Screenshot](./assets/\screenshot.png)

## Table of Contents 
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Questions](#questions)

## Installation
* Start by creating the databases by running SOURCE schema.sql;
* Change the .env.example to a .env file with your MySQL credentials
* Type npm i on your terminal to install all dependencies
* Type npm run seed to seed the database
* Type npm start to run the application

## Usage
See video walkthrough [Part 1](https://drive.google.com/file/d/1ajSgI8dSkMNp08XDrcCPdwZ-D5acjBvl/view) and [Part 2](https://drive.google.com/file/d/1IEMlkfmRPaQir67V2wuAtZAojPsCMwmT/view).
1. npm start to get started
2. Go to insomnia and set the necessary routes

This has the following routes setup under http://localhost:3001/api
* /categories
    * GET all categories
    * GET categories by ID (use /categories/:id)
    * POST a new category
    * DELETE a category by ID (use /categories/:id)
    * UPDATE a category by ID (use /categories/:id)
* /products
    * GET all products
    * GET products by ID (use /products/:id)
    * POST a new category
    * DELETE a product by ID (use /products/:id)
    * UPDATE a product by ID (use /products/:id)
* /tags
    * GET all tags
    * GET tags by ID (use /tags/:id)
    * POST a new category
    * DELETE a tag by ID (use /tags/:id)
    * UPDATE a tag by ID (use /tags/:id)

## License
This project uses MIT license.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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

## Tests
No tests installed on this repo. 

## Questions
For any further questions, reach out to rpgarde@gmail.com or visit my [Github profile](https://github.com/rpgarde).