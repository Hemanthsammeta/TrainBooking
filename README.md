# Train Seat Reservation System

## Description
This project is a Train Seat Reservation System built using Spring Boot. It allows users to reserve seats in a train coach. The coach has a total of 80 seats organized in rows, and users can reserve up to 7 seats at a time. The system prioritizes booking in one row and displays the seat availability status.

## Features
- Reserve up to 7 seats at a time.
- Prioritize booking in the same row.
- Display available and booked seats.
- Simple REST API for seat reservation.

## Technologies Used
- Spring Boot
- Java
- Maven

## Getting Started

### Prerequisites
- JDK 11 or higher
- Maven
- Git

### Installation
 
 **Clone the repository:**
     git clone https://github.com/Hemanthsammeta/TrainBooking.git

 **Navigate to the project directory:**
      cd TrainSeatReservation1
 
 **Build the project:**
      mvn clean package
 **Run the application:**
      java -jar Hemanth.jar

### API Endpoints
  **Get Seat Status: GET /seats**
  **Book Seats: GET /seats/book?numSeats={number_of_seats}**
  



