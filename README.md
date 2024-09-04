# 🚗 Car Rental System

A simple yet powerful command-line-based Car Rental System built in Java. This project allows users to rent and return cars, while efficiently managing vehicle availability and customer details. The system is designed using Object-Oriented Programming (OOP) principles for better code organization and maintainability.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)

## 🌟 Overview

The Car Rental System is designed to manage a fleet of cars that customers can rent for a specified number of days. The system ensures that cars are only rented if available and properly handles the return process. Built with a focus on simplicity and efficiency, this system is ideal for small car rental businesses or as a learning project for Java developers.

## ✨ Features

- **Car Management**: Add and manage cars in the system.
- **Customer Management**: Add and track customer details.
- **Rental Management**: Rent cars to customers and calculate the total rental price based on the number of rental days.
- **Return Management**: Process car returns and update availability.
- **Command-line Interface**: Interact with the system through a simple and intuitive command-line menu.

## 🛠️ Technologies

- **Java**: Core language used for the entire application.
- **OOP Principles**: Encapsulation, inheritance, and polymorphism for better structure and code reusability.

## ⚙️ Setup Instructions

Follow these steps to set up and run the Car Rental System on your local machine:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system

## 🚀 Usage
- **Rent a Car**: Select the car you want to rent from the list of available cars and enter the number of days for rental. The system will calculate the total price and confirm the rental.
- **Return a Car**: Enter the ID of the car you want to return. The system will update the car's availability status.
- **Exit**: Close the application when done.

## 🎥 Demo
- **Renting a Car**:
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: Nilansh

Available Cars:

C0001 - Mercedes Maybach GLS600

C0002 - BMW X80

Enter the car ID you want to rent: C0001

Enter the number of days for rental: 5

== Rental Information ==

Customer ID: CUS1

Customer Name: Nilansh

Car: Mercedes Maybach GLS600

Rental Days: 5

Total Price: $400.00


Confirm rental (Y/N): Y

Car rented successfully.

- **Returning a Car**:

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit

Enter your choice: 2

== Return a Car ==

Enter the car ID you want to return: C0001

Car returned successfully by Nilansh.

## 🤝 Contributing
Contributions are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request or open an issue.

1. **Fork the repository.**
2. **Create a new branch (`git checkout -b feature-branch`).**
3. **Commit your changes (`git commit -m 'Add a feature`).**
4. **Push to the branch (`git push origin feature-branch`).**
5. **Open a pull request.**
