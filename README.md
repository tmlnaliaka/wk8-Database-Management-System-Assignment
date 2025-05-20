# wk8-Database-Management-System-Assignment

## Airline Services Database.

### Project Description

This project implements a MySQL database for an Airline Services system, managing flights, passengers, tickets, aircraft, airports, and crew assignments.
The database is designed to be in at least 3NF, with proper constraints (primary keys, foreign keys, NOT NULL, UNIQUE) and relationships (1-1, 1-M, M-M). It includes:

#### Table Details

Airports: Stores airport details (e.g., JFK, LAX).  
-Aircraft: Stores aircraft details (e.g., model, capacity).  
Flights: Stores flight schedules, linking to airports and aircraft.  
Passengers: Stores passenger information.  
Tickets: Links passengers to flights (M-M relationship).  
Crew: Stores crew member details.  
CrewAssignments: Links crew to flights (M-M relationship).  

#### How to Run/Setup the Project

Import SQL File (airline_services) 
Open MySQL command-line client or a tool like MySQL Workbench.  
Use the command: SOURCE path/to/airline_services.sql; or import the airline_services.sql file via the GUI.  
Verify Setup: Query the tables (e.g., SELECT * FROM Airports;) to ensure they are created correctly.  
