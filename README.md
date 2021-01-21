# E-Commerce

## Description
This application builds the backend for an e-commerce site using express.js, mysql2 and sequelize.

- Link: [See the GitHub Repository for this application here](https://github.com/kohringsw/e-commerce.git)

## Table of Contents
- [Description](#description)
- [Installation Instructions](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)

## Installation Instructions
Required Installation
- npm install
- npm install express
- npm install sequelize
- npm install mysql2
- npm install dotenv

## Usage
1. npm install dotenv 
2. Create a .env file 
3. Update .env file with the database name, your username and password 
- [See video tutorial on how to set up your .env file](https://drive.google.com/file/d/1SsJAjsy3_P6HX21FEqigwJHJL1pMv29k/view)

4. mysql -u root -p (enter password)
5. source db/schema.sql ("show databases;" see that it was created then quit mysql)
6. npm run seed to seed data to your database so that you can test your routes
7. npm start to open the server
8. Test your routes in Insomnia Core
- [See full video walk through of the E-Commerce application](https://drive.google.com/file/d/1TJJ8XPeHksgAOmIK4R7D5_xCovCt1r3q/view)

## Contributors
Shelby Kohring

## Tests
Testing provided using Insomnia Core

## License 
None

## Questions
If you have questions about this application: 
- Find me on [GitHub: kohringsw](https://github.com/kohringsw) or 
- Email me at [kohringsw@gmail.com](mailto:kohringsw@gmail.com)