#  AWS Security

## 1. What is AWS Security?

AWS Security refers to the tools, features, and best practices that help you protect your cloud resources, data, and infrastructure. It operates under the Shared Responsibility Model, where AWS manages security of the cloud, and customers manage security in the cloud.


## 2. Core AWS Security Services

 **AWS Identity and Access Management (IAM)**

 IAM centrally manage users, groups, roles, and permissions.Apply the Principle of Least Privilege.Supports Multi-Factor Authentication for extra security.IAM policies define what actions a user or service can perform.

**AWS Organizations**

Manage multiple AWS accounts under a single structure.Apply Service Control Policies (SCPs) for account-level restrictions.Centralize billing and security management.Method used to pay for multiple accounts under aws organisation is called consoladated biling.

 **AWS Cognito**

Provides authentication and user sign-in for web and mobile apps.Supports social logins and enterprise identity providers.

**AWS GuardDuty**

Aws guardduty is a threat detection service that monitors for malicious activity.Uses machine learning and threat intelligence to alert on potential risks.

**AWS Security Hub**

AWS Security Hub centralized dashboard that aggregates security findings from GuardDuty, Inspector, and other tools.Helps maintain compliance with standards such as CIS AWS Foundations Benchmark.

**AWS CloudTrail**

AWS CloudTrail records API calls and user activities across your AWS account.Enables auditing, monitoring, and incident investigation.

 **AWS Config**

AWS Config tracks changes to your AWS resources and configurations.Helps ensure compliance and detect misconfigurations.

**AWS Key Management Service (KMS)**

KMS manages encryption keys used to protect your data.
Integrated with many AWS services (S3, EBS, RDS).

## 3. Shared Responsibility Model


| **Security Area**        | **AWS Responsibility**                                   | **Customer Responsibility**                              |
|---------------------------|----------------------------------------------------------|----------------------------------------------------------|
| Physical Security    | Secures global infrastructure and data centers.          | Not responsible.                     |
| Infrastructure       | Manages servers, networking, and virtualization layer.   | Secures workloads, operating systems, and applications.  |
| Access Management     | Provides IAM tools and features.                         | Implements and enforces proper access controls.          |
| Data Security       | Offers encryption tools (KMS, S3 encryption).            | Encrypts, classifies, and manages their data.            |
| Network Configuration | Provides secure networking capabilities (VPC, firewalls).| Configures and maintains secure network setups.           |
| Application Security  | Secures AWS-managed services.   | Secures customer applications and dependencies.           |


## 4. Best Practices for AWS Security

- Enable MFA for all IAM users and root accounts.
- Follow the Principle of Least Privilege when granting access.
- Use IAM Roles instead of long-term access keys.
- Regularly rotate keys and credentials.
- Encrypt data in transit (SSL/TLS) and at rest (KMS).
- Use AWS Config Rules to monitor compliance.
- Regularly review IAM policies and access logs.

## Reflection

AWS provides strong security tools but it’s up to us to use them wisely. Even though AWS ensures the global infrastructure is secure, our responsibility as customers is to configure our environments correctly, manage identities carefully, and protect our data by granting the right permisions to the right person.

