# Movie Ticket Booking
A Basic Movie Ticket Booking System. Best suited for someone who is a beginner in Java full stack development. 

## About
The Software system is an online movie ticket booking system where customers can book seats according to their preference.<br>
## Technologies Used
* SpringBoot
* Java
* AngularJS
* Git
* HTML
* CSS
* Bootstrap
## Features
* All active movies are available for booking.
* Customer can select seat according to their preference.
* System is validated for smooth functioning.# Movie Ticket Booking System

A beginner-friendly project for developing a basic movie ticket booking system, ideal for those new to Java full-stack development.

## Overview
This software enables users to book movie tickets online, allowing them to choose seats based on availability and preference.

## Technologies
- **Backend**: Spring Boot, Java
- **Frontend**: AngularJS, HTML, CSS, Bootstrap
- **Version Control**: Git

## Key Features
- View all active movies available for booking.
- Select seats based on user preference.
- Includes validation to ensure smooth and error-free booking experience.

## Database
The application uses an H2 in-memory database for demonstration purposes, making it easy to set up and test locally. 
- If users want to connect a different database, they can adjust settings in the `application.properties` file.
- Some sample data is pre-loaded for quick testing.

## Sample Data
- Four movies are available in four different theaters, with four shows each scheduled for the current day.
- The application automatically updates the status of each show:
  - **Completed**: If the show’s end time has passed, bookings are closed.
  - **In Progress**: If the show has started but not yet ended, bookings are restricted.

This setup provides a seamless user experience and ensures all interactions are validated for ease of use.

