# Inventory Management System

## Introduction

Welcome to the Inventory Management App! This project aims to streamline inventory management processes using Laravel for the backend, Vue.js for the frontend, and additional technologies such as Jetstream, Inertia, and Laradock.

## Getting Started

To get started with the project, follow these steps:

1. **Clone Repository**: Clone this repository to your local machine by running the following command in your terminal:

   ```
   git clone https://github.com/dennisgldev/hiring-team-logistica.git
   ```

2. **Initialize Docker Engine**: Ensure Docker Engine is installed and initialized on your local machine.

3. **Start Laradock Services**: Navigate to the `laradock` directory within the project and start the Laradock services by executing the following command:

   ```
   docker-compose up -d nginx mysql phpmyadmin redis workspace
   ```

4. **Install Dependencies**: Navigate back to the project directory and install the necessary dependencies by running:

   ```
   cd ..
   npm install
   npm run dev
   ```

5. **Access the Application**: You can now access the application by navigating to http://localhost in your web browser.

## Test User Credentials

Use the following credentials to log in as a test user:

- **Email:** admin@funiber.org
- **Password:** 12345678

## Acknowledgements

Thank you for considering this project! If you have any questions or feedback, feel free to reach out.
