
# Node.js REST API Deployment to AWS Lambda

This repository contains a simple Node.js-based REST API for managing items. The API allows you to perform CRUD (Create, Read, Update, Delete) operations on a collection of items.

# Prerequisites

Install Node.js

Make sure you have Node.js and NPM (Node Package Manager) installed on your machine. You can download them from the official Node.js website: https://nodejs.org/
## Instructions

- Clone or download this project from GitHub to your local machine

```bash
https://github.com/Suraj127-git/nodejs_restapi_lambda.git

cd nodejs_restapi_lambda
```
- Initialize the Project:
```bash
npm init -y
```

- Install Dependencies

Next, install the required dependencies - Express and Serverless Framework:

```bash
npm install express serverless-http serverless -S
```

- Configure AWS Credentials

After installing the AWS CLI, open the terminal and run the following command to configure your AWS credentials:

```bash
aws configure
```

You'll be prompted to enter your AWS Access Key ID, Secret Access Key, default region, and default output format. These credentials will be used by the Serverless Framework to authenticate with AWS and deploy your application.

- Deploy to AWS Lambda

To deploy the REST API to AWS Lambda, use the following command:

```bash
npx serverless deploy
```

This will package and deploy your application to AWS Lambda, and Serverless Framework will provide you with the API endpoint URL where your Lambda function is accessible.

That's it! You now have a simple Node.js REST API with POST, GET, PUT, and DELETE endpoints deployed on AWS Lambda. You can access the API by using the provided endpoint URL, e.g., https://your-api-endpoint.amazonaws.com/items.

## Note

The information in this README assumes that you have the necessary Nodejs installations on your system. If you encounter any issues, please ensure that you have the correct versions of Nodejs installed.

## Document

For more information read Documentation
