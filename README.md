# Flight-Reservation-System
**1. Data Structure**
   
 The program establishes a data structure known as Flight, which encompasses the following information:
 - Flight number, along with departure and arrival locations.
 - Departure and arrival times.
 - Total seats available in First Class, Business, and Economy.
 - Ticket prices for each class.

**2. Major Functionalities**

   **a. User Authentication**
  
  - Users can Sign Up by providing a username and password, which is saved in a file (users.txt).
  - Users can Sign In by providing their credentials, which are checked against the saved data.
    
   **b. Flight Booking System**

  - The system offers International and Domestic flight options.
  - Users choose a flight and class of seat (First, Business, or Economy).
  - If the chosen seat is free, a ticket is created, and the seat number is decreased.
  - Ticket information is saved in a file (ticket.txt).
  - 
   **c. Flight Cancellation**

  - There is an option to cancel the booking for users.
  - If cancelled, the seat is returned to the availability of the flight.

**3. Features & Implementation**

  - Employs file handling to save user information and create ticket information.
  - Employs loops and conditionals for menu handling.
  - Employs arrays to save multiple flight information.
  - Handles seat availability dynamically as per bookings and cancellations.
     
**4. Possible Improvements**

  - Implement GUI for improved user experience.
  - Integrate payment processing.
  - Enhance error handling for wrong inputs.
  - Implement a database rather than file storage.

**5. Dependencies**

  - C++ Standard Library (iostream, fstream, string)
    
**6. Author**

  - Nibtahil Sohail
  - Abdullah Tahir
  - Khansa Jamal
  - Malahim Hider
