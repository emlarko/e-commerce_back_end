# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

The aim of this project was to build the back-end for an e-commerce site from starter code, using Express.js, Sequelize and MySQL.

## Installation

Clone the project onto your machine, then run the following commands to create the schema from the MySQL shell.

```
mysql -u root -p
<enter your MySql password>

source db/schema.sql

exit
```

Run the following line of code in your terminal to install the needed packages:

```
npm i
```

Enter your details into a .env file:

```
DB_NAME='ecommerce_db'
DB_USER='<your MySql username'
DB_PASSWORD='<your MySql password>'
```

Seed the database by running the following command:

```
node seeds/index.js
```

## Usage 

Once the above instructions have been followed, run the following line of code in your terminal:

```
npm start
```

After starting the applications server, the user will be able to test the API routes in Insomnia.

When opening the API GET routes in Insomnia, the user will be able to view all the data for categories, products, or tags in formatted JSON.

They will also be able to view individual items by providing the ID in the GET request.

When using the API POST, PUT, and DELETE routes in Insomnia, the user is able to successfully create, update, and delete data in the database.

[Object-Relational Mapping (ORM)_ E-Commerce Back End.webm](https://user-images.githubusercontent.com/101362057/227213792-0a6f9616-bfc1-4352-a241-0a20136df694.webm)
