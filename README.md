# MERN Stack Bookstore Project

This is a full-stack bookstore application built with the MERN (MongoDB, Express, React, Node.js) stack. The project consists of two main folders:
- `frontend`: Handles the user interface using **React** and **Tailwind CSS**.
- `backend`: Manages the server and API routes with **Node.js** and **MongoDB** Cloud.

Users can browse free books without an account, but premium books require account registration and login to access. Axios is used to facilitate communication between the frontend and backend.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- **User Authentication**: 
  - Sign up and login for users to access premium books.
  - Protected routes ensure that only logged-in users can view or purchase premium content.
  
- **Book Management**:
  - Browse free books without needing an account.
  - Access premium books by creating an account and logging in.

## Technologies Used

- **Frontend**:
  - [React](https://reactjs.org/): JavaScript library for building user interfaces.
  - [Tailwind CSS](https://tailwindcss.com/): Utility-first CSS framework for styling.
  - [Axios](https://axios-http.com/): HTTP client for making API requests from the frontend to the backend.

- **Backend**:
  - [Node.js](https://nodejs.org/): JavaScript runtime for server-side code.
  - [Express](https://expressjs.com/): Web framework for Node.js.
  - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): Cloud database for data storage.
  - **JSON Web Token (JWT)**: For securing protected routes.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sheikh-bilal/bookstore.git
   cd bookstore
