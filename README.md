AWS Dev:AX Learning Material 
https://workshops.devax.academy/monoliths-to-microservices/module8.html

In this lab, we will demonstrate an implementation of the Saga Orchestration pattern for an E-commerce order transaction system, known as AwsomePets. The saga pattern is a sequence of local transactions where each transaction updates data within a single service. Saga orchestration relies on a single orchestrator to coordinate the series of local transactions. The system was implemented using API Gateway, AWS Lambda, Amazon DynamoDB and AWS Step Function as the saga orchestrator.

You will be using SAM (Serverless Application Model) to deploy the services. Click here for more information about SAM. The source code for the Lambda functions will also be included for the deployment.