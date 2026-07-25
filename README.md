#  Fetch Data with Lambda

##  Project Overview

This project demonstrates how to use **AWS Lambda** to retrieve data from an **Amazon DynamoDB** table.

The Lambda function is configured to connect with DynamoDB, fetch the required user data, and return the retrieved information. This project provides practical experience in working with AWS serverless computing and NoSQL databases.

---

##  Architecture

```text
AWS Lambda
     │
     │ Fetch Data
     ▼
Amazon DynamoDB
     │
     │ Return Data
     ▼
AWS Lambda
```

---

##  AWS Services Used

| AWS Service         | Purpose                                                       |
| ------------------- | ------------------------------------------------------------- |
| **AWS Lambda**      | Runs the serverless function and retrieves data from DynamoDB |
| **Amazon DynamoDB** | Stores and manages the user data                              |

---

##  How It Works

1. An AWS Lambda function is created to retrieve user data.
2. The Lambda function connects to the DynamoDB table.
3. The function requests the required data from DynamoDB.
4. DynamoDB returns the requested data.
5. The Lambda function processes the retrieved information.
6. The result is returned as the Lambda function output.

---

##  Project Objectives

* Understand the basics of AWS Lambda.
* Learn how Lambda functions interact with DynamoDB.
* Retrieve data from a NoSQL database using serverless computing.
* Understand AWS Identity and Access Management permissions required for Lambda.
* Gain practical experience with AWS serverless services.

---

##  Project Output

The project output screenshots demonstrate the implementation and execution of the Lambda function.

The screenshots include:

* AWS Lambda function configuration.
* Lambda function code.
* Amazon DynamoDB table and stored data.
* Lambda execution result showing the retrieved data.

All project output screenshots are available in the **`screenshots`** folder.

---

##  Project Documentation

The complete project documentation is available below:

**[View Project Documentation](documentation/project-documentation.pdf)**

---

##  Key Learnings

Through this project, I gained practical experience in:

* AWS Lambda and serverless computing.
* Amazon DynamoDB and NoSQL databases.
* Retrieving data from DynamoDB using Lambda.
* Understanding Lambda execution and testing.
* Configuring permissions for AWS service integration.
* Working with serverless AWS architecture.

---

##  Project Outcome

Successfully created and tested an AWS Lambda function that retrieves user data from an Amazon DynamoDB table.

This project helped strengthen my practical understanding of **AWS Lambda, DynamoDB, serverless computing, and AWS cloud service integration**.

---

##  Technologies Used

* AWS Lambda
* Amazon DynamoDB
* Serverless Computing
* NoSQL Database

---

 **This project was completed as part of my hands-on learning and practical experience with AWS Cloud and Serverless technologies.**
