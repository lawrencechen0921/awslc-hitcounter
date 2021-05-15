# Welcome to your CDK Workshop project!

In this chapter we will define a new construct called HitCounter. This construct can be attached to any Lambda function that’s used as an API Gateway backend, and it will count how many requests were issued to each URL path. It will store this in a DynamoDB table.

<img width="748" alt="Screen Shot 2021-05-15 at 10 21 40 PM" src="https://user-images.githubusercontent.com/50194219/118364654-edf24c00-b5cb-11eb-9b2d-4bcf15971634.png">

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
