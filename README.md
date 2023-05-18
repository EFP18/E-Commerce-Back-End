# Object-Relational Mapping (ORM): E-Commerce Back End

  ![License](https://img.shields.io/badge/License-MIT.svg)

  https://opensource.org/licenses/MIT

  GitHub: https://github.com/EFP18/E-Commerce-Back-End
  ![Video Walk-Through](https://drive.google.com/file/d/1iYCDobA7heymm4wU5gyKGA_F2mMqOaXl/view)

  ## Table of Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Questions](#questions)


  ### Description
  This project shows the backend of an e-commerce platform. It uses the Express JS API, [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages, as well as the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data. 

  ### Installation
  The file package.json contains all the necessary dependencies for the repository to work. The user needs to simply right click on the repository folder in `VS Code`, click on `Open in Integrated Terminal`, and then down in the terminal follow the steps below: 
  * Type `npm i` to install all the dependencies. 
  * Next, they will need to create the database by accessing MySQL, by typing `mysql -u root -p`, inserting their credentials, and then typing `SOURCE schema.sql` (making sure that they are in the right folder (DB)). 
  * After that, they can exit SQL by typing exit, and type `npm run seed` to populate the database. 
  * Lastly, the user will need to type `npm start` to activate the port and access the database through `Insomnia`, by using the different routes created. They will have the ability to see all the data, see a specific one by its id, create, update and delete data. 

  ### Usage
  To view and edit a database in the backend. 

  ### License
  MIT

  ### Questions
  * GitHub: http://github.com/https://github.com/EFP18
  * Email: ester.p18@hotmail.com
  
