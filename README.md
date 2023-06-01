# Building Event-Driven Architectures on AWS: Six Patterns to Know

Resources for my talk introducing event-driven architectures on AWS and 6 common EDA patterns.

## Why build event-driven?
- Greater developer agility and extensibility - Hear from [Taco Bell](https://youtu.be/U5GZNt0iMZY?t=2139)
- Increased scalability and fault tolerance - Hear from [Lego.com](https://www.youtube.com/watch?v=20KBtJOxUpw)
- Lower total cost of ownership - Hear from [Cinch](https://www.youtube.com/watch?v=wM-dTroS0FA)

## Common AWS services for event-driven architectures:
- Amazon EventBridge
- Amazon SQS
- Amazon SNS
- AWS Step Functions
- AWS Lambda
- Amazon Kinesis Data Streams

With purpose-built serverless services, your application is likely to use **a combination of multiple services** together in an architecture pattern.

## Six EDA patterns to know
### Producing events:
1. User input event - Pattern: [API Gateway to Lambda to EventBridge](https://serverlessland.com/patterns/apigw-lambda-eventbridge-sam-java)
2. SaaS application event - Example: [Salesforce to EventBridge](https://s12d.com/salesforce-eventbridge)
3. Event stream - Pattern: [Kinesis to Lambda](https://serverlessland.com/patterns/kinesis-lambda)
### Consuming events:
4. Buffering events - Pattern: [Trigger ECS task from SQS using EventBridge](https://serverlessland.com/patterns/eventbridge-sqs-ecs-cdk)
5. Workflows - Pattern: [EventBridge to Step Functions](https://serverlessland.com/patterns/eventbridge-sfn)
6. User notifications - Pattern: [Lambda to SNS](https://serverlessland.com/patterns/lambda-sns-sms)

## Bringing it all together: Insurance claims processing application
- [GitHub repo](https://github.com/aws-samples/serverless-eda-insurance-claims-processing)
- [Serverless office hours: Architecture walkthrough](https://www.youtube.com/watch?v=tkLEaaUmC30)
- Building a modern, event-driven application for insurance claims processing - [Part 1](https://aws.amazon.com/blogs/industries/building-a-modern-event-driven-application-for-insurance-claims-processing-part-1/), [Part 2](https://aws.amazon.com/blogs/industries/building-a-modern-event-driven-application-for-insurance-claims-processing-part-2/), [Part 3](https://aws.amazon.com/blogs/compute/extending-a-serverless-event-driven-architecture-to-existing-container-workloads/)

## Learn more:
- [Serverless Land: Event-driven architecture guide](https://serverlessland.com/event-driven-architecture)
- [AWS Skill Builder: Serverless course](https://s12d.com/serverless-badge)