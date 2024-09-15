# Restaurant Management System

## Introduction

The **Restaurant Management System** is a comprehensive software solution developed in C++, designed to streamline the operations of a restaurant. It provides robust tools for managing orders, menu items, kitchen operations, and inventory. The system models core components such as a bar, kitchen, and warehouse, offering a structured and efficient approach to restaurant management.

This project emphasizes clean architecture, separation of concerns, and object-oriented design principles. It includes key features like menu management, order tracking, and inventory control.

## Key Features

- **Menu Management**: Add, update, and remove food and drink items, including alcoholic beverages and custom cocktails.
- **Order Management**: Efficiently handle customer orders with functionalities for placing, modifying, and completing orders.
- **Inventory Management**: Track ingredient availability in both the kitchen and warehouse, ensuring stock levels are always up to date.
- **Observer Pattern**: Real-time monitoring of changes within the restaurant system, allowing for reactive updates to inventory and order statuses.
- **Modular Design**: A well-structured, component-based architecture that separates business logic into independent modules (kitchen, bar, menu, etc.).

## Project Structure

The project is divided into several modules, each representing a distinct aspect of the restaurant system:

- **Menu Module**: 
  - `Menu.cpp` and `MenuItem.cpp` handle the management of food and drink items.
  - `Alcoholicdrink.cpp` and `Cocktail.cpp` manage alcoholic beverages.
  
- **Order Module**: 
  - `Order.cpp` manages the lifecycle of customer orders, from creation to completion.
  
- **Operations Module**: 
  - `Bar.cpp` and `Kitchen.cpp` manage specific operations for drinks and food preparation.
  
- **Inventory Module**: 
  - `Warehouse.cpp` and `Ingredient.cpp` handle ingredient tracking and restocking functionalities.

- **Utilities**: 
  - `HelpFunctions.cpp` provides auxiliary functionalities for common operations.
  - `Observer.h` implements the observer design pattern to manage event-driven notifications.

## Technology Stack

- **Programming Language**: C++
- **Development Environment**: Visual Studio
- **Build System**: MSBuild via Visual Studio

## Installation and Setup

### Prerequisites

Ensure you have the following tools installed on your system:

- **Visual Studio 2019 or later** (with C++ support)
- **C++ Compiler** (compatible with Visual Studio)

## Usage Guide

After running the application, you can interact with the system through its console-based interface. Key functionalities include:

- **Menu Operations**: Add or remove food and drink items to and from the menu.
- **Order Operations**: Place orders for a table and modify them as needed.
- **Inventory Management**: Monitor and update ingredient levels in the kitchen and warehouse.

## Contributing

Contributions to this project are welcome. If you would like to contribute:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request to the branch.
