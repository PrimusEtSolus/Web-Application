# Web-Application
Web Application CIT14 | CITCS 2J GROUP B
Objective:

For our final lab activity, you will be creating a web application using Node.js, Express and SQLite3 that allows you to interact with a database. The goal is to implement basic CRUD operations (Create, Read, Update, Delete) and display the data in a user-friendly web interface. You will also deploy the application to the web using Render, making it accessible to to others.

For this activity you will

learn how to set upo a basic Node.js application with Express
learn how to use SQLite as a database to store and manage data
implement HTTP methods for CRUD operations: GET, POST, PUT, PATCH and DELETE
organize your application with routes, controllers, and models to follow good coding practices
deploy your application to a cloud platform, Render
 

Instructions:

Create a Node.js application using Express and SQLite3
create a .gitignore file, and ignore: your database and the content of your node_modules folder. You may ignore other files
For your database, it must have a minimum of 1 table called 'items' with the following columns:
id: a unique identifier (primary key, auto-increment)
name: the name of the item (required field, VARCHAR 255)
description: optional
date_created: timestamp for when the item was created
Implement CRUD operations for the items table
GET: must return a list of items from the database
POST: add a new item to the database
PUT: update an existing item based on its ID
PATCH: partially update an existing item
DELETE: delete an item from the database
Web Interface:
there must be a web page to display the fetched items
there must be a pop-up, modal or separate page to Add, Edit and Delete the items
Use good coding practices such as organizing your code into separate files for:
routes
controllers
models
Put your code into your github, but this time, you will be deploying your web app using Render (pointed at your web application)
your repository must be named: web-app
you must submit 2 links: your github repository and your render link
your repository has to have a README.md file that includes:
a short description of your web application
how to make it run locally if other people clone it
 

BONUS:

add the ability to search or filter items by name or filter by date/date range
you may use tailwind css
add the ability to handle fetching thousands of records
