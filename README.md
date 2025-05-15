# Maruti Hotel Booking and Management System

## Overview

The Maruti Hotel Booking and Management System is a full-stack web application that enables users to book hotel rooms online and allows hotel admins to manage bookings, rooms, and customer information. It streamlines the hotel reservation process with features such as room availability checking, user authentication, booking history, and admin management dashboard.


# Features

* User registration and login

* Search and filter available rooms

* Book rooms and view booking history

* Admin panel for managing rooms, bookings, and customers

* Responsive design for mobile and desktop use


# Tech Stack

## Frontend:

* React.js / HTML / CSS / JavaScript


## Backend:

* Spring Boot (Java)


## Database:

* MySQL / PostgreSQL


## Others:

* REST APIs

* JWT for authentication

* Maven / Gradle for build automation


# Getting Started

Prerequisites

Java 17+

Node.js and npm

MySQL server

Maven (if using Spring Boot with Maven)


# Backend Setup

cd backend
./mvnw spring-boot:run

Frontend Setup

cd frontend
npm install
npm start

## Database Setup

Create a database named hotel_booking_db

Update database config in application.properties:


spring.datasource.url=jdbc:mysql://localhost:3306/hotel_booking_db
spring.datasource.username=your_username
spring.datasource.password=your_password


---

## API Endpoints

POST /api/auth/register – Register a user

POST /api/auth/login – User login

GET /api/rooms – Get all available rooms

POST /api/bookings – Book a room

GET /api/admin/bookings – View all bookings (admin)



## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
