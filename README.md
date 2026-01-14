# Restaurant Credit Management System

A Spring Boot–based web application for managing restaurant customers, their credit balances, orders, transactions, and settlements in a secure and structured manner.

---

## Overview
Many restaurants manage customer credit manually, which can lead to calculation errors, missing records, and poor financial tracking.  
This application digitizes the entire credit management workflow, ensuring accurate balance calculation, transaction tracking, and secure access.

---

## Key Features

### Customer Management
- Add, update, and delete customers  
- Maintain customer credit limits and current balances  
- Support full and partial credit settlements  

### Order Management
- Create and manage customer orders  
- Automatic credit balance updates on order creation  

### Transaction Management
- Track all credit, debit, and settlement transactions  
- View detailed transaction history per customer  

### Dashboard
- Overview of total outstanding credit  
- Quick access to customers, orders, and transactions  

### Reporting
- Generate customer credit and transaction reports  

---

## Technology Stack
- Java 11  
- Spring Boot  
- Spring Data JPA (Hibernate)  
- Spring Security  
- Thymeleaf  
- Bootstrap 5  
- MySQL Database  
- Maven  

---

## Application Architecture
- **Controller Layer** – Handles HTTP requests and UI navigation  
- **Service Layer** – Business logic and validations  
- **Repository Layer** – Database operations using JPA  
- **Model Layer** – Domain entities (Customer, Order, Transaction, Admin)  
- **Security Layer** – Authentication and authorization configuration  

---

## Getting Started

### Prerequisites
- Java 11 or higher  
- Maven  
- MySQL  

---

### Installation and Setup

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   ```

2. Navigate to the project directory:
   ```bash
   cd restaurant-credit-system
   ```

3. Create a MySQL database:
   ```sql
   CREATE DATABASE restaurant_credit;
   ```

4. Configure the application.properties file with your database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/restaurant_credit
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

5. Build and run the application:
   ```bash
   mvn spring-boot:run
   ```

6. Access the application at: http://localhost:8080

## Usage

1. Register an admin account
2. Log in to access the dashboard
3. Add customers and set their credit limits
4. Create orders and manage credit settlements
5. View transaction history and generate reports

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

