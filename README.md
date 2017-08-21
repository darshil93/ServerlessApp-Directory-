# ServerlessApp-Directory-

Using AWS Lambda API Gateway, S3 and Dynamo DB

* directoryapp.html pulls data from DyanmoDB using API calls.
* API Gateway provides the ability to call DyanmoDB.
* Response function on website works on AWS Lambda based on the event callback that is present in apiclient.js

# Steps

 * Create Dyanamo DB with Data like userid, username, lastname, firstname
 * Create AWS Lambda Function to Fetch Data in DynamoDB
 * Create REST Calls using API Gateway and attached it to Lambda Function
 * Create a Web Page where you call the function and insert the Javascript and sdk previously downloaded
