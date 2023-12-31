# E-Commerce-Website
  ![MIT license](https://img.shields.io/badge/license-MIT-blue)
  ## Description 
    
   Back end for an e-commerce site taking a working Express.js API and configured it to use Sequelize to interact with a MySQL database.

  ## Table of Contents
  * [installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Screenshots](#screenshots)
  * [URL](#url)
  * [Questions](#questions)
  
  ## Installation
  
    1. Install NODE.js to run this application
    2. Create a .gitignore file and include node_modules/ and .DS_Store/ so that your node_modules directory isn't tracked or uploaded to GitHub. Be sure to create your .gitignore file before installing any npm dependencies.
    3. Make sure that your repo includes a package.json with the required dependencies. You can create one by running npm init when you first set up the project, before installing any dependencies.
    4. Run command npm install Express from the integrated terminal to install server.js package dependency.
    5. Run command npm install mysql2 from the integrated terminal to install mysql package to connect with database and perfrom queries.
    6. Run command npm install sequelize from the integrated terminal install sequelize package to connect Express.js API to a MYSQL database.
    7. Run command npm install dotenv from integrated terminal to install dotenv package to use environment variables to store sensitive data like your MySQL username, password, and database name.
    8. Use the schema.sql file in the db folder to create database with MySQL shell commands - mysql -u root..
    9. Run command npm run seed from integrated terminal to seed tables with data. .
    10. Application is invoked by using following command: node server.js from integrated terminal.
    11. This will start localhost server on PORT 3001.
    12. For testing Open insomnia and type http://localhost:3001/ with necessary API routes.

  ## Usage
        * GIVEN a functional Express.js API
    1. WHEN I add my database name, MySQL username, and MySQL password to an environment variable file, THEN I am able to connect to a database using Sequelize
    2. WHEN I enter schema and seed commands, THEN a development database is created and is seeded with test data
    3. WHEN I enter the command to invoke the application THEN my server is started and the Sequelize models are synced to the MySQL database
    4. WHEN I open API GET routes in Insomnia for categories, products, or tags THEN the data for each of these routes is displayed in a formatted JSON
    5. WHEN I test API POST, PUT, and DELETE routes in Insomnia THEN I am able to successfully create, update, and delete data in my database

  ## License
  
This project is licensed under the MIT

  ## Contributing
  
Email me if you wish to contribute

  ## Tests
  
 To run test, run the following command:

  ```
  npm test
  ```
  ## Screenshots

![Alt text](<Screenshot 2023-06-22 204946.png>)

  ## URL

Walkthrough video of E-commerce Back End : 
The walkthrough video demonstrating GET,POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia Core.
https://drive.google.com/file/d/1J1ZfAguhftGK_aLUnl2J2_pAQi3nxWTr/view

The walkthrough video demonstrating how to seed the database from the command line and to to start the application’s server..
https://drive.google.com/file/d/155-61Son0zLzpmq2qsWQHg5FGJhhNT3v/view

The URL of the GitHub repository : https://github.com/Meera-Mohanan/E-Commerce-Website

  ## Questions
 
 If you have any questions about the repo, open an issue or contact me directly at meera.mohanan@gmail.com. you can find more of my work at [Meera-Mohanan](https://github.com/Meera-Mohanan)

