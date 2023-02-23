# E-Commerce-Back-End

## Description

This project is a back end for an e-commerce site built using Express.js and Sequelize. It provides API routes for managing categories, products, and tags.

## Technologies Used

This project uses the following technologies:

- Node.js
- Express.js
- Sequelize
- MySQL

## Getting STarted

To get started with this project, follow the steps below:

1. Clone the project repository using the command git clone teh repository.
2. Navigate to the project directory using the command

```
cd e-commerce-back-end
```

3. Install the necessary dependencies using the command

```
npm install
```

4. Create a .env file and add your database name, MySQL username, and MySQL password.
5. Run the schema and seed commands to create the development database and seed it with test data using the command

```
npm run seed
```

6. Start the application using the command

```
npm start
```

## API Routes

This project provides the following API routes:

- /api/categories - provides a list of all categories
- /api/categories/:id - provides details for a specific category
- /api/products - provides a list of all products with their associated category and tag data
- /api/products/:id - provides details for a specific product with its associated category and tag data
- /api/tags - provides a list of all tags
- /api/tags/:id - provides details for a specific tag

## Contribution Guidelines

If you want to contribute to this project, please follow the guidelines below:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make changes and commit them
4. Push your changes to your forked repository
5. Submit a pull request with a detailed description of your changes

## Walkthrough Video

Please follow to watch the [walkthrough video](https://drive.google.com/file/d/1Di5wQEn6US3yL5yX2PLaB37_ns3sE5Kt/view) that demonstrates the functionality of the application.
