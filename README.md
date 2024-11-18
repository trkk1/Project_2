Project 2 - This project will create a simple Theater Booking System. It allows users to view shows, book tickets, and manage their bookings. The program will use arrays, pointers, structures, enumerations, and file operations to store and manage data.
Features
View Available Shows:
Users can view a list of available movies, including their titles, showtimes, and ticket prices.

Book Tickets:
Users can select a movie and book a certain number of tickets for that movie.

View Bookings:
Users can view their booking details, including the movie title, the number of tickets booked, and the booking status.

File Operations:
Booking data is saved to a file for persistence. Upon startup, previous bookings are loaded from the file.

Technical Details
Arrays and Pointers

Arrays store movie and booking data:
Movies: An array stores details like movie title, showtimes, ticket prices, and available seats.
Bookings: An array stores customer booking details such as name, movie, and the number of tickets booked.
Pointers are used to manage dynamic memory for bookings, allowing for flexible data handling during transactions.
Structures and Advanced Data Types

Movie Structure: Stores movie details including title, showtimes, price, and available seats.
Booking Structure: Stores booking details including the customer’s name, the selected movie, and the number of tickets booked.
Enumerations are used to track the booking status, such as "Confirmed" and "Pending."
String and File Operations

Strings are used for storing movie titles, customer names, and other textual data.
File I/O is used to persist booking data, which is saved and loaded from a file when the application starts or ends.
Code Efficiency and Memory Management

The application efficiently stores, searches, and manages movie and booking data.
Memory management is handled using pointers and dynamic allocation to ensure scalability as users add bookings.
Bonus Features

Booking Limits: The system limits the number of tickets that can be booked per transaction.
Show Availability Update: After a booking, the number of available seats is updated in real time to reflect current availability.

How to Use
Run the Program: Compile and execute the program in a C environment.
View Shows: The list of available movies will be displayed, including the title, showtimes, and prices.
Book Tickets: Select a movie from the list and enter the number of tickets you wish to book. After booking, your reservation details will be shown.
View Your Bookings: You can check your bookings at any time during the session.
File Operations: The system automatically saves booking data to a file, which is loaded when the program starts.
