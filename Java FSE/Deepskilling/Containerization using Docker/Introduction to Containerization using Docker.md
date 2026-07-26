# 🐳 Containerization Using Docker

> **Cognizant Digital Nurture 5.0 — Java FSE**
> Basic introduction to **Containerization and Docker**.

---

## 📖 Introduction

Modern applications are developed and deployed in different environments such as development, testing, and production.

Sometimes an application works correctly on one system but fails on another because of differences in software versions, dependencies, libraries, or system configurations.

**Containerization** provides a solution by packaging an application together with the components required to run it.

**Docker** is a popular platform used for creating and running containerized applications.

---

## 📦 What is Containerization?

**Containerization** is a method of packaging an application along with its required dependencies, libraries, and configuration into a single isolated environment called a **container**.

```text
Application
     +
Dependencies
     +
Libraries
     │
     ▼
  Container
```

> 💡 **Simple Definition:**
> Containerization allows an application and its dependencies to be packaged together so that the application can run consistently across different environments.

---

## 🐳 What is Docker?

**Docker** is a platform that helps developers build, package, distribute, and run applications inside containers.

Docker makes it easier to run the same application across different environments without repeatedly configuring all of its dependencies.

```text
Application
     │
     ▼
Docker Image
     │
     ▼
Container
     │
     ▼
Running Application
```

---

## 🎯 Why is Docker Used?

Docker is commonly used because it provides:

| Benefit             | Description                                                           |
| :------------------ | :-------------------------------------------------------------------- |
| 📦 **Portability**  | Applications can be moved between Docker-supported environments       |
| 🔄 **Consistency**  | Helps maintain similar environments across development and deployment |
| ⚡ **Lightweight**   | Containers generally require fewer resources than virtual machines    |
| 🚀 **Fast Startup** | Containers can usually start quickly                                  |
| 🔒 **Isolation**    | Applications can run in separate environments                         |
| 📈 **Scalability**  | Multiple container instances can be created when required             |

---

## 💿 What is a Docker Image?

A **Docker Image** is a packaged template containing the application and the components required to run it.

An image may contain:

* Application code
* Runtime
* Libraries
* Dependencies
* Required configuration

```text
Application
     +
Runtime
     +
Dependencies
     │
     ▼
Docker Image
```

> 💡 A Docker image acts as a **template for creating containers**.

---

## 📦 What is a Docker Container?

A **Docker Container** is a running instance of a Docker image.

One Docker image can be used to create multiple containers.

```text
             Docker Image
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
   Container 1 Container 2 Container 3
```

Each container runs as an isolated application environment.

---

## 🆚 Docker Image vs Docker Container

| Docker Image                      | Docker Container                       |
| :-------------------------------- | :------------------------------------- |
| Template for an application       | Running instance of an image           |
| Used to create containers         | Created from an image                  |
| Contains application requirements | Runs the application                   |
| Can be stored and shared          | Exists while being created/run/stopped |

### Easy Way to Remember

```text
Docker Image     → Blueprint
Docker Container → Running Instance
```

---

## 📄 What is a Dockerfile?

A **Dockerfile** is a text file containing instructions that describe how a Docker image should be created.

It can define:

* Base environment
* Application files
* Dependencies
* Required configuration
* Application startup instructions

The basic relationship is:

```text
Dockerfile
    │
    ▼
Docker Image
    │
    ▼
Docker Container
```

> 💡 **Dockerfile creates the instructions, an Image is built from those instructions, and a Container runs from the Image.**

---

## ⚙️ Basic Docker Components

Docker consists of several important components.

| Component               | Description                                    |
| :---------------------- | :--------------------------------------------- |
| 🐳 **Docker Engine**    | Core software used to build and run containers |
| 💿 **Docker Image**     | Template used to create containers             |
| 📦 **Docker Container** | Running instance of an image                   |
| 📄 **Dockerfile**       | Instructions used to create an image           |
| 🗃️ **Docker Registry** | Location used to store and distribute images   |

---

## 🗃️ What is a Docker Registry?

A **Docker Registry** is a service used to store and distribute Docker images.

Developers can store images in a registry and use them on different systems.

```text
Developer
    │
    ▼
Docker Image
    │
    ▼
Docker Registry
    │
    ▼
Other Systems
    │
    ▼
Containers
```

This makes it easier to share and distribute containerized applications.

---

## 🆚 Containers vs Virtual Machines

Both containers and virtual machines provide isolated environments, but they work differently.

| Containers                                     | Virtual Machines                          |
| :--------------------------------------------- | :---------------------------------------- |
| Share the host operating system kernel         | Include a complete guest operating system |
| Generally lightweight                          | Generally heavier                         |
| Usually start quickly                          | Usually take longer to start              |
| Require fewer resources                        | Require more resources                    |
| Suitable for portable application environments | Provide full machine-level virtualization |

### Basic Difference

```text
Virtual Machine
───────────────
Application
Guest OS
Hypervisor
Host OS
Hardware
```

```text
Container
─────────
Application
Container Runtime
Host OS
Hardware
```

---

## 🔄 How Docker Works

The basic Docker concept can be understood as:

```text
Application Code
       │
       ▼
   Dockerfile
       │
       ▼
  Docker Image
       │
       ▼
Docker Container
       │
       ▼
Running Application
```

### Flow

1. The application is developed.
2. A Dockerfile describes its container environment.
3. A Docker image is created.
4. The image is used to create a container.
5. The application runs inside the container.

---

## 🚀 Docker in DevOps

Docker is commonly used in DevOps because it helps provide consistent application environments.

Without containerization:

```text
Development Environment
          ↓
Testing Environment
          ↓
Production Environment

Environment differences may occur.
```

With containerization:

```text
        Docker Image
             │
      ┌──────┼──────┐
      ▼      ▼      ▼
Development Test Production
```

The same application image can be used across different stages of software delivery.

---

## 🔄 Docker and CI/CD

Docker can also be used as part of a CI/CD workflow.

A simple conceptual flow is:

```text
Code
  ↓
Build
  ↓
Test
  ↓
Create Container Image
  ↓
Deploy
```

This helps provide a consistent application package throughout the delivery process.

---

## 📚 Important Terms

| Term                 | Meaning                                        |
| :------------------- | :--------------------------------------------- |
| **Containerization** | Packaging an application with its dependencies |
| **Docker**           | Platform used to create and run containers     |
| **Docker Image**     | Template used to create containers             |
| **Docker Container** | Running instance of an image                   |
| **Dockerfile**       | Instructions for creating a Docker image       |
| **Docker Engine**    | Software that manages Docker containers        |
| **Docker Registry**  | Service used to store and distribute images    |
| **Host System**      | Machine on which Docker runs                   |

---

## 🧠 Quick Revision

### 📦 Containerization

> Packaging an application and its dependencies into an isolated container.

### 🐳 Docker

> A platform used to build and run containerized applications.

### 💿 Docker Image

> A template containing the application and its required components.

### 📦 Docker Container

> A running instance of a Docker image.

### 📄 Dockerfile

> A file containing instructions for creating a Docker image.

### 🗃️ Docker Registry

> A service used to store and distribute Docker images.

---

## 🎯 Key Takeaways

* ✅ Containerization packages applications with their dependencies.
* ✅ Docker is a popular containerization platform.
* ✅ Docker helps provide consistent application environments.
* ✅ A Docker image is a template for creating containers.
* ✅ A Docker container is a running instance of an image.
* ✅ A Dockerfile contains instructions for creating an image.
* ✅ Multiple containers can be created from the same image.
* ✅ Docker registries are used to store and distribute images.
* ✅ Containers are generally more lightweight than virtual machines.
* ✅ Docker is commonly used with DevOps and CI/CD practices.

---

## 🏁 Conclusion

**Containerization** is a technique used to package applications together with their required dependencies so that they can run consistently across different environments.

**Docker** provides a simple and widely used platform for creating and managing these containerized applications.

The basic Docker concept can be summarized as:

```text
Application
     ↓
Dockerfile
     ↓
Docker Image
     ↓
Docker Container
     ↓
Running Application
```

Understanding **containers, images, Dockerfiles, and registries** provides the basic foundation required to understand Docker and containerization.

---

> ### 🎉 Containerization Using Docker — Basic Introduction
>
> **Cognizant Digital Nurture 5.0 — Java FSE**
