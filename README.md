StayBooker

StayBooker is a comprehensive hotel booking management system built using React for the frontend and Spring Boot for the backend. This application allows users to search for hotels, view room details, make reservations, and manage bookings efficiently.

Features
User Registration and Authentication: Secure user registration and login functionalities.
Hotel and Room Management: CRUD operations for hotels, rooms, and room types.
Search and Booking: Easy search for hotels based on location, dates, and room availability.
Payment Integration: Secure online payment processing.
Booking Management: View, modify, and cancel bookings.
Admin Dashboard: Manage hotels, rooms, bookings, and users.

Technologies Used
Frontend
React: JavaScript library for building user interfaces.
Axios: Promise-based HTTP client for making API requests.
React Router: Declarative routing for React applications.
Material-UI: React components for faster and easier web development.

Backend
Spring Boot: Framework for building production-ready applications.
Spring Security: Provides authentication and authorization support.
Spring Data JPA: Abstraction over the persistence layer.
Hibernate: ORM framework for managing database operations.
MySQL: Relational database management system.
Swagger: API documentation and testing.


Installation
Frontend
1) git clone https://github.com/yourusername/staybooker.git
cd staybooker/frontend
2)npm install
3)npm start

Backend
1)cd staybooker/backend
2)Configure the database:
Create a MySQL database named staybooker.
Update the application.properties file with your database credentials.
3)run the springboot Application

API Endpoints

Authentication
POST /api/auth/register: Register a new user.
POST /api/auth/login: Authenticate a user and return a token.

Hotels
GET /api/hotels: Get a list of all hotels.
GET /api/hotels/{id}: Get details of a specific hotel.
POST /api/hotels: Add a new hotel (admin only).
PUT /api/hotels/{id}: Update hotel details (admin only).
DELETE /api/hotels/{id}: Delete a hotel (admin only).

Rooms
GET /api/rooms: Get a list of all rooms.
GET /api/rooms/{id}: Get details of a specific room.
POST /api/rooms: Add a new room (admin only).
PUT /api/rooms/{id}: Update room details (admin only).
DELETE /api/rooms/{id}: Delete a room (admin only).

Bookings
GET /api/bookings: Get a list of all bookings.
GET /api/bookings/{id}: Get details of a specific booking.
POST /api/bookings: Create a new booking.
PUT /api/bookings/{id}: Update booking details.
DELETE /api/bookings/{id}: Cancel a booking.


