# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Your Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Developer Notes
- To begin, please make sure to run the database schema file by logging into mySql and running 'source schema.sql'
- Seed files were already developed to add test data to the database. Please run the seed files by the following command: "npm run seed"
- To start the server please run the command "npm run start" or "node server.js"
- API routes have been configured with the following endpoints:
    - /categories
    - /tags
    - /products
- User will be able to run GET, PUT, POST and DELETE on these routes. Please view the /routes folder for more details on specific functionality. 


## Future Development Ideas
- Eventually I would like to hook up a front end via React to this server so a user has a nicer interface to view and manage their stock
- Possibly add another model to develop further associations with additional products or assets the owner may wish to incorporate into their ecommerce site.

## Walkthrough Video
- Link to walkthrough video can be found here: 

## Screenshots