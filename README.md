#  Fetch Data with AWS Lambda

##  Project Overview

This project demonstrates how to retrieve data from an **Amazon DynamoDB** table using an **AWS Lambda** function.

The Lambda function is designed to access the DynamoDB table, retrieve the required user data, and return the results as the function output. This hands-on project provides practical experience with AWS serverless computing, NoSQL databases, Lambda execution, and AWS Identity and Access Management (IAM) permissions.

---

##  Architecture

```text
┌─────────────────────┐
│     AWS Lambda      │
│  Serverless Logic   │
└──────────┬──────────┘
           │
           │ Retrieve Data
           ▼
┌─────────────────────┐
│   Amazon DynamoDB   │
│    User Data        │
└──────────┬──────────┘
           │
           │ Return Data
           ▼
┌─────────────────────┐
│     Lambda Output   │
│  Retrieved Results  │
└─────────────────────┘
```

---

##  AWS Services Used

| AWS Service         | Purpose                                                         |
| ------------------- | --------------------------------------------------------------- |
| **AWS Lambda**      | Runs the serverless function and retrieves data from DynamoDB   |
| **Amazon DynamoDB** | Stores and manages user data                                    |
| **AWS IAM**         | Controls the permissions required for Lambda to access DynamoDB |

---

##  How It Works

1. An AWS Lambda function is created to retrieve user data.
2. The Lambda function is configured with the required IAM permissions.
3. The function accesses the Amazon DynamoDB table.
4. Lambda retrieves the requested data from DynamoDB.
5. DynamoDB returns the data to the Lambda function.
6. Lambda processes the retrieved information.
7. The retrieved data is displayed in the Lambda execution result.

---

##  Project Objectives

* Understand the fundamentals of AWS Lambda.
* Learn how to retrieve data from Amazon DynamoDB using Lambda.
* Understand how serverless functions interact with AWS services.
* Configure IAM permissions for secure service access.
* Test Lambda functions and validate execution results.
* Gain practical experience with AWS serverless architecture.

---

##  Repository Structure

```text
fetch-data-with-lambda/
│
├── README.md
│
├── lambda/
│   └── lambda_function.py
│
├── lambda-policy.json
├── [second-json-file].json
│
├── screenshots/
│   ├── dynamodb.png
│   ├── lambda.png
│   └── output.png
│
└── documentation/
    └── project-documentation.pdf
```

> **Note:** Replace `[second-json-file].json` with the actual name of your second JSON file.

---

##  Configuration Files

This repository includes JSON configuration files used during the project implementation.

* **`lambda-policy.json`** – Contains the IAM policy configuration required for the Lambda function to access DynamoDB.
* **`[second-json-file].json`** – Contains additional configuration or policy information used during the project.

These files are included for project documentation and reference.

---

##  Project Screenshots

The `screenshots` folder contains visual evidence of the project implementation and output.

The screenshots demonstrate:

* Amazon DynamoDB table and stored user data.
* AWS Lambda function configuration and code.
* Lambda function execution and retrieved data output.

---

## Project Documentation

The complete project documentation is available in the `documentation` folder.

 **Project Documentation:**
`documentation/project-documentation.pdf`

The documentation provides additional details about the project implementation, AWS services, configuration, and results.

---

##  Key Learnings

Through this project, I gained practical experience in:

* AWS Lambda and serverless computing.
* Amazon DynamoDB and NoSQL databases.
* Retrieving DynamoDB data using Lambda.
* AWS IAM policies and permissions.
* Connecting AWS services securely.
* Testing and validating Lambda function execution.
* Understanding serverless cloud architecture.

---

##  Security Considerations

The project follows the principle of granting only the required permissions for AWS service access.

No AWS credentials, secret keys, passwords, or other sensitive information should be stored in this repository.

---

##  Project Outcome

Successfully created and tested an **AWS Lambda function that retrieves user data from an Amazon DynamoDB table**.

This project strengthened my practical understanding of **AWS Lambda, Amazon DynamoDB, IAM permissions, serverless computing, and cloud service integration**.

---

##  Technologies Used

* **AWS Lambda**
* **Amazon DynamoDB**
* **AWS IAM**
* **Python**
* **JSON**
* **Serverless Computing**

---

 **This project was completed as part of my hands-on learning and practical experience with AWS Cloud and Serverless technologies.**
