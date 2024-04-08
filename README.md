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
├── loans/
│ ├── default.yml
│ ├── prod.yml
│ └── qa.yml
│
├── accounts/
│ ├── default.yml
│ ├── prod.yml
│ └── qa.yml
│
└── cards/
├── default.yml
├── prod.yml
└── qa.yml
```

Each microservice directory contains YAML configuration files for the **default**, **prod**, and **qa** profiles.

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
