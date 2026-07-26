# 🚀 DevOps — Basic Concepts

> **Cognizant Digital Nurture 5.0 — Java FSE**
> A beginner-friendly introduction to **DevOps, its lifecycle, principles, benefits, and commonly used tools**.

---

## 📖 Overview

**DevOps** is a software development approach that combines **Development (Dev)** and **Operations (Ops)**.

The main purpose of DevOps is to improve collaboration between development and operations teams and make software development, testing, deployment, and maintenance **faster and more reliable**.

```text
Development + Operations = DevOps
```

---

## 🔄 What is DevOps?

Traditionally, development and operations teams may work separately.

* **Development Team** creates the application.
* **Operations Team** deploys and maintains the application.

DevOps encourages these teams to work together throughout the software development lifecycle.

```text
┌─────────────────┐       ┌─────────────────┐
│   Development   │   +   │   Operations    │
└────────┬────────┘       └────────┬────────┘
         │                         │
         └───────────┬─────────────┘
                     ▼
                  DevOps
```

> 💡 **Simple Definition:**
> DevOps is a combination of **people, practices, and tools** that helps organizations develop and deliver software efficiently.

---

## 🎯 Goals of DevOps

| Goal                          | Description                               |
| :---------------------------- | :---------------------------------------- |
| ⚡ **Faster Delivery**         | Develop and release applications faster   |
| 🤝 **Collaboration**          | Improve communication between teams       |
| 🤖 **Automation**             | Reduce repetitive manual tasks            |
| 🧪 **Better Quality**         | Detect problems earlier                   |
| 🚀 **Reliable Deployment**    | Make releases more consistent             |
| 🔄 **Continuous Improvement** | Improve software through regular feedback |

---

## ♾️ DevOps Lifecycle

DevOps follows a continuous lifecycle:

```text
Plan
  ↓
Code
  ↓
Build
  ↓
Test
  ↓
Deploy
  ↓
Operate
  ↓
Monitor
  │
  └────────► Plan Again
```

### Lifecycle Stages

|      Stage     | Description                         |
| :------------: | :---------------------------------- |
|   📝 **Plan**  | Define requirements and tasks       |
|   💻 **Code**  | Develop the application             |
|  🔨 **Build**  | Compile and package the application |
|   🧪 **Test**  | Verify application functionality    |
|  🚀 **Deploy** | Release the application             |
| ⚙️ **Operate** | Run and maintain the application    |
| 📊 **Monitor** | Observe performance and errors      |

---

## 🌿 Role of Git in DevOps

**Git** is widely used in DevOps for source code version control.

Git allows developers to:

* Track code changes
* Maintain project history
* Create branches
* Merge changes
* Collaborate with other developers
* Restore previous versions when required

### Basic Git Workflow

```text
Developer
    │
    ▼
Write Code
    │
    ▼
Git Add
    │
    ▼
Git Commit
    │
    ▼
Git Push
    │
    ▼
Remote Repository
```

---

## 🤖 Automation in DevOps

Automation is an important part of DevOps.

Instead of performing repetitive tasks manually, tools can automate many operations.

### Examples

| Task          | Automation                                |
| :------------ | :---------------------------------------- |
| 🔨 Build      | Automatically compile/package application |
| 🧪 Testing    | Automatically execute tests               |
| 🚀 Deployment | Automatically release application         |
| 📊 Monitoring | Automatically track system health         |
| 🔔 Alerts     | Automatically notify teams about failures |

> 💡 **Key Idea:** Automation helps reduce manual errors and makes processes faster and more consistent.

---

## 🧰 Common DevOps Tools

Different tools can be used during different stages of the DevOps lifecycle.

| Tool                    | Purpose                           |
| :---------------------- | :-------------------------------- |
| 🌿 **Git**              | Version control                   |
| ☁️ **GitHub / GitLab**  | Source code hosting               |
| 🔨 **Maven / Gradle**   | Build automation                  |
| 🔄 **Jenkins**          | Automation and CI/CD              |
| ⚙️ **GitHub Actions**   | GitHub workflow automation        |
| 🐳 **Docker**           | Application containerization      |
| 📊 **Monitoring Tools** | Application and system monitoring |

> **Note:** Different organizations may use different tools depending on their project requirements.

---

## 🔨 Build Automation

Build tools automate the process of preparing an application for execution or deployment.

For Java applications, common build tools include:

* Maven
* Gradle

Example Maven command:

```bash
mvn clean package
```

This command can clean previous build files, compile the application, run configured tests, and package the project.

---

## 🔍 Monitoring in DevOps

After an application is deployed, it needs to be monitored.

Monitoring helps teams identify:

* Application failures
* Performance problems
* High resource usage
* Server availability
* Unexpected errors

```text
Application
     │
     ▼
  Monitoring
     │
     ├── Performance
     ├── Errors
     ├── Availability
     └── System Health
```

---

## 🆚 Traditional Approach vs DevOps

| Traditional Approach      | DevOps Approach             |
| :------------------------ | :-------------------------- |
| Teams may work separately | Teams collaborate           |
| More manual processes     | More automation             |
| Longer release cycles     | Faster release cycles       |
| Testing may happen later  | Testing happens frequently  |
| Feedback can be slower    | Continuous feedback         |
| Deployment may be manual  | Deployment can be automated |

---

## 📚 Important DevOps Terms

| Term           | Meaning                                        |
| :------------- | :--------------------------------------------- |
| **Repository** | Location where source code is stored           |
| **Commit**     | Recorded snapshot of code changes              |
| **Branch**     | Independent line of development                |
| **Build**      | Process of preparing source code for execution |
| **Test**       | Verification of application functionality      |
| **Deploy**     | Release an application to an environment       |
| **Automation** | Performing processes automatically             |
| **Monitoring** | Observing application and system health        |

---

## 🔁 Basic DevOps Workflow

|  Step | Activity                        |
| :---: | :------------------------------ |
| **1** | 📝 Plan the application         |
| **2** | 💻 Write the code               |
| **3** | 🌿 Store code using Git         |
| **4** | 🔨 Build the application        |
| **5** | 🧪 Test the application         |
| **6** | 🚀 Deploy the application       |
| **7** | 📊 Monitor the application      |
| **8** | 🔄 Collect feedback and improve |

---

## 🧠 Quick Revision

### What is DevOps?

> **DevOps = Development + Operations**

DevOps improves collaboration between development and operations teams and helps automate software delivery processes.

### Why is DevOps Used?

DevOps is used to:

* Deliver applications faster
* Improve collaboration
* Automate repetitive tasks
* Detect problems earlier
* Improve software quality and reliability

---

## 🎯 Key Takeaways

* ✅ DevOps combines **Development and Operations**.
* ✅ Collaboration is a major DevOps principle.
* ✅ Automation reduces repetitive manual work.
* ✅ Git is commonly used for version control.
* ✅ Build and testing processes can be automated.
* ✅ Applications can be deployed more efficiently.
* ✅ Monitoring provides continuous feedback.
* ✅ DevOps follows a continuous lifecycle.

---

## 🏁 Conclusion

**DevOps** is an approach that improves collaboration between development and operations teams while promoting automation throughout the software development lifecycle.

The basic DevOps lifecycle can be summarized as:

```text
Plan → Code → Build → Test → Deploy → Monitor → Improve
```

Understanding these concepts provides a foundation for learning DevOps practices and technologies in greater detail.

---

> ### 🎉 DevOps — Basic Concepts Completed
>
> **Cognizant Digital Nurture 5.0 — Java FSE**
