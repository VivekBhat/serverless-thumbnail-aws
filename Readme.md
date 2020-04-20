# Serverless Thumbnail Generator
In this project I am using the serverless deployment template to deploy a serverless app.

### About the app
Once an image is uploaded to the S3 bucket a Thumbnail of the same image will be created and uploaded in the same bucket with a '_thumbnail' suffix

### Working of the app:
1. Upload an image to the S3 bucket (.png extension)
2. This will trigger the Lambda function that will convert the image to a thumbnail
3. Thumbnail will be uploaded to the bucket with a _thumbnail suffix

## Architecture

![architecture](https://github.com/VivekBhat/serverless-thumbnail-aws/blob/master/aws-s3-thumbnail-lambda.png?raw=true)
### Requirements

Please install the following plugin:
https://github.com/UnitedIncome/serverless-python-requirements

```
npm install --save serverless-python-requirements
```

### Useful Links: 
* [AWS Documentation](https://aws.amazon.com/documentation/)
* [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
* [AWS Documentation on Github](https://github.com/awsdocs)
* [AWS Doc SDK Examples](https://github.com/awsdocs/aws-doc-sdk-examples)
