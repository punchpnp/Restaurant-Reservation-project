<p align="center">
  <img src="https://drive.google.com/uc?id=1f-WRLlX9blyBdRAci8YmSxvW3VNcYZ24" alt="Alt Text" height="400">
</p>

# Restaurant Reservation Project - Backend

This is the backend repository for the Restaurant Reservation project, built using Express and Node.js.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Team Process](#team-process)

## Introduction

The Restaurant Reservation project is designed to facilitate restaurant reservation and management. This backend repository serves as the server-side application handling user authentication, reservation creation, and restaurant-related functionalities.

## Features

- User Registration and Login
- Reservation Management
- Restaurant Information

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- npm (Node Package Manager) installed
- MongoDB installed and running (or provide a connection string to an online MongoDB instance)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/punchpnp/Restaurant-Reservation-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Restaurant-Reservation-project
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To start the server, run the following command:

```bash
npm run dev
```

This will start the server at `http://localhost:5000` by default.

## API Endpoints

- **User Routes:**
  - `POST /api/v1/auth/register`: Register a new user.
  - `POST /api/v1/auth/login`: Log in an existing user.
  - `GET /api/v1/auth/me`: Get User's data.
  - `GET /api/v1/auth/logout`: Log out.

- **Reservation Routes:**
  - `GET /api/v1/reservation/:reservation_ID`: Get details for a specific reservation.
  - `GET /api/v1/reservation`: Get a list of all reservations.
  - `POST /api/v1/reservation` : Create new reservation.
  - `PUT /api/v1/reservation/:reservation_ID` : Update reservation
  - `DELETE /api/v1/reservation/:reservation_ID` : Delete reservation
- **Restaurant Routes:**
  - `GET /api/v1/restaurant/:restaurant_ID`: Get details for a specific restaurant.
  - `GET /api/v1/restaurant`: Get a list of all restaurants.
  - `POST /api/v1/restaurant` : Create new restaurant.
  - `PUT /api/v1/restaurant/:restaurant_ID` : Update restaurant
  - `DELETE /api/v1/restaurant/:restaurant_ID` : Delete restaurant

## Authentication

User authentication is implemented using JSON Web Tokens (JWT). To access protected routes, include the JWT token in the request headers.

## Team Process

<p align="center">
  <img src="https://drive.google.com/uc?id=1rZAtJ3nrL_tklx3kJaoYpY9TEJDMQkIc" alt="Alt Text" weight="100%">
</p>
