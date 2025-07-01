Railway Reservation System

Project overview:

This project implements a fully functional railway ticket booking and cancellation system using SQL. It is designed to simulate the real-world workflow of train ticketing, including features like seat reservation, cancellation, real-time seat tracking, and PNR generation. The objective was to apply database design principles and SQL queries to build an efficient and normalized relational database that captures the end-to-end flow of passenger ticket management.

The system models core entities such as Trains, Passengers, Routes, Seats, Bookings, and Cancellations. It uses a normalized schema (1NF to 3NF) to ensure data integrity, avoid redundancy, and improve query performance. Relationships among tables are established using primary and foreign keys, and constraints are implemented to maintain consistency.

Key features include the ability to book tickets based on available seats, maintain a waitlist system, handle ticket cancellations with seat reallocation, and automatically update availability status. A unique PNR number is generated for each booking to track transaction details, passenger status, and train schedules.

The project emphasizes the use of SQL constructs such as JOIN, GROUP BY, DATE functions, subqueries, and trigger logic to manage real-time updates. It also includes custom functions and procedures for booking logic, status updates, and fare calculation.
