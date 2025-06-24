# Elevate-lab-sql-internship
# Airline Management System – SQL Schema Project

## Overview
This project is a relational database schema designed to manage the core operations of an *Airline Management System*. It covers entities such as airlines, airports, flights, passengers, bookings, ticketing, and staff assignments.

---

## Tech Stack
- *Database*: MySQL
- *Design Tool*: dbdiagram.io
- *Language*: SQL (DDL)

---

## Schema Features

- Define and manage multiple airlines and airports
- Schedule flights with source and destination airports
- Handle passenger records and passport details
- Book flights and assign tickets with seat and class information
- Manage payments and payment methods
- Assign staff (pilots and crew) to scheduled flights
- Enforce data integrity through primary and foreign keys

---

## Tables and Descriptions

| Table Name       | Description |
|------------------|-------------|
| Airlines       | Stores airline company details |
| Airports       | Contains airport information |
| Flights        | Flight number and route details |
| FlightSchedule | Departure and arrival times, flight status |
| Passengers     | Passenger contact and ID details |
| Bookings       | Flight bookings and their status |
| Tickets        | Ticket class, seat, and pricing |
| Payments       | Payment amount, method, and status |
| Staff          | Airline staff (pilots, crew) info |
| FlightCrew     | Staff assignments to flight schedules |

---

## How to Run

1. Open MySQL Workbench or any MySQL interface.
2. Run the script from airline_schema.sql (containing all CREATE TABLE statements).
3. The schema will be created under the database AirlineManagementSystem.

---
## Author

Manas Ravi Chandran  
Intern - SQL Developer
