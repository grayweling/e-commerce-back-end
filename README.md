# E-commerce Back End
  
  ![language](https://img.shields.io/badge/language-dotenv-red)
  ![language](https://img.shields.io/badge/language-Express.js-yellow)
  ![language](https://img.shields.io/badge/language-MySQL-Blue)
  ![inquirer](https://img.shields.io/badge/language-Sequelize-blue)


  ## Description

  ----------------------

  This project uses Express.js, MySQL and Sequelize in order to set up a server that allows for persistent storage. We are utilizing dotenv in order to protect sensitive environment data. A user will be able to create, view, update, and delete various products, tags, and categories using a RESTful api.

  
 ## Installation

 To install the E-commerce Back End or view the code, open `terminal` or `gitbash` and navigate to desktop.

    cd desktop


Clone this repo

     git clone https://github.com/lrodenyoder/e-commerce-back-end
  
Open folder in Visual Studio Code

Before the generator can be used, a `.env` file must be created in the root directory of the project and populated with the information needed to log into MySQL

    cd e-commerce-back-end
    touch .env

Install npm modules for the project

    npm install

To initialize the server, run the following commands

    mysql -u <username> -p

Enter password when prompted
    
    source db/schema.sql
    quit
    npm run seed
    npm start

   
 ## License

  -----------------------

  MIT License 

  Copyright (c) [2022] by [John Yoder]

  [Click Here](https://choosealicense.com/licenses/mit/) to go to license details