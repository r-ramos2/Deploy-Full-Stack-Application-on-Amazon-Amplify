# Deploy Full-Stack Application on Amazon Amplify

## Overview
This guide provides steps to deploy a secure, scalable, and full-stack application on Amazon Amplify. By following these steps, you can create a scalable and reliable application that can handle high levels of traffic. The application is built using technologies such as **React**, **GraphQL**, and **AWS Amplify**.

## AWS Amplify Set Up
1. Open AWS Amplify on a separate tab.
2. Click on "Get Started".
3. Under "Host your web app", choose "Deploy without Git provider".
4. Click on "Continue".
5. Under "Manual deploy", enter "App name"="Choose your own", "Environment Name"="dev, prod, etc.".
6. Under "Method", choose "Drag and drop" and upload your files.
7. Click on "Save and deploy" and wait for completion.
8. Click on link under "Domain" to see your app live on AWS.

## Clean Up
Empty and terminate Amplify, CloudFormation Stacks, and S3 Bucket (e.g. you may need to delete bucket policy). To avoid unnecessary costs, please double-check that no underlying resources are still running.

## Conclusion
In this project, we demonstrated how to deploy a full-stack application on Amazon Amplify. By following these steps, we have created a scalable and reliable application that can handle high levels of traffic. Feel free to message me with code improvement suggestions or any questions you may have.

## Acknowledgment
This tutorial is adapted from the [Build a Full-Stack React Application website](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/) provided by Amazon Web Services. We extend our gratitude to AWS for providing this valuable resource, which served as the foundation for the "Deploy Full-Stack Application on Amazon Amplify" tutorial.
