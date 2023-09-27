


# BACK-END Project with Server-Side API

This is a simple node js app project that utilizes a server-side API. The project includes a server.js file that serves as the backend for the application.

## Technologies Used

- Node.js with Express.js
- MongoDB for database
- Express
- connect-history-api-fallback for handling client-side routing

## Getting Started

1. Clone the repository to your local machine:

```bash
git clone <repository-url>
cd <repository-folder>
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the project root directory and set the following environment variables:

```
MONGO_PASS=<your-mongodb-password>
DATABASE=<your-mongodb-database-name>
```

4. Start the server:

```bash
npm start
```

The server will run on port 8000 by default. You can change the port in the `app.listen()` function in `server.js`.

## API Endpoints

- **GET /api/products**: Retrieve a list of products from the database.

- **GET /api/users/:userId/cart**: Retrieve the user's cart items based on their user ID.

- **GET /api/products/:productId**: Retrieve a specific product by its ID.

- **POST /api/users/:userId/cart**: Add a product to the user's cart.

- **DELETE /api/users/:userId/cart/:productId**: Remove a product from the user's cart.

## Frontend

The frontend buid of this application is expected to be located in the `dist` folder. 
See the full FrontEnd Project with code source here [FullStack Ecommerce App](#)

## Contributing

Feel free to contribute to this project by creating issues or pull requests. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the [MIT](LICENSE) file for details.
```

Make sure to replace `<repository-url>` and `<repository-folder>` with your actual repository URL and folder name. Additionally, update the MongoDB connection variables in the `.env` section as needed.
