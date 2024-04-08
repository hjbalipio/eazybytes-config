# Microservices Configuration Repository

This repository contains YAML configuration files for the **loans**, **accounts**, and **cards** microservices. Each microservice has three profiles: **default**, **prod**, and **qa**, which are used for different deployment environments.

## Microservices Overview

- **Loans Microservice**: Responsible for managing loan-related functionalities.
- **Accounts Microservice**: Manages account-related operations.
- **Cards Microservice**: Handles card-related functionalities.

## Configuration Profiles

- **Default**: Default configuration settings applicable across all environments.
- **Prod**: Configuration settings optimized for production deployment.
- **QA**: Configuration settings tailored for the QA/testing environment.

## File Structure

The repository is organized as follows:

```
microservices-config/
│
├── accounts/
│ ├── accounts.yml
│ ├── accounts-prod.yml
│ └── accounts-qa.yml
│
├── cards/
│ ├── cards.yml
│ ├── cards-prod.yml
│ └── cards-qa.yml
│
└── loans/
├── loans.yml
├── loans-prod.yml
└── loans-qa.yml
```

Each microservice directory contains YAML configuration files for the **default**, **prod**, and **qa** profiles.

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   ```
   
1. Navigate to the desired microservice directory and profile:

   ```bash
   cd microservices-config/loans
   ```
1. Modify the configuration files according to your requirements. Use these configuration files with your Spring Boot application by specifying the appropriate profile during deployment.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.
