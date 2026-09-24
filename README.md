# 🚀 DevOps Learning Journey

This repository contains my **DevOps learning notes, concepts, tools, commands, and hands-on practice**.

My goal is to understand how development and operations work together to build, test, release, deploy, and monitor applications through automation and CI/CD.

---

# 📚 1. What is DevOps?

**DevOps** is a combination of development and operations practices that focuses on:

* Collaboration
* Automation
* Continuous Integration
* Continuous Delivery
* Continuous Deployment
* Monitoring
* Faster and more reliable software delivery
* Continuous improvement

### Simple DevOps Flow

```text
Development
     ↓
    Code
     ↓
   Build
     ↓
   Test
     ↓
  Release
     ↓
  Deploy
     ↓
  Operate
     ↓
  Monitor
     ↓
  Feedback
     ↓
 Continuous Improvement
```

---

# 🔄 2. DevOps Lifecycle

## Plan

Define requirements, tasks, features, and project goals.

## Code

Developers write and manage application source code.

Common tools:

```text
Git
GitHub
```

## Build

Source code is compiled and packaged into an artifact.

Common tools:

```text
Maven
Gradle
```

## Test

Applications are tested for functionality and code quality.

Examples:

```text
JUnit
Selenium
SonarQube
```

## Release

The tested application or artifact is prepared for deployment.

## Deploy

The application is deployed into the required environment.

Examples:

```text
Jenkins
Docker
Kubernetes
AWS
```

## Operate

The deployed application and infrastructure are maintained.

## Monitor

Application and infrastructure performance are monitored.

Examples:

```text
Prometheus
Grafana
CloudWatch
```

---

# 🔁 3. 7 Cs of DevOps

The DevOps lifecycle can be represented through continuous activities:

```text
Continuous Planning
        ↓
Continuous Development / Building
        ↓
Continuous Testing
        ↓
Continuous Integration
        ↓
Continuous Release
        ↓
Continuous Deployment
        ↓
Continuous Monitoring
        ↓
Continuous Feedback
```

These practices help teams continuously improve the software delivery process.

---

# 🧩 4. SDLC & Development Methodologies

## Waterfall

Waterfall follows a sequential development approach.

```text
Requirements
     ↓
Design
     ↓
Development
     ↓
Testing
     ↓
Deployment
     ↓
Maintenance
```

Characteristics:

* Sequential process
* Requirements are generally defined early
* Changes can be more difficult later in the process
* Limited feedback during later stages

---

## Agile

Agile uses an iterative development approach.

```text
Plan
 ↓
Develop
 ↓
Test
 ↓
Feedback
 ↓
Improve
 ↓
Repeat
```

Characteristics:

* Iterative development
* Frequent releases
* Continuous feedback
* Adaptation to changing requirements

---

## DevOps

DevOps combines development and operations practices with automation.

```text
Development
      +
Operations
      +
Automation
      +
CI/CD
      +
Monitoring
```

The goal is to create a continuous software delivery and feedback cycle.

---

# 🛠️ 5. DevOps Tools I Have Learned

| Category                 | Tools                           |
| ------------------------ | ------------------------------- |
| Source Code              | Git, GitHub                     |
| Build                    | Maven, Gradle                   |
| Testing / Code Quality   | SonarQube, Selenium, JUnit      |
| Artifact Management      | Nexus, Amazon S3                |
| CI/CD                    | Jenkins, GitHub Actions         |
| Containers               | Docker                          |
| Orchestration            | Kubernetes, Docker Swarm        |
| AWS Containers           | ECS, EKS                        |
| Configuration Management | Ansible                         |
| Infrastructure as Code   | Terraform                       |
| Monitoring               | Prometheus, Grafana, CloudWatch |

---

# 📂 6. Source Code Management

## Git

Git is a distributed version control system used to track source-code changes.

Important concepts:

```text
Working Directory
       ↓
Staging Area
       ↓
Local Repository
       ↓
Remote Repository
```

Important Git commands:

```bash
git init
git status
git add
git commit
git log
git branch
git merge
git clone
git push
git pull
```

---

## GitHub

GitHub provides remote repository hosting and collaboration features.

I practiced:

* Creating repositories
* Pushing code
* Pulling code
* Branching
* Merging
* Forking
* Pull Requests
* Repository collaboration

---

# 🔨 7. Build Tools

## Maven

Maven is a Java build automation and project management tool.

Typical Maven lifecycle:

```text
Validate
   ↓
Compile
   ↓
Test
   ↓
Package
   ↓
Install
   ↓
Deploy
```

Example:

```bash
mvn clean package
```

This removes the previous build output and creates a fresh artifact.

---

## Gradle

Gradle is another build automation tool commonly used for Java and other application projects.

---

# 🔍 8. Testing & Code Quality

## SonarQube

SonarQube can analyze source code for issues related to:

* Bugs
* Code smells
* Security vulnerabilities
* Duplicate code
* Code quality

Example CI flow:

```text
Source Code
     ↓
Build
     ↓
Test
     ↓
SonarQube Analysis
     ↓
Quality Evaluation
```

---

## JUnit

JUnit is used for automated testing of Java applications.

---

## Selenium

Selenium is commonly used for browser-based application testing and automation.

---

# 📦 9. Artifact Management

After an application is built, the generated package can be stored as an artifact.

Examples:

```text
JAR
WAR
EAR
```

Tools I practiced:

```text
Nexus Repository
Amazon S3
```

Example:

```text
Source Code
     ↓
Maven Build
     ↓
WAR / JAR
     ↓
Nexus / S3
```

---

# ⚙️ 10. Jenkins

Jenkins is an automation server commonly used for CI/CD.

A Jenkins pipeline can automate:

```text
Checkout
    ↓
Build
    ↓
Test
    ↓
Code Analysis
    ↓
Package
    ↓
Artifact
    ↓
Deploy
```

I have practiced Jenkins concepts including:

* Freestyle Jobs
* Pipelines
* Scripted Pipelines
* Jenkins Agents
* Remote Deployment
* GitHub Webhooks
* Build Parameters
* Linked Jobs
* Nexus Integration
* SonarQube Integration
* S3 Artifact Storage

---

# 🐳 11. Docker

Docker is a containerization platform used to package applications and their dependencies into containers.

Basic concept:

```text
Application
     +
Dependencies
     +
Configuration
     ↓
 Docker Image
     ↓
 Docker Container
```

Containers help provide consistent application environments across systems.

---

# ☸️ 12. Kubernetes

Kubernetes is a container orchestration platform.

Important concepts I am learning:

```text
Cluster
  ↓
Node
  ↓
Pod
  ↓
Container
```

Kubernetes can provide capabilities such as:

* Container orchestration
* Scaling
* Service discovery
* Load balancing
* Rolling deployments
* Self-healing

---

# 🐝 13. Docker Swarm

Docker Swarm provides container orchestration capabilities using Docker.

Basic architecture:

```text
Swarm Cluster
      ↓
Manager Node
      ↓
Worker Nodes
      ↓
Containers
```

I explored Docker Swarm as part of understanding container orchestration.

---

# ☁️ 14. AWS Container Services

## Amazon ECS

Amazon Elastic Container Service is an AWS-managed container orchestration service.

## Amazon EKS

Amazon Elastic Kubernetes Service is AWS's managed Kubernetes service.

Basic concept:

```text
Docker Containers
       ↓
AWS Container Platform
       ↓
ECS / EKS
       ↓
AWS Infrastructure
```

---

# 🔧 15. Ansible

Ansible is an IT automation and configuration management tool.

It can be used for:

* Configuration management
* Package installation
* Service management
* User management
* Remote command execution
* Application deployment

Basic architecture:

```text
Ansible Controller
       |
       +------> Server 1
       |
       +------> Server 2
       |
       +------> Server 3
```

Ansible uses modules to perform different tasks on managed systems.

---

# 🏗️ 16. Terraform

Terraform is an Infrastructure as Code tool.

It allows infrastructure to be defined using configuration files.

Basic workflow:

```text
Terraform Configuration
        ↓
   terraform init
        ↓
   terraform plan
        ↓
   terraform apply
        ↓
 Infrastructure
```

Terraform can be used to manage cloud infrastructure such as AWS resources.

---

# 📊 17. Monitoring

Monitoring helps us understand the health and performance of applications and infrastructure.

Tools I am learning:

### Prometheus

Used for collecting and storing monitoring metrics.

### Grafana

Used for visualizing metrics through dashboards.

### AWS CloudWatch

AWS monitoring and observability service used for AWS resources and applications.

Basic monitoring flow:

```text
Application / Infrastructure
          ↓
       Metrics
          ↓
     Prometheus
          ↓
       Grafana
```

---

# ⚡ 18. CI/CD Pipeline

A complete DevOps CI/CD workflow can connect multiple tools together.

```text
Developer
    ↓
GitHub
    ↓
Jenkins / GitHub Actions
    ↓
Maven Build
    ↓
Automated Tests
    ↓
SonarQube
    ↓
Artifact
    ↓
Nexus / S3
    ↓
Docker / EC2 / Kubernetes
    ↓
Deployment
    ↓
Prometheus / Grafana / CloudWatch
    ↓
Monitoring
```

---

# 🔄 19. Complete DevOps Toolchain

The tools I am practicing can be connected together like this:

```text
                  Developer
                      |
                      v
                 Git / GitHub
                      |
                      v
              Jenkins / GitHub Actions
                      |
                      v
                    Maven
                      |
              +-------+-------+
              |               |
              v               v
            Tests          SonarQube
              |               |
              +-------+-------+
                      |
                      v
                   Artifact
                      |
              +-------+-------+
              |               |
              v               v
            Nexus             S3
              |
              v
        Docker / EC2 / K8s
              |
              v
          Application
              |
              v
 Prometheus / Grafana / CloudWatch
```

---

# 📚 20. My Learning Progress

My DevOps learning journey is progressing through different areas:

```text
Git & GitHub
      ↓
Maven
      ↓
Jenkins
      ↓
SonarQube
      ↓
Nexus
      ↓
Ansible
      ↓
Docker
      ↓
Kubernetes
      ↓
AWS
      ↓
Terraform
      ↓
Monitoring
```

I am focusing on **hands-on practice** by creating small projects, testing configurations, troubleshooting errors, and documenting what I learn.

---

# 🎯 Key Takeaways

Through my DevOps learning journey, I am building an understanding of:

* Version control
* Source code management
* Build automation
* Continuous Integration
* Continuous Delivery
* Continuous Deployment
* Code quality
* Artifact management
* Configuration management
* Containerization
* Container orchestration
* Infrastructure as Code
* Cloud infrastructure
* Monitoring and observability

---

# 🚀 DevOps Learning Goal

My goal is to continue moving from individual tools toward understanding how the tools work together in a **complete DevOps CI/CD environment**.

```text
PLAN
 ↓
CODE
 ↓
BUILD
 ↓
TEST
 ↓
ANALYZE
 ↓
PACKAGE
 ↓
STORE
 ↓
DEPLOY
 ↓
OPERATE
 ↓
MONITOR
 ↓
IMPROVE
```

**Learn → Practice → Build → Troubleshoot → Document → Improve 🚀**
