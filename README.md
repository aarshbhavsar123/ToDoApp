# Todo App

## Description
This is a ToDo app which can be used to create, read, update and delete a task for a given day.

---

## Prerequisites

Before you start, ensure you have the following installed:

- Node.js (version 14 or higher)
- npm (Node package manager)
- React
- MongoDB as Database
  

---

## Project Setup

Follow these steps to set up the project locally:

### 1. Client Setup

1. Navigate to the `/client` directory:

   ```bash
   cd client
2. Install the necessary dependencies:
   ```bash
   npm install
3. Start the client server:
   ```bash
   npm start
This will start the client application, and it should be accessible at http://localhost:3000 by default.


### 2. Server Setup
1. Navigate to the /server directory:
   ```bash
   cd ../server
2. Install the necessary dependencies:
   ```bash
   npm install
3. Start the server:
   ```bash
   npm start
This will start the backend server, and it should be accessible at http://localhost:5000 by default.

## Environment Variables
If your project requires any environment variables, create a .env file in the root of the respective directories and add the required keys and values.
Example:
```bash
  URI=<your_db_uri>
