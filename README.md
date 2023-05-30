# Object-Relational Mapping (ORM): E-Commerce Back End

## Description
My task for this assignment was to build the back end for this e-commerce application with the help of starter code given to me. You are able to connect to the database using Sequelize, and the User will be able to create, update, and delete data from their database.

## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Walkthrough](#walkthrough)
* [Installation](#installation)
* [Technologies](#technologies)
* [Notes](#Notes)
* [Questions](#questions)

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Walkthrough 

## Installation
- Run `npm i` to install all dependencies 
- Log in mysql and `source db/schema.sql`
- Next `use ecommerce_db`
- 'quit' mysql then run `npm run seed`
- Finally run the application by entering `node server.js`

## Technologies
- Dontenv
- SQL
- Express
- Node
- JavaScript

## Notes
Troubles that I ran into mainly had to do with my seed files, however once I was able to sort out that issue everything worked perfectly.

## Questions
[TianPnce](https://github.com/TianPnce)

