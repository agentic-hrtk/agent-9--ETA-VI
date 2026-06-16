# Migration Owner Inventory

## Related Repositories

- **[api-gateway](https://github.com/agentic-hrtk/api-gateway)**: Internal API gateway and rate-limiting service
- **[payroll-processor](https://github.com/agentic-hrtk/payroll-processor)**: Bi-weekly payroll computation and ACH transfer engine
- **[financial-reporting](https://github.com/agentic-hrtk/financial-reporting)**: Quarterly financial report generation and filing
- **[ml-model-training](https://github.com/agentic-hrtk/ml-model-training)**: Proprietary ML pipeline for customer churn and LTV prediction
- **[customer-data-pipeline](https://github.com/agentic-hrtk/customer-data-pipeline)**: ETL pipeline for customer analytics and segmentation
- **[auth-service](https://github.com/agentic-hrtk/auth-service)**: OAuth2 / JWT authentication microservice
- **[internal-hr-system](https://github.com/agentic-hrtk/internal-hr-system)**: Employee management and HR portal (internal)

## README Contents

### api-gateway

```
# API Gateway

This repository contains the code for the internal API gateway and rate-limiting service.

## Dependencies

- **auth-service**: For OAuth2 authentication and JWT token validation.
- **customer-data-pipeline**: For customer data enrichment.
```

### payroll-processor

```
# Payroll Processor

This repository contains the code for the bi-weekly payroll computation and ACH transfer engine.

## Dependencies

- **auth-service**: For OAuth2 authentication and JWT token validation.
- **financial-reporting**: For financial data integration.
```

### financial-reporting

```
# Financial Reporting

This repository contains the code for the quarterly financial report generation and filing.

## Dependencies

- **auth-service**: For OAuth2 authentication and JWT token validation.
- **payroll-processor**: For payroll data integration.
```

### ml-model-training

```
# ML Model Training

This repository contains the code for the proprietary ML pipeline for customer churn and LTV prediction.

## Dependencies

- **customer-data-pipeline**: For customer data ingestion.
- **auth-service**: For OAuth2 authentication and JWT token validation.
```

### customer-data-pipeline

```
# Customer Data Pipeline

This repository contains the code for the ETL pipeline for customer analytics and segmentation.

## Dependencies

- **auth-service**: For OAuth2 authentication and JWT token validation.
- **ml-model-training**: For ML model training data.
```

### auth-service

```
# Auth Service

This repository contains the code for the OAuth2 / JWT authentication microservice.

## Dependencies

- **None**: This service is standalone.
```

### internal-hr-system

```
# Internal HR System

This repository contains the code for the employee management and HR portal (internal).

## Dependencies

- **auth-service**: For OAuth2 authentication and JWT token validation.
- **payroll-processor**: For payroll data integration.
```
