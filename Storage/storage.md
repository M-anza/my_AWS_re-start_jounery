# 📦 AWS Journey – Storage

## 1. What is Storage in AWS?

AWS storage services allow you to store, manage, and access data in the cloud.  

## 2. AWS Storage Services

### Amazon S3 (Simple Storage Service)

Amazon S3 is an object storage service that allows you to store and retrieve any amount of data, such as images, backups, and log files. It offers scalability and durability. S3 is commonly used for data backup, website hosting, and big data storage. Its pricing model is based on the amount of data stored and transferred, allowing users to pay only for what they use. 

### Amazon EBS (Elastic Block Store)

Amazon EBS provides block-level storage that attaches directly to Amazon EC2 instances. It functions like a traditional hard drive in the cloud and retains data even after an EC2 instance is stopped or restarted. EBS is well-suited for use cases such as database storage, operating systems, and transactional workloads where consistent performance and persistence are required.

### Amazon EFS (Elastic File System)

Amazon EFS is a fully managed, scalable file storage service that can be shared across multiple EC2 instances. It automatically scales up or down as files are added or removed and supports the Network File System (NFS) protocol. This makes it an ideal solution for shared storage in applications like content management systems and web server clusters. 

### Amazon S3 Glacier

Amazon S3 Glacier is a low-cost archival storage service designed for data that is rarely accessed but must be retained for long periods. Although data retrieval can take longer compared to S3 Standard, it provides a highly economical solution for compliance archives, backups, and long-term data prevention.

## 3. Key Concepts

- **Durability vs. Availability**  
  - S3: 11 nines durability, high availability.  
  - EBS: Durable, but tied to an Avalabity Zone.  
  - EFS: Highly available across multiple Avalabity Zones.  

- **Storage Classes (S3)**  
  - Standard  
  - Intelligent-Tiering  
  - Standard-IA (Infrequent Access)  
  - Glacier & Glacier Deep Archive  

## 💭 Reflection

When we store data in AWS, we are essentially handing it over to one of the most secure and durable infrastructures in the world. AWS storage services don’t just store data they keep it highly available, secure, and resilient, ensuring that even if hardware fails, our data remains intact and accessible.  