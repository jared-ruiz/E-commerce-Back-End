# Challenge -13
## E-commerce Back End Starter Code

- For the thirteenth challenge of my bootcamp, I am tasked with creating the back end of a fictional e-commerce website utilizing sequelize, insomnia for api functionality, model creation and table relationships.

<br>
<br>

## User Story
---

- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Criteria to be considered complete (Apr. 2022)
---

GIVEN a functional Express.js API
> WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
> WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
> WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
> WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
> WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

<br>
<br>

## Table of Contents
---
- [Installation](#installation)
- [Usage](#usage)
- [License Information](#license-information)
- [Questions](#questions)
- [Working Example of Project](#working-example-of-project)

## Installation
---
- Download repo from github, run "npm i" to install all dependencies, create a ".env" file and then add this code to the created file: 

- DB_NAME='ecommerce_db'
- DB_USER='root'
- DB_PW=''

---
- Replace the "user and pw" fields with your respective username and password.
- run "mysql -u root -p" to access your MySQL shell. run "source db/schema.sql;" to create the ecommerce_db database.
- exit MySQL shell and run "node seeds/index.js" to seed database.
- run "npm start" to start your server and begin testing within insomnia.

## Usage
---

- The current usage of this application is to practice and build a back end database with table relationships and api routes displaying said data. The routes follow CRUD operations and RESTful api standards to the best of my current ability.


## License Information
---
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
<br/>

## Questions
---
- If you have any further questions, contact me here: [GitHub](https://github.com/jared-ruiz)

## Working Example of Project
---
[Demo of Working Example - Google Drive Video](https://drive.google.com/file/d/1XkxXxX3zOzXqgEJACXc_Uhef8LHKcM9m/view?usp=sharing)


## Weekly Reflection
---

- This weeks assignment was not as difficult as I was dreading, but the relationship aspect of the models was definitely the hardest for me to conceptually grasp. I need more practice with sequelize and model syntax but I'm confident at what I can recall right now. Project 2 is coming up very soon and I'm doing my best to catch up and grasp all I can. I'm looking forward to working with my team again and experiecing the team work flow again! Leaning on people who are passionate about coding just as much or even more so than me is a truly unique feeling. Here's to another week! 

-J