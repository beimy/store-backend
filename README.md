# Store-Backend
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Table of Contents
  [Description](#Description)

  [Installation Instructions](#Installation-Instructions)

  [Usage Rights](#Usage-Rights)

  [Contribution Guidelines](#Contribution-Guidelines)

  [Testing Instructions](#Testing-Instructions)

  [License Info](#License)

  
  


  ## Description
  
  This application sets up a backend meant for an online storefront. Users can use the api endpoints to read, write, update, andelete data from a MySQL database, via an express server making use of the sequelize package.

  ## Installation Instructions
  
  1. Install MySQL, and node.js.

  2. Download the project files here with the green code button at the top of the github page

  3. Open the terminal and navigate to the folder you saved the project files at. Navigate into the Develop folder.

  4. Inside the Develop folder run the command [mysql -u root -p], this will log you into the MySQL shell. If you set up a password enter it after running this command.

  5. With the MySQL shell open run the command [SOURCE db/schema.sql], this will create a new database for you. You can now close out of the MySQL shell with the command exit.

  6. Again in your terminal navigate to the programs file location, then navigate deeper into the Develop folder.

  7. Inside the Develop folder in the terminal run the command [npm i], this will install all of the dependency libraries for the application (express, sequelize, mysql2, dotenv).

  8. Create a new file called [.env] in the Develop folder, and open it in your editor of choice. You need to add your database name, username, and password data in this file. The following is an example DB_NAME = ecommerce_db DB_USE = YOUR_USERNAME DB_PW = YOUR_PASSWORD.

  9. Now we can seed the database with the included seed data with the command [npm run seed].

  10. With the database seeded you can start the server with the command [npm start] you can now read, write, update, and delete data from your database with the included api endpoints.

  ## Usage Rights
  
  Anyone may use this project

  ## Contribution Guidelines
  
  Feel free to fork and add to this repo

  ## Testing Instructions
  
  Currently no testing commands exist

  

  ## License
    
  Copyright <YEAR> <COPYRIGHT HOLDER>

  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files
  (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge,
  publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
  subject to the following conditions:

  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO
  THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
  CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
  DEALINGS IN THE SOFTWARE.
    
  Click [here](https://www.mit.edu/~amini/LICENSE.md) for more info
  