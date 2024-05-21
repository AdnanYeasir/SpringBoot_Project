
# SpringBoot CI/CD Integrator

## Description
SpringBoot CI/CD Integrator is a comprehensive Java and Spring Boot application designed to demonstrate advanced CI/CD processes using GitHub Actions, Docker, and deployment to AWS. This project showcases how to build, test, and deploy a microservices-based application with enhanced security and efficient logging.

## Features
- **CI/CD Pipeline:** Automated build and deployment processes using GitHub Actions.
- **Containerization:** Uses Docker for consistent deployment environments.
- **Cloud Deployment:** Configured to deploy seamlessly to AWS.
- **Microservices Architecture:** Organized into small, independent services for better scalability and maintenance.
- **Security:** Implements OAuth2 and JWT for secure authentication.
- **Logging:** Centralized logging with the ELK Stack for effective monitoring.

## Prerequisites
- Java 8 or higher
- Docker
- AWS Account
- GitHub Account

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AdnanYeasir/springboot-cicd-integrator.git
   cd springboot-cicd-integrator
   ```

2. **Build the Docker image:**
   ```bash
   docker build -t springboot-cicd-integrator .
   ```

3. **Run the Docker container:**
   ```bash
   docker run -p 8080:8080 springboot-cicd-integrator
   ```

## Usage
Navigate to `http://localhost:8080` to access the application through your web browser. The application is set up with several endpoints demonstrating different functionalities of the system.

## Testing
Run the following command to execute the integrated tests:
```bash
mvn test
```

## Deployment
The project includes configuration files for deployment to AWS using GitHub Actions. Ensure your AWS credentials are configured properly.

## Contributing
Contributions to the SpringBoot CI/CD Integrator project are welcome! Please fork the repository and submit a pull request with your improvements.


## Authors
- **Adnan ** -  - [AdnanYeasir](https://github.com/AdnanYeasir)
