# MERN Stack Food Delivery Project

## Overview
The **MERN Stack Food Delivery** project is a restaurant food delivery app developed using the **MERN Full Stack**. Users can browse the menu, add food items to their cart, and place orders, while admins can manage the menu by adding new food items.

State management is handled using **Redux Toolkit**, along with other essential npm packages.

## Features
### User Modules:
1. **User Authentication**: Login via Firebase Google Authentication.
2. **Order Management**: Users can order food items.
3. **Cart Functionality**: Users can add and remove food items from the cart.
4. **Search Functionality**: Users can search for food items in the menu.

### Admin Modules:
1. **Admin Authentication**: Login, logout, and change password.
2. **Menu Management**: Admins can add food items to the menu.

## Software Requirements
- Any device capable of running **Node.js** and **MongoDB**.
- Internet connection to connect Firebase and Stripe.

## Hardware Requirements
- No high-end hardware required; a basic working device is sufficient.

## How to Import and Run the Project
1. Extract the project files.
2. Open both **client** and **server** folders in **VS Code**.
3. Open the terminal in both **VS Code** windows.
4. Run the following command in both terminal windows:
   ```sh
   npm i
   ```
5. Create Firebase and Stripe accounts.
6. Retrieve the required credentials and paste them into the `.env` file as per the given instructions.
7. Start the client:
   ```sh
   npm start
   ```
8. Start the server:
   ```sh
   node index
   ```

## How to Import the Database
- The project uses **MongoDB** as the database.
- Import the provided **database file** to store and manage data.


---

**Developed using MERN Stack | Redux Toolkit | Firebase Authentication | Stripe Integration**

