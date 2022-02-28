# commerce-app

## Description

This is an api for a commerce app for products. Products have an associated tag, and category. They can have many tags, and one category. You can create products, tags, and categorys. You can also view, change and delete other products, tags, and categorys.

## Installation

To install this app, you just have to clone the repository, and run npm i. You will also need to create a .env file that has DB_NAME=ecommerce_db, DB_USER=, DB_PW=, to be able to run the program.

## Usage
To use this app, use MySql Shell and run source db/schema.sql. Next open your terminal in the directory, and run node seeds/index.js to seed all the data, and finally run npm start, to start the server. Then just use a program like insomnia to use the routes.

[Walk-through](https://drive.google.com/file/d/1YVWx3HDDTgAL1M52CuMwadx6Jwe_npEN/view)