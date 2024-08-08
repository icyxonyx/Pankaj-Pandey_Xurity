# Pankaj-Pandey_Xurity

## Description
A generic implementation of CRUD operations featuring a login page, a registration page, a list of users accessible only by admin, and an option to change personal details.

## Features
- Login page
- Register page
- List of users (admin access only)
- Option to change personal details

## Technologies Used
- **MongoDB**
- **Express**
- **React**
- **Node.js**

## Installation Instructions

1. Navigate to the `client` folder:
    ```bash
    cd client
    ```

2. Install client dependencies:
    ```bash
    npm install
    ```

3. Navigate back to the main project folder:
    ```bash
    cd ../server
    ```

4. Install server dependencies:
    ```bash
    npm install
    ```

5. Create a `.env` file in the `test` folder with the following variables:
    - `MONGO_URL`: Your MongoDB connection string.
    - `JWT_SECRET`: A secret key for JSON Web Tokens.

6. Open two separate terminals:
    - In the first terminal, navigate to the `client` folder and run:
      ```bash
      npm start
      ```
    - In the second terminal, stay in the main folder and run:
      ```bash
      npm start
      ```

## Usage
After setting up the environment and running the application, you can access the following features:
- Login to the application
- Register a new account
- View the list of users (admin access required)
- Change personal details
