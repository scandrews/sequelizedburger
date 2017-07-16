# Sequelized Burger Application
Home Work 15, The burger app, using Sequelize for data base access, node and handlebars
Steven Andrews

## Overview

This application will list the burgers in an SQL database, allowing the user to create new burgers and to "eat" the burgers.

## Deployment

This applicatin is deployed on Heroku at:
https://git.heroku.com/scandrewsburger.git

## Homepage



## Functionality

This application will list the burgers in the database, displaying a left column of the burgers that can be eaten with a "devour" button.  The right column displays the burgers that have been eaten.  Under the list is a text box with a submit button allowing the user to create a new burger.  Once a new burger is created it will be put on the list.  If the "devour" button is clicked, the burger is moved to the right column.

## Technologies

The sever is a node application written in JavaScript
The display is through handlebars
The database is mySQL running localy
Node packages used:
	body-parser
	path
	method-override
	express
	express-handlebars

