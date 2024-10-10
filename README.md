# Hospital-appointment-booking-system
-------------------------------------
Overview:
--------
This Appointment Booking System enables users to book and cancel appointments with doctors in a hospital setting. It also includes a billing system for managing user bills and processing payments. This repository contains the server and client components necessary for the operation of the system, along with a performance monitoring client.
Features:
--------
Appointment Booking: Users can book and cancel appointments with available doctors.
Billing Management: Users can check their pending bills and process payments, with options for insurance claims.
Performance Monitoring: A dedicated client that simulates user interactions and logs performance metrics for server responses.
Technologies Used:
-----------------
Python: All code is written in Python, which is the primary programming language used.
Socket Programming: The system uses socket programming for client-server communication, allowing for real-time interaction between users and servers.
Multithreading: The servers utilize threading to handle multiple client connections simultaneously.
JSON: User bills are stored and loaded using JSON format for easy serialization and deserialization.
CSV: The performance monitoring client logs metrics to a CSV file for analysis.
Logging: The application uses the logging module for debugging and tracking performance metrics.
Components:
-----------
1. Appointment Booking Server
File: appointment_server.py
Functionality: Manages user appointments and doctor availability, processes booking and cancellation requests.
2. Billing Server
File: billing_server.py
Functionality: Handles billing queries and payment processing for users.
3. Performance Monitoring Client
File: performance_monitor.py
Functionality: Automates user input to the main and billing servers, measures response times, and logs performance data to a CSV file.
Usage:
------
Booking Appointments: Users can connect to the appointment server to book and cancel appointments.
Checking Bills: Users can connect to the billing server to check pending bills and make payments.
Performance Monitoring: The performance monitoring client will periodically simulate user interactions and log performance metrics.
