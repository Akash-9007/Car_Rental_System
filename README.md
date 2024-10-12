# Car_Rental_System
🚗 Car Rental System
Welcome to the Car Rental System! This is a simple Java-based console application that allows users to rent and return cars from a rental company. The system keeps track of available cars, customers, and rentals, ensuring an easy and efficient rental process.

📝 Features
Add Cars: Add new cars to the rental system with specific brands, models, and daily rental prices.
Rent a Car: Users can choose a car, specify rental days, and get a price quote.
Return a Car: Customers can return rented cars and update the system's availability.
Manage Rentals: The system tracks rented cars and ensures that they can only be rented if available.
🚀 Getting Started
Prerequisites
To run this project, you need to have Java installed on your system. You can download it from Oracle's website.

📦 Installation
Clone the repository to your local machine.
Compile the Java files.
Run the main class to start the application.
🏗️ System Design
Car: Represents a car in the system. It stores details like brand, model, base price per day, and availability.
Customer: Stores customer information such as ID and name.
Rental: Tracks rental information, including the car, customer, and rental period.
CarRentalSystem: The main system class that manages cars, customers, and rentals.
📂 Class Diagram
The system consists of the following core classes:

Main
CarRentalSystem
Car
Customer
Rental
🏃‍♂️ Usage
Upon launching the program, users are presented with a menu with the following options:

Rent a Car: Displays available cars, allows renting, and confirms the rental details.
Return a Car: Facilitates returning a car and marks it as available again.
Exit: Exits the program.
