# Object-Relational Mapping (ORM): E-Commerce Back End

  ![License](https://img.shields.io/badge/License-MIT.svg)

  https://opensource.org/licenses/MIT


  ## Table of Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Questions](#questions)


  ### Description
  This project shows the backend of an e-commerce platform. It uses the Express JS library and Sequelize, to interact with the MySQL ddatabase. 

  ### Installation
  The file package.json contains all the necessary dependencies for the repository to work. The user needs to simply right click on the repository folder in VS Code, click on Open in Integrated Terminal, and then down in the terminal type npm i to install all the dependencies. Next, type npm run seed to populate the database. Lastly, the user will need to type npm start to activate the port and access the database through Insomnia, by using the different routes created. They will have the ability to see all the data, see a specific one by the id, create, update and delete data. 

  ### Usage
  To view and edit a database in the backend. 

  ### License
  MIT

  ### Questions
  * GitHub: http://github.com/https://github.com/EFP18
  * Email: ester.p18@hotmail.com
  


You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

## Getting Started

This Challenge will require a video submission. Refer to the [Fullstack Blog Video Submission Guide](https://coding-boot-camp.github.io/full-stack/computer-literacy/video-submission-guide) for additional guidance on creating a video.





### Seed the Database

After creating the models and routes, run `npm run seed` to seed data to your database so that you can test your routes.

### Sync Sequelize to the Database on Server Start

Create the code needed in `server.js` to sync the Sequelize models to the MySQL database on server start.

## Grading Requirements




* The walkthrough video must demonstrate how to create the schema from the MySQL shell.

* The walkthrough video must demonstrate how to seed the database from the command line.

* The walkthrough video must demonstrate how to start the application’s server.




