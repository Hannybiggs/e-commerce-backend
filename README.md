# E-Commerce Backend

[Watch the Functionality Video Here](https://drive.google.com/file/d/1Ci1l8klpcfmL_eoGLcAb-cgzLvd--imo/view)

This application is a simple backend structure for an e-commerce site. It uses a working Express.js API and Sequalize to interact with the MySQL database and assist with altering the data. 

## How to Use:
To start using the backend application, the user takes the following steps in VS Code:
- Connect to MySQL using the "mysql -u root -p" in the command line at the root
- npm run seed
- npm start

Transitioning to Insomnia to visualize the functionality, the user can do the following:
- Get all categories, tags, and products
- Get all categories, tags, and products by ID
- Create new categories, tags, and products
- Update categories, tags, and products
- Delete categories, tags and products 

## What Makes it Work:
- Express.js
- Sequalize
- MySQL
- Insomnia

## Use Notes
It is key to adjust the routes up top to access or adjust the data you are hoping to adjust. For example, when deleting a category, the user must be sure to put the corresponding ID in the route for the category to be properly deleted. If this is not adjusted properly, the change will not take place. In addition, there are several categories that must not be null when creating a new product (such as price). This can naturally all be adjusted on the backend per the users liking.