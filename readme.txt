This rolodex application uses a server side API to access and modify a mongo database. It is built with Angular/Mongo/Express/Node.js.

To set up the application the user will either need access my mongo 
Database or create a database with an identical schema. The schema for 
my database is in a file called 'contacts' and can be found in the models 
folder within the client folder. Alternatively, email me for the login credentials. 


To set up this application:
	1) Clone the repository to your machine
	2) Use NPM to install all of the dependencies for both the 
	client and the server folders
	3) Create a .env file with either: the username and password to my 
	database, or the username and password to your database with an 
	identical schema
	4) Load the client with the cmd 'npm run start-dev'
	5) Navigate to localhost:2000

This github repository includes my Angular build in the dist folder. 
As a result, if any changes are made to the client side, the contents of the
dist folder will need to be deleted, and the updated app will need to be 
recompiled with the Angular CLI (using ng build).

A link to a working iteration of the application can be found at my 
personal site www.alex-g-portfolio.me
