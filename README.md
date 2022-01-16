# eProductStorage

## Description

The foundation for this project was provided by an online bootcamp for [Full-Stack Development](https://bootcamps.vanderbilt.edu/coding/online/landing/). 

This project focused on creating a generated webpage from user input to display a team's basic information.

The requirements for the project were as follows:
* Use `Express.js`
* Use MySQL
* Use `MySQL2` package
* Use `Sequelize` package
* Use `dotenv` package
* All route skeletons were to be filled out
* Sequelize code was to be introduced into the main `server.js` file to initialize the database.
* All models were to be filled out with columns and properties of those columns

## Installation

1. Make sure you have `node`, `git`, and `MySQL` installed.
2. Clone this repository to a location of your preference.
3. Navigate to this location with a terminal of choice.
4. Run the command `npm install`.
5. Provide the `schema.sql` file to `MySQL` through some means (such as command-line) to create the database.
6. Setup your `.env` file with your `MySQL` credentials.
7. Seed the application with `node run seed` if you want example data, otherwise continue to the next step.
8. Start the application with `node start`.
9. Your application is now running a RESTful API locally, you can connect to it through http://localhost:3001/api/.

## Guide

For a visual guide of the above steps, watch [this video](https://youtu.be/PDllcoRHRZ4).

## What I Did

I started this project by creating all of the models through Sequelize. Once the tables had been completed I setup the relations between them. After this I created the routes required and tested them to verify their validity.