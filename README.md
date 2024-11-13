# QEats - Swiggy-like Food Ordering App

## Overview
QEats is a scalable, distributed food ordering application similar to Swiggy, built using Java and Spring Boot. The backend provides functionality for users to browse food items, place orders, manage restaurants, and track deliveries.

This repository contains a fully functional backend for QEats, utilizing a microservice architecture to support high scalability and availability.

  
## Architecture
- **MVCS Architecture**: The backend follows the Model-View-Controller-Service architecture.
- **Database**: MongoDB is used to store user data, orders, and restaurant details.
- **Spring Boot**: The application is built using Spring Boot for ease of deployment and scalability.
- **Jackson**: For JSON serialization and deserialization to convert Java objects to JSON and vice versa.

## Technologies
- Java 11 or higher
- Spring Boot 2.x
- Spring Data MongoDB
- Jackson for JSON serialization
- MongoDB for persistent storage
- Mockito for unit testing

## Prerequisites
- Java 11 or higher
- MongoDB instance running locally or in the cloud
- Maven or Gradle for dependency management

## Setup Instructions

### Step 1: Clone the repository
```bash
git clone https://github.com/yourusername/QEats.git
cd QEats
