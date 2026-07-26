# ☁️ Amazon Web Services (AWS)

> **Cognizant Digital Nurture 5.0 — Java FSE**
> A very basic introduction to **Amazon Web Services (AWS)** and cloud computing.

---

## 📖 Introduction

**Amazon Web Services (AWS)** is a cloud computing platform provided by Amazon.

AWS provides different cloud services that allow individuals and organizations to use computing resources over the internet instead of maintaining all physical infrastructure themselves.

These services include:

* 💻 Computing
* 💾 Storage
* 🗄️ Databases
* 🌐 Networking
* 🔒 Security
* 📊 Monitoring

---

## ☁️ What is AWS?

**AWS stands for Amazon Web Services.**

It provides cloud-based services that can be used to build, deploy, and manage applications.

```text
User / Organization
        │
        ▼
     Internet
        │
        ▼
    ☁️ AWS Cloud
        │
   ┌────┼─────┐
   ▼    ▼     ▼
Compute Storage Database
```

> 💡 **Simple Definition:**
> AWS is a cloud platform that provides computing resources and services over the internet.

---

## 🎯 Why is AWS Used?

| Benefit                      | Description                                              |
| :--------------------------- | :------------------------------------------------------- |
| ☁️ **Cloud Access**          | Access computing resources through the cloud             |
| 💰 **Flexible Pricing**      | Many services use usage-based pricing models             |
| 📈 **Scalability**           | Increase or decrease resources when required             |
| 🌍 **Global Infrastructure** | Deploy applications across multiple geographic regions   |
| ⚡ **Fast Provisioning**      | Create resources without purchasing physical hardware    |
| 🔒 **Security Features**     | Provides tools and services for securing cloud resources |

---

## 🧩 Basic AWS Services

AWS provides a large number of services. Some basic services are:

| AWS Service              | Purpose                        |
| :----------------------- | :----------------------------- |
| 💻 **Amazon EC2**        | Virtual computing servers      |
| 💾 **Amazon S3**         | Object storage                 |
| 🗄️ **Amazon RDS**       | Managed relational databases   |
| 🌐 **Amazon VPC**        | Virtual networking             |
| 👤 **AWS IAM**           | Identity and access management |
| 📊 **Amazon CloudWatch** | Monitoring and observability   |

---

## 💻 Amazon EC2

**Amazon Elastic Compute Cloud (EC2)** provides virtual computing resources in AWS.

An EC2 instance can be thought of as a **virtual server in the cloud**.

```text
AWS Cloud
    │
    ▼
EC2 Instance
    │
    ▼
Application
```

EC2 can be used to run applications and other workloads.

---

## 💾 Amazon S3

**Amazon Simple Storage Service (S3)** is an object storage service.

It can be used to store data such as:

* Images
* Videos
* Documents
* Application files
* Backups

```text
Application
     │
     ▼
Amazon S3
     │
     ▼
Stored Objects
```

---

## 🗄️ Amazon RDS

**Amazon Relational Database Service (RDS)** is a managed service for relational databases.

It supports several database engines and helps reduce the infrastructure management required to operate relational databases.

```text
Application
     │
     ▼
Amazon RDS
     │
     ▼
Database
```

---

## 🌐 Amazon VPC

**Amazon Virtual Private Cloud (VPC)** allows AWS resources to run inside a logically isolated virtual network.

It helps organize and control networking between cloud resources.

```text
AWS Cloud
    │
    ▼
   VPC
    │
 ┌──┴──┐
 ▼     ▼
EC2   Other Resources
```

---

## 👤 AWS IAM

**AWS Identity and Access Management (IAM)** helps control access to AWS resources.

IAM is used to manage:

* Users
* Roles
* Permissions
* Access policies

> 🔐 **Basic Idea:** IAM determines **who can access which AWS resources and what actions they are allowed to perform**.

---

## 📊 Amazon CloudWatch

**Amazon CloudWatch** is a monitoring and observability service.

It can help monitor AWS resources and applications using information such as:

* Metrics
* Logs
* Alarms
* Application and infrastructure activity

---

## 🌍 AWS Regions

AWS infrastructure is available across multiple geographic locations called **Regions**.

```text
AWS
 │
 ├── Region A
 │
 ├── Region B
 │
 └── Region C
```

Organizations can choose a Region based on requirements such as latency, service availability, compliance, and architecture.

---

## 🏢 Availability Zones

AWS Regions contain multiple **Availability Zones (AZs)**.

```text
AWS Region
    │
 ┌──┼──┐
 ▼  ▼  ▼
AZ1 AZ2 AZ3
```

Availability Zones are separate infrastructure locations within a Region and can be used to design highly available applications.

---

## 🔄 Basic AWS Workflow

A very simple AWS application architecture might look like:

```text
        User
          │
          ▼
       Internet
          │
          ▼
     AWS Application
          │
     ┌────┴────┐
     ▼         ▼
    EC2       S3
     │
     ▼
    RDS
```

In this example:

* **EC2** runs the application.
* **S3** stores objects/files.
* **RDS** stores relational application data.

---

## 📚 Important AWS Terms

| Term                  | Meaning                                          |
| :-------------------- | :----------------------------------------------- |
| **AWS**               | Amazon Web Services                              |
| **EC2**               | Virtual computing service                        |
| **S3**                | Object storage service                           |
| **RDS**               | Managed relational database service              |
| **VPC**               | Virtual network in AWS                           |
| **IAM**               | Identity and access management                   |
| **CloudWatch**        | Monitoring and observability service             |
| **Region**            | Geographic AWS infrastructure area               |
| **Availability Zone** | Isolated infrastructure location within a Region |

---

## 🧠 Quick Revision

### ☁️ AWS

> Cloud computing platform provided by Amazon.

### 💻 EC2

> Provides virtual computing servers.

### 💾 S3

> Provides object storage.

### 🗄️ RDS

> Provides managed relational databases.

### 🌐 VPC

> Provides virtual networking.

### 👤 IAM

> Controls identity, permissions, and access.

### 📊 CloudWatch

> Provides monitoring and observability capabilities.

---

## 🎯 Key Takeaways

* ✅ AWS stands for **Amazon Web Services**.
* ✅ AWS is a cloud computing platform.
* ✅ EC2 provides virtual computing resources.
* ✅ S3 provides object storage.
* ✅ RDS provides managed relational databases.
* ✅ VPC provides virtual networking.
* ✅ IAM manages access and permissions.
* ✅ CloudWatch helps monitor applications and AWS resources.
* ✅ AWS infrastructure is organized into Regions and Availability Zones.
* ✅ AWS services can be combined to build and deploy applications.

---

## 🏁 Conclusion

**Amazon Web Services (AWS)** provides cloud services for computing, storage, databases, networking, security, monitoring, and many other requirements.

For beginners, the basic AWS services to remember are:

```text
AWS
 │
 ├── 💻 EC2       → Compute
 ├── 💾 S3        → Storage
 ├── 🗄️ RDS       → Database
 ├── 🌐 VPC       → Networking
 ├── 👤 IAM       → Access Control
 └── 📊 CloudWatch → Monitoring
```

Understanding these basic services provides a foundation for learning AWS and cloud computing.

---

> ### ☁️ Amazon AWS — Basic Concepts
>
> **Cognizant Digital Nurture 5.0 — Java FSE**
