# Note-Taker

![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

This application is a back end to an e-commerce website. The application uses an express server and Sequelize that interacts a mySQL database. Users will use Insomnia Core to Get, Post, Update, and Delete categories, products, and tags to and from the mySQL database.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)
- [Links](#links)

## Installation

1. Clone E-commerce Back End repo from GitHub.
2. Access repo using the command line.
3. In the terminal run `npm i`

## Usage

1. Access E-commerce Back End through the command line on your local machine.
2. Copy schema.sql from db and paste into new tab on mySQL. Run the schema.
3. In the command line run `node seeds/` to seed the database
4. In the command line run `npm start` to start the server
5. Open Insomnia Core and run GET, POST, PUT, and DELETE routes in http://localhost:3001/api + the route you would like to change.

Demo

Seed database and start server
https://drive.google.com/file/d/1jmiz_kEWFbpy6L1fCxr-edwVv6tmV340/view
![Seed database and start server](./public/images/seed_serverStart.gif)

Get all categories, products, and tags and get by ID
https://drive.google.com/file/d/1e2PDP6aun3UI7Y_o13dHfrSJLdVq6phv/view
![Get all categories, products, and tags or get by ID](./public/images/GETall_GETbyID.gif)

Post a category, product, or tag
https://drive.google.com/file/d/1e2PDP6aun3UI7Y_o13dHfrSJLdVq6phv/view
![Post a category, product, or tag](./public/images/POSTall.gif)

Update a category, category or tag by ID
https://drive.google.com/file/d/1AlP1nJSO-7R6a3pQ5FQilyGSZuc3-eyW/view
![Update a category, product, or tag](./public/images/PUTbyID.gif)

Delete a category, product, or tag by ID
https://drive.google.com/file/d/1oh9EtVZcErzDOw1oWs8pjJzyPmniHVxI/view
![Delete a category, product, or tag by ID](./public/images/DeletebyID.gif)

## License

This application is covered by MIT License. For more information please refer to https://choosealicense.com/licenses/mit/

## Questions

- GitHub: [jkcanoy](https://github.com/jkcanoy).

- For more information please contact kylecanoy96@gma
