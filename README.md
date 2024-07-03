# Argent Bank

![Banking Agency](https://img.shields.io/badge/Banking%20Agency-kasa-green)


This repository contains the code needed to run both the frontend and backend for Argent Bank. The frontend is coded in React, and the backend with Node.js, Express, and MongoDB.

## Description

Argent Bank is a web application for a banking agency.


## Installation

To install and run this project locally on your machine, follow these simple steps:

1. Make sure you have Node.js installed on your machine. If not, you can download and install it from [the official Node.js website](https://nodejs.org/).

2. Clone this GitHub repository to your local machine using the following command:

    ```
    git clone https://github.com/MoonstruckDev/ArgentBank.git
    ```

3. Install the necessary dependencies:

### Frontend Application

Run the following commands:

```bash
# Navigate to the frontend directory
cd Frontend
```

```bash
# Install dependencies
npm install
```

```bash
# Start local dev server
npm start
```

Open your browser and go to the following URL: [http://localhost:3000](http://localhost:3000)

### Backend Server

Run the following commands:

```bash
# Navigate to the server directory
cd server
```

```bash
# Install dependencies
npm install
```

```bash
# Start local dev server
npm run dev:server
```

Your server should now be running at [http://localhost:3001](http://localhost:3001) and you will now have two users in your MongoDB database!

## Populated Database Data

Once you run the `populate-db` script, you should have two users in your database:

### Tony Stark

- First Name: `Tony`
- Last Name: `Stark`
- Email: `tony@stark.com`
- Password: `password123`

### Steve Rogers

- First Name: `Steve`
- Last Name: `Rogers`
- Email: `steve@rogers.com`
- Password: `password456`

## API Documentation

To learn more about how the API works, once you have started your local environment, you can visit: [http://localhost:3001/api-docs](http://localhost:3001/api-docs)

## Design Assets

Static HTML and CSS have been created for most of the site and are located in: `/designs`.

For some of the dynamic features, like toggling user editing, there is a mock-up for it in `/designs/wireframes/edit-user-name.png`.

And for the API model that you will be proposing for transactions, the wireframe can be found in `/designs/wireframes/transactions.png`.

## Technologies Used

- React
- Redux
- MongoDB
- CSS


## How to Contact Me

If you have any questions, comments, or collaboration proposals, feel free to contact me via [Mail](mailto:dev@moonstruck.pro) or through my [LinkedIn profile](https://www.linkedin.com/in/luc-smith-62a4b52a6/).

I am proud to have completed this project which taught me a lot about React, and I am happy to share this experience with you.
