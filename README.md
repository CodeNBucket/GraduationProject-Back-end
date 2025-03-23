
# Rent Finder Backend

The backend for *Rent Finder*, a web application designed to help users find rental properties while ensuring the credibility of reviews through machine learning algorithms for fake review detection and sentiment analysis. The backend is built using Spring Boot and handles user authentication, property listings, and review management.

## Features

- **User Authentication:** Secure user registration and login functionality.
- **Property Management:** Endpoints for adding, updating, and deleting property listings.
- **Review Management:** Endpoints for submitting, updating, and displaying property reviews.
- **Fake Review Detection:** Machine learning-based model to identify fraudulent reviews.
- **Sentiment Analysis:** Analyzes reviews to determine the overall sentiment.

## Tech Stack

- **Backend Framework:** Spring Boot
- **Database:** PostgreSQL
- **Security:** Spring Security
- **Machine Learning (for Fake Review Detection & Sentiment Analysis):** Python

## Prerequisites

- **JDK 17** or higher
- **Maven**
- **PostgreSQL**
- **Python** (for machine learning models)

## Installation

### 1. Clone the Repository

Clone the backend repository to your local machine:

```bash
git clone https://github.com/your-username/rent-finder-backend.git
```

### 2. Set Up Database

1. Create a PostgreSQL database for the project.

2. Configure the database connection in `src/main/resources/application.yaml`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/rent_finder
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 3. Build the Project

Navigate to the project directory and install the required dependencies using Maven:

```bash
cd rent-finder-backend
mvn clean install
```

### 4. Run the Application

To run the Spring Boot application:

```bash
mvn spring-boot:run
```

The backend will be running at `http://localhost:8080`.


