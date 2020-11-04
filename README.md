# Eat-Da-Burger-:hamburger:

It is a restaurant app that lets users input the names of burgers they'd like to eat.

## Installation
1. Add a package.json file by running `npm init` from the command line.
2. Install the Express npm package: `npm install express`.
3. Install the Handlebars npm package: `npm install express-handlebars`.
4. Install MySQL npm package: `npm install mysql`.
5. Inside your `burger` directory, create a folder named `db`.
6. Run the `schema.sql` and `seeds.sql` files into the mysql workbench
7. Inside config folder update connection.js file with your password

## Usage 
* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.
* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.
* Your app will store every burger in a database, whether devoured or not.


