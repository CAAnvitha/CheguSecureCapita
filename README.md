# InvoiceNow: Secure Account Management & Invoicing 

InvoiceNow is a full-stack web application focused on providing secure and efficient customer account management and invoicing services. It uses Java and Spring Boot for the backend, ReactJS for the frontend, and is deployed using Docker.

## Features

- **Secure Authentication**: Implements JWT for secure authentication and role-based authorization.
- **Two-Factor Authentication**: Integrates Twilio for robust two-factor authentication.
- **Asynchronous Processing**: Utilizes Kafka for asynchronous invoice processing, enhancing performance.
- **Secure Storage**: Stores invoices securely in AWS S3.
- **Containerized Deployment**: Uses Docker to containerize both frontend and backend services for consistent deployments.

## Getting Started

### Prerequisites

- Docker
- Java 11 or higher
- Spring Boot
- AngularJS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourgithub/invoicenow.git
   cd invoicenow
   // backend/.env
2.	Set up environment variables
Create .env files for both frontend and backend services. Example variables include:
```DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
TWILIO_API_KEY=your_twilio_api_key

// frontend/.env
REACT_APP_API_URL=http://localhost:8080
```
## Starting the Backend

To start the backend service independently, follow these steps:

1. **Navigate to the backend directory**:
   Open your command line interface and enter:
   ```bash
   cd backend
2. Run the Spring Boot application:
   Execute the following command to start the server:
   ```./mvnw spring-boot:run```
   
##Starting the Frontend

To start the frontend service independently, perform the following:

1.	Navigate to the frontend directory:
    Open a new command line interface window and enter:
  	  ```bash
  	cd frontend
2.	Install dependencies:
Run the following command to install all required npm packages:
``` npm install ```
   
