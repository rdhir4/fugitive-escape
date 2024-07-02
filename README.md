# Fugitive Capture Game

## Overview
This is a web application where users can help three cops find a fugitive by selecting cities and vehicles for each cop. The application is built with React on the frontend and Node.js on the backend.

## Assumptions
1. The fugitive is randomly located in one of the cities.
2. There is no persistent database; data is stored in-memory for simplicity.
3. The images for cities, vehicles, and cops are stored locally in the `public/images` directory.

## Technologies Used
- **Frontend**: React, Material-UI, Axios
- **Backend**: Node.js, Express

## Setup and Build Steps

### Backend

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the backend server:
    ```bash
    npm start
    ```
   The backend server will run on `http://localhost:5000`.

### Frontend

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the frontend server:
    ```bash
    npm start
    ```
   The frontend application will run on `http://localhost:3000`.

### Running the Application
1. Ensure both the backend and frontend servers are running.
2. Open your browser and navigate to `http://localhost:3000`.
3. Use the application to select cities and vehicles for each cop to attempt to find the fugitive.

## Folder Structure
- **backend**: Contains the Node.js backend server code.
  - **controllers**: Controllers for handling API requests.
  - **routes**: Route definitions for API endpoints.
  - **services**: Business logic for handling game logic.
  - `server.js`: Main server file.

- **frontend**: Contains the React frontend application code.
  - **components**: React components for the application.
  - **services**: Service file for making API calls to the backend.
  - **themes**: Theme file for Material-UI customization.
  - `App.js`: Main application file.
  - `index.js`: Entry point for the React application.

### Netlify
1. The Frontend is deployed on netlify, In order for it to connect to backend, backend must be running on localhost on port 5000.

## Authors
- Raghav

## License
This project is licensed under the MIT License.