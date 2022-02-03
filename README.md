# ORM E-commerce Backend

## Contents

- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Questions](#Questions)

## Description

For this project, created an ORM e-commerce backend by creating an Express API that uses Sequelize to interact with a MySQL database.

This app will allow you to view, create, update and delete your products, categories and tags in an API client like Insomnia.

You can see a full walk through of this app here - https://watch.screencastify.com/v/uWXCGbfXX4UPYlJb1ElC

## Installation

To install this project, simple clone the repository, then run the below command to install all dependencies.

```
npm i
```

## Usage

Firstly, to use this app, make sure you have both node.js and MySQL installed. Once installed, follow the below steps:

- You need to create a .env file that holds the DB_NAME and your MySQL user name and password (DB_USER & DB_PW)

- Next, navigate into the db folder in the terminal and then log into the mysql CLI and run the below command to create the database.

```
source schema.sql
```

- Once this has been done, exit the mysql CLI back to your normal terminal shell and navigate back to the root folder and run the below command if you want to seed the database.

```
npm run seed
```

- When this is done, you have created the database and seeded it with some data. You can now start the application with the below command.

```
node server.js
```

- Now the server has started, you can navigate to insomnia and get cracking with viewing, creating, updating and deleting data as you please.

## Questions

If you have any questions, you can contact me via GitHub or email me at mattwilliamsdev@gmail.com
