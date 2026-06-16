# Car-Rental-Site-SDA

The purpose of the site is to simulate a car rental platform where users can browse and rent vehicles for a specified number of days. This project was created to showcase different software design patterns being implemented an demonstrated. The focus is on design and architecture rather than production-ready business functionality.

## Repository Structure

```
Car-Rental-Site-SDA/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── carrental/
│   │   │           ├── builder/
│   │   │           ├── command/
│   │   │           ├── factory/
│   │   │           ├── mediator/
│   │   │           ├── observer/
│   │   │           ├── model/
│   │   │           ├── service/
│   │   │           └── controller/
│   │   └── resources/
│   └── test/
│       └── java/
├── pom.xml
├── mvnw
├── mvnw.cmd
├── .gitignore
├── .gitattributes
└── README.md
```

## Technologies Used
- Java
- Maven
- HTML
- CSS

## Design Patterns Implemented

### 1- Builder Pattern [Needs rework and correction]

The Builder Pattern is used to construct complex objects step-by-step while keeping object creation separate from business logic.

### 2- Command Pattern

The Command Pattern encapsulates requests as objects.

### 3- Factory Pattern

The Factory Pattern centralizes object creation.

### 4- Mediator Pattern

The Mediator Pattern controls communication between multiple components.

### 5- Observer Pattern

The Observer Pattern enables one-to-many communication between objects.

## Running the Project

### Prerequisites
- Java 17+ (or project-required version)
- Maven

### Build

```
mvn clean install
```

### Run

``` 
mvn spring-boot:run
```
