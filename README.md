# serverless-rest-api-with-aws-lambda

![1!](images/1.png)

In this article, I’ll be making use of the **Serverless Framework** to build and deploy a simple **Node.js API to Lambda and API Gateway**. Our data will be stored using **Amazon Relational Database Service (RDS) for PostgreSQL.**

# Objective

1. Developing a Serverless framework based application using Node.js to build and deploy it to AWS Lambda and AWS API Gateway.
2. Backing up the application with an Amazon Relational Database Service (RDS) for PostgreSQL,using pgAdmin for creation of database and table with the required columns.
3. Fully verifying the implemented REST APIs using Postman running the application on the localhost server on current machine, later migrated the deployment completely on the AWS Lambda and AWS API Gateway services.

# Pre-Requisite

1. Node.js version 6.x or later installed locally on your machine. You can get it here (https://nodejs.org/en/download/).
2. An AWS account, which you can create here (https://aws.amazon.com/resources/create-account/).
3. We’ll be using pgAdmin to create our database tables, you can download that here (https://www.pgadmin.org/download/).
4. Postman, a super handy tool we’ll be using to test our API. Get that here (https://www.postman.com/).

Once you are done with all the pre-requisite installation and setup,we can now proceed ahead in developing the REST API backend application.