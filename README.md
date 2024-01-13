# Cloud-solution-for-a-transportation-application
This project outlines the architecture and implementation details for a transportation application that supports connections from both mobile devices and web browsers. The solution comprises a Client Application and a Driver Application that communicate with each other. 

## Services that we used to deliver a scalable, highly available solution 
Amazon Cognito: Used for authentication and authorization. It provides a comprehensive set of tools and services to handle user registration, sign-in, and access control, ensuring secure user management.
Multiple Availability Zones and Load Balancing: Implemented to achieve high availability. By deploying resources across multiple availability zones and using load balancers, the system can distribute traffic evenly and handle failures in one availability zone without impacting overall availability.
Auto Scaling Groups: Used for achieving scalability. Auto Scaling groups automatically adjust the number of instances based on demand, allowing the system to scale up during peak periods and scale down during periods of low demand, ensuring optimal resource utilization.
AWS Lambda: Leveraged for serverless computing. AWS Lambda enables the execution of code without the need to provision or manage servers. It allows for efficient scaling, cost optimization, and event-driven processing.
Amazon RDS: Used for database scalability. Amazon RDS (Relational Database Service) provides managed database solutions, allowing for easy scalability of database resources to accommodate growing data and traffic demands.
AWS Shield: Employed in traffic security. AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications against common and sophisticated DDoS attacks, ensuring the availability and stability of applications.
AWS WAF: Used for filtering traffic. AWS WAF (Web Application Firewall) is a web application firewall that filters and protects web applications from common web exploits and attacks, enhancing security and mitigating potential threats.
Amazon CloudFront: Implemented for content delivery. Amazon CloudFront is a fast and highly scalable content delivery network (CDN) that caches and delivers content to end-users with low latency and high data transfer speeds.
AWS Identity and Access Management (IAM): Utilized for access control. IAM enables the management of user access and permissions to AWS services and resources, allowing for fine-grained control and secure delegation of access.
Amazon API Gateway: Used for API management. API Gateway acts as a front door for APIs, providing capabilities such as request authentication, rate limiting, and request/response transformations, ensuring secure and controlled access to APIs.
Amazon Simple Queue Service (SQS): Utilized for message queuing. SQS provides a scalable and reliable message queuing service, allowing for the decoupling of components and asynchronous communication between different parts of the system.
Amazon SNS: Used for push notifications. Amazon SNS (Simple Notification Service) enables the sending of push notifications to mobile devices, allowing for real-time communication and notifications to users.
S3 bucket with objects: Amazon S3 is used to store objects, such as images, documents, or media files, improving data durability.
Cache Redis: Used for quick retrieval of data without the need for time-consuming operations like querying a database

# Project Architecture 
![AWS (2019) horizontal framework](https://github.com/HussamAlbadri/Cloud-solution-for-a-transportation-application/assets/59113969/86284bfe-2dcf-4e89-8f0b-206fd2da1fa1)


