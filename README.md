# CloudResumeChallenge backend with AWS SAM.
Sudha Resume backend with AWS, SAM, DynamoDB, API Gateway, Lambda functions and Infrastructure as code.

This is my writeup for the #CloudResumeChallenge by @forrestbrazeal https://cloudresumechallenge.dev

# Javascript
Resume webpage includes a visitor counter that displays how many people have accessed the site. Used Javascript to discplay this.

# Database
The visitor counter will need to retrieve and update its count in a database somewhere. So used Amazon’s DynamoDB for this.

# API
To avoid communication directly with DynamoDB from frontend's Javascript code, created an API that accepts requests from resume web app and communicates with the DynamoDB database using AWS’s API Gateway and Lambda services for this.

# Python
boto3 library for AWS: Lambda function in back-end function to update DynamoDB using Python as language and boto3 library.

# Infrastructure as Code
To avoid configuring your API resources like the DynamoDB table, the API Gateway, the Lambda function – manually, by clicking around in the AWS console. 
Instead, defined them in an AWS Serverless Application Model (SAM) template and deploy them using the AWS SAM CLI.


Finally a great first Challenge i have done.
Here's the output of this challenge: https://sudhachandranbc.online

> Sudha Chandran [@sudhaKishoreBC](https://twitter.com/SudhaKishoreBC) || <a href="(https://dev.to/sudhachandranbc/sam-serverless-application-model-cloudresumechallenge-dee)">August 1, 2020</a>
