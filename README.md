# University Course Management System (UCMS) - Frontend

### Overview
The UCMS-UI is the frontend application for the University Course Management System, built with React, Vite, and TypeScript. It provides a user-friendly interface for managing university courses, student registrations, and administrative tasks, communicating with the UCMS backend via RESTful APIs. This project is optimized for fast development and production builds using Vite and is deployed on Vercel for seamless hosting.
- Vercel Link - https://ucms-ui.vercel.app/

### Prerequisites
To run this project locally, ensure you have the following installed:
- Node.js: Version 18 or higher
- npm: Version 9 or higher (comes with Node.js)
- IDE: Optional (e.g., VS Code for easier development)
- Backend: The UCMS Backend running locally or deployed

### Installation
Follow these steps to set up the project locally:
1. Clone the Repository:
```
git clone https://github.com/AjinthaSivam/UCMS-UI.git
cd UCMS-UI
```
2. Install Dependencies:
- Run the following command to install the required npm packages:
```
npm install
```
3. Configure Environment Variables:
- Create a .env file in the root directory based on .env.example (if provided).
- Set the backend API URL to connect to the UCMS backend:
```
VITE_API_URL=http://localhost:8080
```
- Replace http://localhost:8080 with the actual URL of your running backend (local or deployed).

### Running the Application Locally
1. Start the Development Server:
- Run the following command to start the Vite development server:
```
npm run dev
```
The application will be available at http://localhost:5173 (or another port if 5173 is in use).

2. Access the Application:
- Open your browser and navigate to http://localhost:5173.
- Ensure the backend is running and accessible at the URL specified in the .env file.

### License
This project is licensed under the MIT License. See the LICENSE file for details.
