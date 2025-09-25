# 📦 AWS Journey – Storage

Welcome back to my **AWS Learning Journey** 🚀  
This section covers **Storage concepts and services** in AWS.

---

## 1. 🌩️ What is Storage in AWS?
AWS storage services allow you to **store, manage, and access data** in the cloud.  

---

## 2. 🗂️ AWS Storage Services

### 🔹 Amazon S3 (Simple Storage Service)
- Object storage – store any amount of data (images, files, backups, logs).  
- Scalable and durable (11 nines: 99.999999999%).  
- Use cases: Backup, website hosting, big data storage.  
- **Pricing**: Pay for what you store and transfer.  

### 🔹 Amazon EBS (Elastic Block Store)
- Block-level storage – attaches to EC2 instances.  
- Functions like a “hard drive in the cloud.”  
- Persistent (survives EC2 restart).  
- Use cases: Databases, OS storage, transactional workloads.  

### 🔹 Amazon EFS (Elastic File System)
- File storage – shared, fully managed, elastic file system.  
- Scales automatically as files are added/removed.  
- Supports NFS protocol.  
- Use cases: Content management systems, shared storage across multiple EC2s.  

### 🔹 Amazon S3 Glacier
- Archival storage – very low cost, but slower retrieval.  
- Designed for data you rarely access.  
- Use cases: Compliance archives, backups, long-term storage.  

---

## 3. 🔑 Key Concepts
- **Durability vs. Availability**  
  - S3: 11 nines durability, high availability.  
  - EBS: Durable, but tied to an AZ (backups needed).  
  - EFS: Highly available across multiple AZs.  

- **Storage Classes (S3)**  
  - Standard  
  - Intelligent-Tiering  
  - Standard-IA (Infrequent Access)  
  - Glacier & Glacier Deep Archive  

- **Data Lifecycle Policies** – Automatically transition data between storage classes.  
- **Encryption** – Server-side and client-side options available.  

---

## 5. 💭 Reflection

When we store data in AWS, we are essentially handing it over to one of the **most secure and durable infrastructures** in the world.   

- **Reliability & Durability**:  
  - **Amazon S3** is designed for **11 nines durability (99.999999999%)**, meaning the chance of data loss is extremely small.  
  - **EBS volumes** are automatically replicated within an AZ to protect against hardware failure.  
  - **EFS** spreads data across multiple AZs for high availability.  
  - **Glacier** provides long-term retention, with durability on par with S3 but at lower cost.  

- **Control & Access**:  
  - With features like **bucket policies, IAM roles, ACLs, and lifecycle policies**, we decide **who can access** the data and how long it stays in a given storage tier.  

👉 In short, AWS storage services don’t just **store data** – they keep it **highly available, secure, and resilient**, ensuring that even if hardware fails, our data remains intact and accessible.  

---



