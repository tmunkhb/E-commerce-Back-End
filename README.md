# E-commerce-Back-End
## Description 
This application was created as back-end for e-commerce site using Express.js API configued to use Sequelize for MySQL database.

## Installation
- Clone the repo
- npm init
- npm install (to install all dependencies such as mysql2, sequelize, dotenv)
- create .env file in root of directory and write the following code with personal mysql username and password:
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'

## Video Demonstration
https://www.youtube.com/watch?v=-q21FmoKPwk

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
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


