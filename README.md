# AWS Digital Guestbook

This is a serverless digital guestbook I built using AWS cloud services.

Users can:

- Submit messages

- Share feedback

- Upload photos and videos

## Architecture

The application uses a serverless AWS architecture:

1. The frontend website is hosted in Amazon S3.

2. User requests are sent through Amazon API Gateway.

3. AWS Lambda processes the requests.

4. Amazon SQS queues incoming messages for processing.

5. Lambda stores guestbook entries in Amazon DynamoDB.

6. Uploaded media is stored in Amazon S3.

7. Stored entries can be retrieved and displayed back to the user.

## AWS Services Used

- Amazon S3

- Amazon API Gateway

- AWS Lambda

- Amazon SQS

- Amazon DynamoDB

## Development Tools

- Visual Studio Code

- Python

- Amazon Q

## What I Learned

This project allowed me to get hands-on experience with building a serverless application and connecting multiple different AWS services together. I learned how to process requests, queue messages, store data, host application content, and connect frontend and backend cloud services.
