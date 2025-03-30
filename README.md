# Medication Reminder System

This is the super repository for the Medication Reminder System. It integrates the following two repositories:

1. [App](https://github.com/MehdiMamas/nodejs-assessment-app/): Contains the frontend or client-side code.
2. [Server](https://github.com/MehdiMamas/nodejs-assessment-server): Contains the backend code.

## Prerequisites

- Node.js (v16 or later)
- npm (v7 or later)
- Ngrok (for exposing the local server)
- A local database server (optional for bonus features)

## Setup Instructions

### 1. Clone the Super Repository and Submodules

Run the following script to clone the super repository and both submodules:

```bash
git clone https://github.com/MehdiMamas/nodejs-assessment
cd nodejs-assessment
git clone https://github.com/MehdiMamas/nodejs-assessment-app/ app
git clone https://github.com/MehdiMamas/nodejs-assessment-server server
```

### 2. Set Up the Server

Follow the instructions in the `server/README.md` file to set up and run the backend server.

### 3. Set Up the App

Follow the instructions in the `app/README.md` file to set up and run the frontend application.

### 4. Access the Application

- Frontend: Open your browser and navigate to `http://localhost:3000`.
- Backend: The API server will run on `http://localhost:5000`.

## Notes

- Ensure the `.env` file in the `server` repository is properly configured with your API keys.
- Use Ngrok to expose your local server for Twilio webhooks.
- Update any `.env` files as needed for environment-specific configurations.
