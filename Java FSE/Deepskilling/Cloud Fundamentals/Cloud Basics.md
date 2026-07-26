# ☁️ Cloud Fundamentals

> **Cognizant Digital Nurture 5.0 — Java FSE**
> Basic introduction to **Cloud Computing, Cloud Services, Deployment Models, Virtualization, Scalability, Availability, and major Cloud Platforms**.

---

## 📖 Introduction

**Cloud Computing** is the delivery of computing resources and services over the internet.

Instead of purchasing and maintaining all physical hardware and infrastructure locally, organizations can use computing resources provided by cloud service providers.

Cloud services can include:

* 💻 Computing power
* 💾 Storage
* 🗄️ Databases
* 🌐 Networking
* 📱 Applications
* 🔒 Security services

> 💡 **Simple Definition:**
> Cloud Computing allows users to access computing resources such as servers, storage, databases, and applications over the internet when required.

---

# ☁️ What is Cloud Computing?

In a traditional environment, organizations maintain their own physical servers and infrastructure.

```text
Traditional Infrastructure

Organization
     │
     ▼
Physical Servers
     │
     ▼
Applications
```

With cloud computing, infrastructure and services can be obtained from a cloud provider.

```text
User / Organization
        │
        │ Internet
        ▼
     ☁️ Cloud
        │
   ┌────┼─────┐
   ▼    ▼     ▼
Compute Storage Database
```

Cloud resources can often be created, modified, and removed according to application requirements.

---

# 🎯 Why is Cloud Computing Used?

Cloud computing provides several benefits.

| Benefit                  | Description                                                           |
| :----------------------- | :-------------------------------------------------------------------- |
| 💰 **Cost Efficiency**   | Reduces the need to purchase and maintain all infrastructure          |
| 📈 **Scalability**       | Resources can be increased as requirements grow                       |
| 🔄 **Flexibility**       | Resources can be provisioned according to changing requirements       |
| 🌍 **Accessibility**     | Cloud services can be accessed over networks from different locations |
| ⚡ **Fast Provisioning**  | Computing resources can often be created quickly                      |
| 🛡️ **Reliability**      | Cloud architectures can be designed for high availability             |
| 💾 **Backup & Recovery** | Cloud services can support backup and disaster recovery               |

---

# 🧩 Basic Characteristics of Cloud Computing

Cloud computing commonly includes the following characteristics:

| Characteristic          | Meaning                                            |
| :---------------------- | :------------------------------------------------- |
| ⚡ **On-Demand Service** | Resources can be provisioned when required         |
| 🌐 **Network Access**   | Services are available through network connections |
| 📦 **Resource Pooling** | Provider resources serve multiple customers        |
| 📈 **Rapid Elasticity** | Resources can expand or reduce based on demand     |
| 📊 **Measured Service** | Resource usage can be monitored and measured       |

---

# 🏗️ Cloud Service Models

Cloud computing is commonly divided into three major service models:

```text
Cloud Services
     │
     ├── IaaS
     │
     ├── PaaS
     │
     └── SaaS
```

---

# 🖥️ 1. Infrastructure as a Service (IaaS)

**Infrastructure as a Service (IaaS)** provides basic computing infrastructure through the cloud.

It may provide:

* Virtual machines
* Storage
* Networking
* Computing resources

```text
Cloud Provider
      │
      ▼
Virtual Infrastructure
      │
      ▼
Customer
```

> 💡 **Simple Definition:**
> IaaS provides computing infrastructure without requiring the customer to purchase and maintain the underlying physical hardware.

---

# 🛠️ 2. Platform as a Service (PaaS)

**Platform as a Service (PaaS)** provides an environment where developers can build, test, and deploy applications without managing much of the underlying infrastructure.

```text
Developer
    │
    ▼
Cloud Platform
    │
    ▼
Build Application
    │
    ▼
Deploy Application
```

PaaS allows developers to focus more on application development and less on infrastructure management.

---

# 💻 3. Software as a Service (SaaS)

**Software as a Service (SaaS)** provides ready-to-use software applications over the internet.

Users generally access the application through a browser or client application.

```text
User
 │
 ▼
Internet
 │
 ▼
SaaS Application
```

Examples of SaaS categories include:

* Email services
* Online document applications
* Collaboration software
* Customer management applications

---

# 🆚 IaaS vs PaaS vs SaaS

| Service Model | Provides             | User Mainly Manages                            |
| :------------ | :------------------- | :--------------------------------------------- |
| **IaaS**      | Infrastructure       | Applications and operating environment         |
| **PaaS**      | Application platform | Application and data                           |
| **SaaS**      | Complete software    | Application usage and user-level configuration |

### Easy Way to Remember

```text
IaaS → Infrastructure

PaaS → Platform

SaaS → Software
```

---

# 🌍 Cloud Deployment Models

Cloud environments can also be classified according to how infrastructure is deployed and used.

The major deployment models are:

```text
Cloud Deployment
      │
      ├── Public Cloud
      ├── Private Cloud
      └── Hybrid Cloud
```

---

# 🌐 Public Cloud

A **Public Cloud** is operated by a cloud service provider and provides cloud resources to customers over shared provider infrastructure.

```text
Cloud Provider
      │
      ▼
Public Cloud
  ┌───┼───┐
  ▼   ▼   ▼
User A B   C
```

### Basic Characteristics

* Managed by a cloud provider
* Shared provider infrastructure
* Flexible resource usage
* Suitable for many types of applications

---

# 🔒 Private Cloud

A **Private Cloud** is a cloud environment dedicated to a single organization.

```text
Organization
      │
      ▼
Private Cloud
      │
      ▼
Internal Users
```

It can provide greater control over infrastructure and configuration.

---

# 🔄 Hybrid Cloud

A **Hybrid Cloud** combines private cloud or private infrastructure with public cloud services.

```text
Private Environment
        │
        │
        ↕
        │
   Public Cloud
```

Organizations can use both environments according to their requirements.

---

# 🆚 Cloud Deployment Models

| Model                | Basic Description                                     |
| :------------------- | :---------------------------------------------------- |
| 🌐 **Public Cloud**  | Provider-operated cloud services offered to customers |
| 🔒 **Private Cloud** | Cloud environment dedicated to one organization       |
| 🔄 **Hybrid Cloud**  | Combination of private and public environments        |

---

# 💻 What is Virtualization?

**Virtualization** is a technology that allows multiple virtual computing environments to run using physical hardware.

A physical server can host multiple **Virtual Machines (VMs)**.

```text
Physical Server
      │
      ▼
   Hypervisor
      │
 ┌────┼────┐
 ▼    ▼    ▼
VM 1 VM 2 VM 3
```

Each virtual machine can operate as an independent computing environment.

> 💡 Virtualization is one of the important technologies that supports cloud infrastructure.

---

# 🖥️ What is a Virtual Machine?

A **Virtual Machine (VM)** is a software-based computer that behaves like a physical computer.

A VM can have its own:

* Operating system
* CPU allocation
* Memory allocation
* Storage
* Applications

```text
Physical Hardware
       │
       ▼
    Hypervisor
       │
       ▼
 Virtual Machine
       │
       ▼
Operating System
       │
       ▼
  Application
```

---

# 📈 Scalability

**Scalability** is the ability of a system to handle increased workload by adding resources.

For example:

```text
Low Demand
    │
    ▼
1 Server

Higher Demand
    │
    ▼
More Resources
```

Cloud platforms make it easier to increase resources when application demand grows.

---

# ↕️ Vertical Scaling

**Vertical Scaling** means increasing the capacity of an existing machine.

For example:

```text
Before
4 GB RAM
2 CPU

   ↓

After
8 GB RAM
4 CPU
```

This is sometimes called **scaling up**.

---

# ↔️ Horizontal Scaling

**Horizontal Scaling** means adding more machines or instances.

```text
Before

Server 1

   ↓

After

Server 1
Server 2
Server 3
```

This is sometimes called **scaling out**.

---

# 🔄 Elasticity

**Elasticity** is the ability to increase or decrease cloud resources dynamically according to demand.

```text
Low Traffic
    ↓
Fewer Resources

Traffic Increases
    ↓
More Resources

Traffic Decreases
    ↓
Fewer Resources
```

### Scalability vs Elasticity

| Scalability                           | Elasticity                                      |
| :------------------------------------ | :---------------------------------------------- |
| Ability to handle increasing workload | Ability to adjust resources according to demand |
| Can involve planned growth            | Often associated with dynamic adjustment        |
| Resources are increased as needed     | Resources can increase and decrease             |

---

# 🛡️ Availability

**Availability** refers to the ability of a system or service to remain accessible and operational when users need it.

Cloud applications can improve availability by using multiple resources.

```text
             Application
                  │
          ┌───────┴───────┐
          ▼               ▼
      Server 1         Server 2
```

If one resource becomes unavailable, another resource may continue serving the application when the system is designed for redundancy.

---

# 💾 Cloud Storage

**Cloud Storage** allows data to be stored on cloud infrastructure.

It can be used for:

* Application files
* Documents
* Images and videos
* Backups
* Application data

```text
User / Application
        │
        ▼
     Internet
        │
        ▼
   Cloud Storage
```

Cloud storage can provide scalable and remotely accessible storage capacity.

---

# 🗄️ Cloud Databases

Cloud providers also provide managed database services.

These may support:

* Relational databases
* NoSQL databases
* Distributed databases
* Data backup and recovery

```text
Application
     │
     ▼
Cloud Database
     │
     ▼
    Data
```

Managed database services can reduce the amount of infrastructure management required from application teams.

---

# 🌐 Cloud Networking

Cloud networking connects cloud resources such as:

* Virtual machines
* Applications
* Databases
* Storage
* Other services

```text
Users
  │
  ▼
Network
  │
  ▼
Application
  │
  ▼
Database
```

Networking is essential for communication between cloud services.

---

# 💰 Pay-as-you-go Concept

Many cloud services follow a usage-based pricing approach.

Instead of purchasing large amounts of infrastructure in advance, customers can pay according to the cloud resources or service plans they consume.

```text
Resource Usage
      │
      ▼
Usage Measurement
      │
      ▼
Cloud Billing
```

> 💡 The exact pricing model depends on the cloud provider and service being used.

---

# 🌎 Major Cloud Service Providers

Some widely used cloud platforms include:

| Cloud Platform                   | Provider  |
| :------------------------------- | :-------- |
| ☁️ **Amazon Web Services (AWS)** | Amazon    |
| 🔷 **Microsoft Azure**           | Microsoft |
| 🌐 **Google Cloud**              | Google    |

These platforms provide services for computing, storage, databases, networking, application deployment, monitoring, and many other cloud requirements.

---

# ☁️ Cloud Computing in DevOps

Cloud computing and DevOps are commonly used together.

```text
Developer
    │
    ▼
Source Code
    │
    ▼
Build & Test
    │
    ▼
Deploy
    │
    ▼
Cloud Environment
    │
    ▼
Application
```

Cloud platforms provide infrastructure and services that can support automated application deployment and operation.

---

# 🔄 Cloud and CI/CD

Cloud environments can also be used as deployment targets in CI/CD pipelines.

```text
Code
  ↓
Build
  ↓
Test
  ↓
Deploy
  ↓
Cloud
```

This allows software delivery processes to integrate with cloud infrastructure.

---

# 📚 Important Cloud Terms

| Term                | Meaning                                                  |
| :------------------ | :------------------------------------------------------- |
| **Cloud Computing** | Delivery of computing services over a network            |
| **IaaS**            | Infrastructure as a Service                              |
| **PaaS**            | Platform as a Service                                    |
| **SaaS**            | Software as a Service                                    |
| **Public Cloud**    | Provider-operated cloud environment offered to customers |
| **Private Cloud**   | Cloud environment dedicated to one organization          |
| **Hybrid Cloud**    | Combination of private and public environments           |
| **Virtualization**  | Creation of virtual computing environments               |
| **Virtual Machine** | Software-based computer environment                      |
| **Scalability**     | Ability to handle increased workload                     |
| **Elasticity**      | Ability to adjust resources according to demand          |
| **Availability**    | Ability of a service to remain accessible                |
| **Cloud Storage**   | Storage provided through cloud infrastructure            |

---

# 🧠 Quick Revision

### ☁️ What is Cloud Computing?

> Cloud Computing provides computing resources and services over the internet or another network.

### 🖥️ What is IaaS?

> Infrastructure services such as computing, storage, and networking.

### 🛠️ What is PaaS?

> A cloud platform used to develop and deploy applications.

### 💻 What is SaaS?

> Ready-to-use software delivered as a service.

### 🌐 What is Public Cloud?

> Cloud infrastructure operated by a provider and offered to customers.

### 🔒 What is Private Cloud?

> A cloud environment dedicated to a single organization.

### 🔄 What is Hybrid Cloud?

> A combination of private infrastructure/cloud and public cloud services.

### 💻 What is Virtualization?

> Technology that enables virtual computing environments to run on physical hardware.

### 📈 What is Scalability?

> The ability to increase system capacity to handle additional workload.

### 🔄 What is Elasticity?

> The ability to adjust resources according to changing demand.

---

# 🎯 Key Takeaways

* ✅ Cloud Computing provides computing services over the internet.
* ✅ Cloud resources can be provisioned according to requirements.
* ✅ IaaS provides infrastructure.
* ✅ PaaS provides an application development platform.
* ✅ SaaS provides ready-to-use software.
* ✅ Public, Private, and Hybrid are common cloud deployment models.
* ✅ Virtualization is an important technology behind many cloud environments.
* ✅ Virtual Machines provide software-based computing environments.
* ✅ Scalability helps systems handle increased workload.
* ✅ Elasticity allows resources to adjust according to demand.
* ✅ Cloud storage provides scalable data storage.
* ✅ AWS, Microsoft Azure, and Google Cloud are major cloud platforms.
* ✅ Cloud services are commonly used with DevOps and CI/CD practices.

---

# 🏁 Conclusion

**Cloud Computing** provides access to computing resources such as servers, storage, databases, networking, and applications without requiring organizations to maintain all underlying physical infrastructure themselves.

The basic cloud concepts can be summarized as:

```text
                 ☁️ Cloud Computing
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
      IaaS             PaaS             SaaS
 Infrastructure       Platform          Software

                         │
                         ▼
               Deployment Models
                         │
              ┌──────────┼──────────┐
              ▼          ▼          ▼
            Public     Private     Hybrid
```

Understanding **Cloud Computing, IaaS, PaaS, SaaS, deployment models, virtualization, scalability, elasticity, storage, and availability** provides a basic foundation for learning cloud technologies.

---

> ### ☁️ Cloud Fundamentals — Basic Concepts
>
> **Cognizant Digital Nurture 5.0 — Java FSE**
