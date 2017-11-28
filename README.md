# AWS Polly Example Using Node.js, SSML and S3
Example Noda.js script thats uses AWS Polly to convert a string to audo and saves the result to an S3 bucket for play back later.

## Requirements
Requires [AWS SDK for JavaScript](http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/welcome.html).

## Basic Configuration
You will need to modify the awscreds.json file to include your AWS security credentials.  The IAM user must have access to Polly.

The following lines will need modification.

```
{
 "accessKeyId": "Your Access Key",
 "secretAccessKey": "Your Secret Key"
}
```
You will also need to modify the main js file adding your chosen bucket and file names.

```
Bucket: "<Your Bucket>", 
Key: "<Your File Name>",
```

## Running the example
From the command line run the following:

```
node aws-polly-example.js   
```