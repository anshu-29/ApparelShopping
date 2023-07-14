# Apparel Shopping Website

This is a README file for an Apparel Shopping website that utilizes EJS, JavaScript, and CSS. The website runs on localhost port 5000 and is built on a SQL Server database. It features both an admin-side and a user-side dashboard, allowing users to add products to their cart and proceed to checkout.

## Installation

1. Clone the repository or download the source code.
2. Ensure you have Node.js and npm (Node Package Manager) installed on your system.
3. Open a terminal or command prompt and navigate to the project directory.
4. Install the required dependencies by running the following command:
   ```
   npm install
   ```

## Configuration

1. Ensure you have SQL Server installed and running on your system.
2. Create a new database for the application.
3. In the project directory, locate the `config` folder and open the `database.js` file.
4. Update the database configuration values in the `database.js` file with your SQL Server credentials and the name of the database you created.

## Usage

1. Open a terminal or command prompt and navigate to the project directory.
2. Start the server by running the following command:
   ```
   npm start
   ```
   The server will start running on localhost:500.
3. Open a web browser and go to http://localhost:500 to access the website.

## Features

### User-side Dashboard

- Browse and search for apparel products.
- View detailed product information.
- Add products to the shopping cart.
- View and update the shopping cart.
- Proceed to the checkout process.

### Admin-side Dashboard

- Login with admin credentials to access the admin dashboard.
- Add new products to the website.
- Edit or delete existing products.
- Manage product categories.
- View and process user orders.



## Technologies Used

- EJS: Templating engine for rendering dynamic web pages.
- JavaScript: Programming language for client-side and server-side logic.
- CSS: Styling language for web page design.
- Node.js: JavaScript runtime environment.
- Express.js: Web application framework for Node.js.
- SQL Server: Relational database management system.

## Contributors

- Aakansh Arora 

## License

This project is licensed under the [MIT License](LICENSE).
