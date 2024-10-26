# Cliq-App

Cliq-App is a versatile, feature-rich web application designed for seamless communication and collaboration. With real-time messaging, group chats, and a user-friendly interface, Cliq-App makes it easy to connect with friends, family, and colleagues.

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the App](#running-the-app)

---

## Features

- Real-time messaging
- Group and direct chats
- User authentication and profiles
- Responsive and intuitive interface

## Prerequisites

To run the Cliq-App locally, ensure you have the following installed:

- **Node.js** (v14.x or higher)
- **npm** (Node package manager, typically installed with Node.js)
- **MongoDB** (for database)

## Installation

Follow these steps to install Cliq-App:

### Clone the Repository
   ```bash
   git clone https://github.com/SubashSK777/Cliq-App.git
   cd Cliq-App
```
### Installation

### Install Backend Dependencies
Navigate to the server directory and install the dependencies:

```bash
cd server
npm install
```

### Install Frontend Dependencies
Next, navigate to the client directory and install the dependencies:

```bash
cd ../client
npm install
```
### Configuration
Environment Variables
Backend Configuration
In the server directory, create a .env file with the following variables:

```plaintext
MONGO_URI=<your_mongo_db_connection_string>
PORT=5000
JWT_SECRET=<your_jwt_secret>
```
MONGO_URI: MongoDB connection string.
PORT: Port for the server (default is 5000).
JWT_SECRET: Secret key for JWT authentication.

Frontend Configuration
In the client directory, create a .env file (if needed) for any API endpoints or configurations.

### Running the App
Start the Backend Server
In the server directory, start the backend server:

```bash
npm start
```

### Start the Frontend Server
In the client directory, start the frontend development server:

```bash
npm start
```

### Access the Application
Open your browser and go to:

```bash
http://localhost:3000
```

<br/>
<br/>
<table>
  <tr>
    <td>
      <img src="/images/1.jpg" width=300>
    </td>
    <td>
      <img src="/images/4.jpg" width=300>
    </td>
    <td>
      <img src="/images/3.jpg" width=300>
    </td>
  </tr>
  <tr>
    <td>
      <img src="/images/6.jpg" width=300>
    </td>
    <td>
      <img src="/images/5.jpg" width=300>
    </td>
    <td>
      <img src="/images/9.png" width=300>
    </td>
    </tr>
    <tr>
    <td>
      <img src="/images/2.jpg" width=300>
    </td>
      <td>
      <img src="/images/7.jpg" width=300>
    </td>
    <td>
      <img src="/images/8.jpg" width=300>
    </td>
  </tr>
</table>

