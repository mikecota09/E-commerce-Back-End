# E-commerce-Back-End
## Description
This project is the back end for an e-commerce site. The application uses Express.js, API, and Sequelize to interact with a MySQL database. Express.js was used for the server and MySQL for the database along with Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used to make requests and updates from the database which are joined through Sequelize queries.

## Criteria Met
- When the user adds their database name, MySQL username, and MySQL password to an environment variable file they are able to connect to the database using Sequelize
- When the user enters schema and seed commands a development database is created and is seeded with test data
- When the user enters the command to invoke the application the server is started and the Sequelize models are synced to the MySQL database
- When the user opens API GET routes in Insomnia for categories, products, or tags the data for each of these routes is displayed in a formatted JSON
- When the user tests API POST, PUT, and DELETE routes in Insomnia they are able to successfully create, update, and delete data in my database

## Languages/Frameworks Used
- JavaScript
- Node.js
- Express
- MySQL2
- Sequelize
- Dotenv

## Installation
1. Clone the GitHub repository
2. Open Git Bash or the Terminal
3. Navigate to the directory where you would like to clone the repository to
4. Type the command `git clone` and paste the link to the repository
5. Open your code editor and open the repository
6. Open the terminal window in your code editor
7. Make sure you are in the correct folder in the terminal window
8. Type the command `npm install` in the terminal and press enter to install the dependency packages that are required

Ensure the following packages were install correctly
* dotenv
* Express
* mysql2
* sequelize

## Application Usage
1. In the terminal window navigate to the root folder
2. Run `mysql -u root -p` to connect to the database
3. Enter the password from .env file
4. Source the schema.sql
5. Run `npm run seed` to seed the file
6. Connect to the server using `npm start`

The application allows users to view, add, edit, and delete categories, products, and tags

## Video Walkthrough
[Link to the MySQL walkthrough video](https://drive.google.com/file/d/1EZjg7v39-ehyVxl63h6Gk8yYCa57V8CJ/view)
[Link to the video walkthrough for API routes]()
[Link to the Insomnia walkthrough video]()
