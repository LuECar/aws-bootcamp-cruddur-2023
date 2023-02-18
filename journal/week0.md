# Week 0 — Billing and Architecture
/*
This week was focused on improving the security, cost optimization, and architecture of our AWS environment. I took the following actions:

Monday, February 14:

Set up MFA for the root account to enhance security and prevent unauthorized access.
Created an IAM role to allow developers to access only the necessary resources in the AWS environment.
Tuesday, February 15:

Set a billing alarm to get notified when our spending exceeds a certain threshold.
Set up an AWS budget to track our spending and ensure we stay within budget.
Wednesday, February 16:

Configured EventBridge to connect the Health Dashboard to SNS, so that we receive notifications when there is a service health issue. This will help us identify and respond to service issues quickly.
Thursday, February 17:

Reviewed all the questions of each pillar in the Well-Architected Tool without any specialized lens. This helped me to identify areas that needed improvement in our architecture.
Friday, February 18:

Created an architectural diagram of the CI/CD logical pipeline in Lucid Charts to better understand the infrastructure and processes that our developers use to build and deploy applications.
Researched the technical and service limits of specific services, such as Lambda, API Gateway, and S3, to understand how they could impact our technical path and flexibility.
Opened a support ticket to request an increase in the service limit for our EC2 instances, which will allow us to scale our infrastructure more effectively.
Overall, this week was a productive week where I improved the security, cost optimization, and architecture of our AWS environment.
*/