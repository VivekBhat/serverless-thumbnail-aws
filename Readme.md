# Python S3 Thumbnail
In this project I am using the serverless deployment template to deploy a serverless app.

Working of the app:
1. Upload a file to the S3 bucket
2. This will trigger the Lambda function that will convert the image to a thumbnail
3. Thumbnail will be uploaded to the bucket with a _thumbnail suffix

## Architecture

![architecture](aws-s3-thumbnail-lambda.png)
### Requirements

Please install the following plugin:
https://github.com/UnitedIncome/serverless-python-requirements

```
npm install --save serverless-python-requirements
```
