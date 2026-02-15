# FoodForward

**Digital Food Donation Matching System** — CS 411 Team | Fall 2024

FoodForward connects food donors with recipients, enabling listings, bookings, and reviews to reduce food waste and support communities.

## Tech Stack

- **Backend:** Spring Boot 3.3.5, Java 17, Spring Data JPA, MySQL
- **Frontend:** React, React Router, Tailwind CSS, Font Awesome

## Features

- **Donors:** Create and manage food listings, view bookings
- **Recipients:** Browse listings, filter by location, book pickups
- **Listings:** Items, locations, availability
- **Bookings:** Reserve listings with confirmation flow
- **Reviews & ratings:** Feedback on donations

## Getting Started

### Prerequisites

- Java 17+
- Maven
- Node.js & npm
- MySQL

### Backend

1. Configure MySQL and update `foodforward/src/main/resources/application.properties` with your database URL, username, and password.
2. From the `foodforward` directory:
   ```bash
   cd foodforward
   mvn spring-boot:run
   ```
   The API runs by default on port 8080.

### Frontend

1. From the frontend directory:
   ```bash
   cd foodforward/frontend
   npm install
   npm start
   ```
   The app runs in development mode (default port 3000).
