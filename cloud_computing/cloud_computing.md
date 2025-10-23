# Cloud Computing & Compute Services

## 1. What is Compute?

Compute refers to the processing power required to run applications and workloads in the cloud. It is the brains of cloud computing the virtual servers containers, or serverless functions that execute code and handle requests.

## 2. Examples of AWS Compute Services

- EC2 (Elastic Compute Cloud) – Virtual machines in the cloud with full control.

- Lambda – Serverless management, event-driven functions.

- ECS (Elastic Container Service) – Managed container orchestration.

- AWS Batch – Run batch computing jobs at scale.

- Fargate – Serverless compute engine for containers.


## 3. Key Concepts

Scalability and Elasticity are core principles of AWS architecture.
They ensure that your applications can handle varying workloads efficiently without manual intervention. AWS services can automatically adjust resources either vertically (scaling up or down by increasing or decreasing instance size) or horizontally (adding or removing instances). This allows systems to maintain performance during high demand and reduce costs during low demand.

Serverless computing, offered through services like AWS Lambda and AWS Fargate, eliminates the need to provision or manage physical or virtual servers. Instead, AWS automatically handles all infrastructure operations such as scaling, patching, and capacity management, allowing developers to focus solely on writing and deploying code.

High Availability and Reliability are built into the AWS infrastructure through redundancy and failover mechanisms.
Resources are distributed across multiple Availability Zones and Regions, ensuring that even if one component fails, the application remains operational. This design helps organizations achieve consistent uptime and dependable performance across their applications.

## 4. Advantages of Cloud Computing

Cloud computing provides numerous benefits that make it the preferred choice for modern IT solutions:

- Cost Efficiency – Pay only for what you use, reducing upfront hardware costs.

- Scalability – Instantly scale resources up or down to meet changing demand.

- Flexibility – Access a wide range of services, tools, and configurations.

- High Availability – Built-in redundancy ensures minimal downtime.

- Security – AWS offers advanced security, compliance, and encryption features.

- Global Reach – Deploy applications across multiple AWS Regions worldwide.

- Speed & Agility – Quickly deploy new applications and experiment without infrastructure delays.

## Reflection

I noticed that serverless and containers are becoming dominant for modern applications, while EC2 remains a core building block for more traditional or highly customized workloads.