# E Commerce Back End [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## License 
ISC License (ISC) [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Table of Contents
* [Acceptance Criteria](#acceptance-criteria)
* [Installation Instructions](#installation-instructions)
* [Links](#links)

## Acceptance Criteria
```md
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
## Installation Instructions
This application requires Node.js, Express.js, and Sequilize. In order to connect to the database, the user must run `mysql -u root -p` then enter their password from the '.env' file. 
Once the user has entered their MySQL username and password, the user must source the 'schema.sql' file. Once the 'schema.sql' file has been sourced, to seed this file, run `npm run seed`.
Lastly, to connect to the server, the user must run `npm start`.

## Links 
[URL to Demo](https://drive.google.com/file/d/1wGubRAVFypEkvjz25rqam52l4XmUpdwD/view)
