# Cafeteria-Management# Cafeteria Management System

## Project Overview

The Cafeteria Management System is a MERN stack-based application that allows customers to view the cafeteria menu, select food items, add them to a cart, and proceed to checkout. The application also displays the total calorie count for the selected items. The admin can manage the menu by adding, editing, or deleting items and generating reports of the menu.

This project is divided into two parts:

- **Frontend**: The user interface where customers can interact with the system.
- **Backend**: The server-side application responsible for managing data and business logic.

## Features

### Customer Features:
- View available food items on the menu.
- Select food items and specify quantities.
- Add selected items to the cart.
- View total calorie count of items in the cart.
- Proceed to checkout.

### Admin Features:
- Add new items to the menu.
- Edit or delete existing items.
- Generate reports for the menu, including calorie counts.

## Repositories

The project is split into two separate repositories for easier management:

- **Frontend Repository**: [Cafeteria Management System - Frontend](https://github.com/your-username/frontend-repo)
- **Backend Repository**: [Cafeteria Management System - Backend](https://github.com/your-username/backend-repo)

## Technology Stack

- **Frontend**: React.js, CSS/Bootstrap, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Database**: MongoDB

## Setup Instructions

### Prerequisites
To run both the frontend and backend locally, you need to have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Running the Frontend

1. Clone the frontend repository:
    ```bash
    git clone https://github.com/your-username/frontend-repo.git
    cd frontend-repo
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory with the backend API URL:
    ```bash
    REACT_APP_API_URL=your_backend_api_url
    ```

4. Start the frontend server:
    ```bash
    npm start
    ```

5. Open the app in the browser at `http://localhost:3000`.

### Running the Backend

1. Clone the backend repository:
    ```bash
    git clone https://github.com/your-username/backend-repo.git
    cd backend-repo
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory with the following:
    ```bash
    MONGO_URI=your_mongoDB_connection_string
    PORT=8000
    ```

4. Start the backend server:
    ```bash
    npm start
    ```

5. The backend will be running on `http://localhost:8000`.

## Future Enhancements

- Add customer authentication and profile management.
- Implement advanced analytics and reporting for admin users.
- Improve UI with more interactive features for users.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

