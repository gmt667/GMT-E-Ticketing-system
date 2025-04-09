# GMT-E-Ticketing-system Booking WebApp for GMT

Welcome to the E-Ticket Booking WebApp for GMT! This repository hosts the source code for a robust e-ticket booking system tailored for Road Transport Corporations (RTC). The application ensures a smooth and efficient online ticket booking experience, complete with QR-coded tickets for hassle-free validation.

## Features

- **Modern User Interface**: Developed using ReactJS and Material UI for a responsive and intuitive design.
- **Secure Authentication**: Incorporates secure user authentication and role-based access control.
- **Comprehensive Booking System**: Enables users to search routes, view schedules, and book tickets effortlessly.
- **QR Code Integration**: Generates QR-coded tickets for streamlined validation and boarding.

## Technologies Used

### Frontend
- **ReactJS**: A powerful library for building dynamic user interfaces.
- **Material UI**: A React-based framework for crafting visually appealing and responsive designs.

### Backend
- **NodeJS**: A runtime environment for executing JavaScript on the server side.
- **ExpressJS**: A minimalist framework for building web applications and APIs.

### Additional Tools
- **JWT**: Used for secure token-based authentication.
- **QR Code Library**: Facilitates the generation of QR codes for tickets.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Vinamra2003/rtc-eticket-booking.git
    cd rtc-eticket-booking
    ```

2. **Install dependencies**:
    - For the frontend:
        ```sh
        cd client
        npm install
        ```
    - For the backend:
        ```sh
        cd server
        npm install
        ```

3. **Configure environment variables**:
    - Create a `.env` file in the `server` directory and define the required variables (e.g., database connection string, JWT secret).

4. **Run the application**:
    - Start the backend server:
        ```sh
        cd server
        npm start
        ```
    - Start the frontend development server:
        ```sh
        cd client
        npm start
        ```

5. **Access the application**:
    Open your browser and navigate to `http://localhost:3000` to explore the application.

## Contribution

We welcome contributions! Feel free to fork this repository, enhance the codebase, and submit pull requests. Whether it's fixing bugs, introducing new features, or improving documentation, your efforts are highly appreciated.

Thank you for exploring the E-Ticket Booking WebApp for GMT repository! We hope this application simplifies your ticket booking experience. Happy booking!

