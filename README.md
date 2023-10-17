# My Bookstore - Backend

Welcome to the backbone of our online bookstore, built using Node.js, Express.js, and MongoDB. Our robust backend provides a foundation for users to seamlessly explore, search for, and purchase their favorite books.

## Key Features

Our backend empowers you with essential features for a smooth user experience:

- **User Management:** Easily manage user accounts with registration, login, and logout functionality.
- **Book Catalog:** Access an extensive collection of books with efficient browsing and search capabilities.
- **Order Processing:** Streamlined order creation ensures a hassle-free shopping experience.

## Technologies at Work

We've harnessed the power of cutting-edge technologies to deliver a robust backend:

- **Node.js:** A high-performance JavaScript runtime built on Chrome's V8 engine, ideal for server-side applications.
- **Express.js:** A fast and flexible Node.js web application framework that ensures a seamless operation.
- **MongoDB:** Our choice for a cross-platform document-oriented database program, offering data flexibility and integrity.
- **Mongoose:** An Object Data Modeling (ODM) library for MongoDB and Node.js, simplifying database operations.
- **JSON Web Token (JWT):** This secure technology plays a pivotal role in representing claims for secure data transfer.

## Project Structure

Let's dive into the core structure of our backend:

- **Routes:** In the `routes` directory, you'll find route handlers responsible for books, users, and orders.
- **Models:** The `models` directory houses Mongoose models, including Book, User, and Order.
- **Middleware:** Inside the `middleware` directory, discover essential middleware functions, such as authentication.
- **Configuration:** The `config` directory contains configuration files, including the setup for connecting to the database.

## Prerequisites

To ensure a seamless experience, please meet the following prerequisites:

- **Node.js and npm:** Make sure you have the latest versions installed to facilitate a smooth setup.
- **Operating System:** Our backend is compatible with Windows, Linux, and macOS, so any of these operating systems will work seamlessly.
- **MongoDB:** You'll need to install MongoDB. If you're new to MongoDB, refer to a setup guide for assistance.

## Installing My Bookstore

To set up your local My Bookstore backend, follow these steps:

1. **Clone the Repository:** Create a local copy of our backend codebase with this command:

    ```bash
    git clone https://github.com/Abhay7apk/Questt_Assignment_Backend_Pt.git
    ```

2. **Navigate to the Project Directory:** Access the project directory using this command:

    ```bash
    cd Questt-backend
    ```

3. **Install Dependencies:** Ensure that all required packages and libraries are readily available by running this command:

    ```bash
    npm install
    ```

## Configuring My Bookstore

To tailor My Bookstore to your requirements, you'll need to configure key environment variables:

1. **Create a `.env` File:** In the root directory of the project, generate a `.env` file to store crucial environment variables.

2. **Add the Following Lines to the `.env` File:**

    ```shell
    PORT="3001"
    MONGODB_URL="mongodb://127.0.0.1:27017/bookstore"
    SECRET_KEY="yourNewSecretKey"
    ```

    - Replace `"mongodb://127.0.0.1:27017/bookstore"` with your unique MongoDB connection string, should it differ.
    - Replace "yourNewSecretKey" with a secure and confidential secret key. After modifying the `.env` file, remember to restart your server for the changes to take effect.

## Running My Bookstore Locally

Explore the capabilities of My Bookstore on your local machine with these straightforward steps:

1. **Start the Development Server:** Initialize the development server by running this command:

    ```bash
    node index.js
    ```

2. **Access the Application:** Open your preferred web browser and head to `http://localhost:3001`. You're now ready to explore My Bookstore's backend.

## Deploying My Bookstore

Should you wish to deploy My Bookstore, consider a cloud platform such as Heroku or AWS. Here are general steps to guide you:

1. **Create a New Application:** On your chosen cloud platform, establish a new application.

2. **Connect to Your Repository:** Link your cloud application to your GitHub repository.

3. **Configure Environment Variables:** Set up environment variables on your cloud platform, similar to the setup in your `.env` file.

4. **Deploy the Application:** Utilize the deployment tools provided by your chosen cloud platform to launch your application.

Please note that the specific steps may vary based on the cloud platform you choose.

## API Endpoints

My Bookstore's backend offers a variety of API endpoints to enhance your experience:

- **Register a New User:** `POST /api/users/register`
- **Login a User:** `POST /api/users/login`
- **Logout a User:** `POST /api/users/logout`
- **Create a New Book:** `POST /api/books`
- **Get All Books:** `GET /api/books`
- **Get a Book by ID:** `GET /api/books/:bookID`
- **Update a Book by ID:** `PUT /api/books/:bookID`
- **Delete a Book by ID**
- **Place an Order:** `POST /api/orders`

Your journey through My Bookstore's backend awaits, with a robust feature set and a wide array of technical prowess!