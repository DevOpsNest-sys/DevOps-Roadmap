# DevOps Roadmap.

This is a step-by-step guide on becoming a DevOps engineer, with links to relevant learning resources.

If you want to learn more about DevOps, subscribe to **https://www.youtube.com/@DevOpsNest**. 

## Disclaimer

> The purpose of this roadmap is to give you an idea of the landscape. The road map will guide you if you are confused about what to learn next, rather than encouraging you to pick what is hype and trendy. You should grow some understanding of why one tool would be better suited for some cases than the other, and remember that hype and trendy do not always mean best suited for the job.

## Table of Contents

- [Learning resources for DevOps Engineers (mostly free)](#learning-resources-for-devops-engineers-mostly-free)
  - [1. GIT](#1-git)
  - [2. Learn one programming language](#2-learn-one-programming-language)
  - [3. Learn Linux & Scripting](#3-learn-linux--scripting)
  - [4. Learn Networking & Security](#4-learn-networking--security)
  - [5. Learn Server Management](#5-learn-server-management)
  - [6. Learn Containers](#6-learn-containers)
  - [7. Learn Container Orchestration](#7-learn-container-orchestration)
  - [8. Learn Infrastructure as a code (X as Code)](#8-learn-infrastructure-as-a-code-x-as-code)
  - [9. Learn CI/CD](#9-learn-cicd)
  - [10. Learn Monitoring & Observability](#10-learn-monitoring--observability)
  - [11. Learn one Cloud provider](#11-learn-one-cloud-provider)
  - [12. Learn Software Engineering Practices](#12-learn-software-engineering-practices)
  - [Bonus: Learn DevSecOps Fundamentals](#bonus-learn-devsecops-fundamentals)
- [Additional resources](#additional-resources)
  - [Tools](#tools)
  - [Books](#books)

## Learning resources for DevOps Engineers (mostly free)

### 1. GIT

All your resources (files) will be held in a GIT repository. Those files are **application code** but also **infrastructure as a code**. 

**Git** is a free tool used for source code management. Git is used to track changes in the source code, enabling multiple developers to work together on non-linear development. 

The two most popular Git platforms are **GitLab** and **GitHub**.

Here you need to learn Git commands, like git clone, branch, merge, and how to collaborate on a project with pull requests.

**Resources:**

- [Pro Git Book](https://git-scm.com/book/en/v2) <sup>FREE</sup>

### 2. Learn one programming language

As an engineer, it is recommended to know at least one programming language that you can use to write **automation scripts**.

Some popular programming languages for DevOps are **Python, Go, and JavaScript**.

Python is a multi-paradigm language. Being an interpreted language, code is executed as soon as it is written, and the syntax allows for writing code in different ways. **Python** is frequently recommended as the first language new coders should learn, because of its focus on readability, consistency, and ease of use. 

Here, you need to learn basic concepts of programming languages, such as syntax, if/else, loops, data structures, etc.

**Resources:**

- Python:
  - [Automate the Boring Stuff with Python book](https://automatetheboringstuff.com/) <sup>FREE</sup>
  - [Python Crash Course](https://ehmatthes.github.io/pcc/) <sup>FREE</sup>
- Shell Script:
  - [The Modern JavaScript Tutorial](https://javascript.info/) <sup>FREE</sup>
  - [JavaScript Crash Course For Beginners](https://www.youtube.com/watch?v=hdI2bqOjy3c) <sup>FREE</sup>
  - [Eloquent JavaScript, 3rd edition](https://eloquentjavascript.net/), Marjin Haverbeke <sup>FREE book</sup>

### 3. Learn Linux & Scripting

An Operating system serves as a bridge between a computer's user and its hardware. Its function is to offer a setting in which a user can conveniently and effectively run programs. 

As most servers use **Linux OS**, you need to make yourself comfortable with Linux and its CLI. 

Lear basic commands, such as: ls, cd, mkdir, rm, cp, mv, touch, cat, printenv, grep, find, chmod, chmod, ps, kill, top, df, du, tar, gzip, ssh, scp, wget, curl, etc.

One easy-to-start distribution is **Ubuntu**. 

In addition, you need to know **scripting** to automate tasks for development and operations. 

Here you can learn OS-specific languages, such as **Bash or Powershell**, or independent, like Python or Go.

**Resources:**

- [Operating System - Overview](https://www.tutorialspoint.com/operating_system/os_overview.htm) <sup>FREE</sup>

### 4. Learn Networking & Security

A **network protocol** is an established set of rules that determine how data is transmitted between different devices in the same network. Essentially, it allows connected devices to communicate with each other, regardless of any differences in their internal processes, structure, or design. 

Here you will need to know how a network works, how to configure **firewalls**, understand how **DNS** works, the **OSI model**, IP addresses, ports, etc.

**Resources:**

- [OSI Model Explained](https://www.cloudflare.com/en-gb/learning/ddos/glossary/open-systems-interconnection-model-osi/) <sup>FREE</sup>

### 5. Learn Server Management

Server management includes all the infrastructure monitoring and maintenance required for servers to operate reliably and at optimal performance levels. The primary goals of an **effective server management strategy** are to:

- Minimize server slowdowns and downtime while maximizing reliability.
- Build secure server environments.
- Scale servers and related operations to meet the needs of the organization over time.

Here you will need to know what **forward and reverse proxies**, **caching servers**, and how to operate **Web Servers**, such as Nginx, Apache, or IIS.

**Resources:**

- [What is a reverse proxy?](https://www.cloudflare.com/en-gb/learning/cdn/glossary/reverse-proxy/) <sup>FREE</sup>

### 6. Learn Containers

A **container** is a standard unit of software that packages up code and all its dependencies, so the application runs quickly and reliably from one computing environment to another. 

**Docker** is by far the most popular container technology today. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries, and settings. 

Here you need to know how to run containers, Docker Networking, Volumes, Dockerfiles, and run multiple containers with Docker-Compose.

Docker Compose is important as a prerequisite for Kubernetes. It is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.

**Resources:**

- [What are Containers?](https://cloud.google.com/learn/what-are-containers) <sup>FREE</sup>

### 7. Learn Container Orchestration

Container orchestration **automates** the deployment, management, scaling, and networking of containers. 

Container orchestration can be used in any environment where you use containers. It can help you to deploy the same application across different environments without needing to redesign it. And microservices in containers make it easier to orchestrate services, including storage, networking, and security. 

Here you need to learn how **Kubernetes** works, and how to administer the Kubernetes cluster and deploy applications on it.

You need to know basic components of Kubernetes, such as: Master Node, Worker Node, Pod, ReplicaSet, Deployment, Service, Ingress, ConfigMap, Secret, PersistentVolume, PersistentVolumeClaim, StatefulSet, DaemonSet, Job, and CronJob.

Also, you need to know how to work with kubectl and Helm tools.

**Resources:**

- [Kubernetes Crash Course for Absolute Beginners by TechWorld with Nana](https://www.youtube.com/watch?v=s_o8dwzRlu4) <sup>FREE</sup>

### 8. Learn Infrastructure as a code (X as Code)

Sometimes referred to as **IaC**, it refers to the techniques and tools used to define infrastructure, typically in a markup language like YAML or JSON. Infrastructure as code allows Engineers to automate environment setup and teardown. Accelerates and de-risks deployment by provisioning gold copy environments on demand.

**Terraform** is the most popular infrastructure provisioning tool, but there are others such as Ansible, Chef, Puppet, and Vagrant.

Here, you need to know how to do **infrastructure provisioning** and **configuration management**.

**Resources:**

- [GUIs, CLI, APIs: Learn Basic Terms of Infrastructure-as-Code](https://thenewstack.io/guis-cli-apis-learn-basic-terms-of-infrastructure-as-code/) <sup>FREE</sup>
- Terraform:
    - [Official Terraform Tutorials](https://learn.hashicorp.com/terraform) <sup>FREE</sup>
- Ansible:
    - [Getting Started With Ansible](https://docs.ansible.com/ansible/latest/getting_started/) <sup>FREE</sup>

### 9. Learn CI/CD

Continuous Integration / Continuous Deployment (CI/CD) is a method to frequently deliver apps to customers by introducing **automation** into the stages of app development. CI/CD is a solution to the problems that integrating new code can cause for development and operations teams.

CI/CD introduces continuous automation and **continuous** monitoring throughout the lifecycle of apps, from integration and testing phases to delivery and deployment. These connected practices are often referred to as a "**CI/CD pipeline**" and are supported by development and operations teams.

There are **different stages** of a CI/CD pipeline, such as: **build, test and deploy**, but there could be much more activities included:

- Checking code from version control and building it
- Having staged gates for different kinds of approvals
- Managing environment variables
- Restarting services
- Executing tests
- And more...

Here you need to learn how to set up CI/CD server, integrate code and trigger pipelines automatically, store and read secrets, and build and package management tools.

Some **popular CI/CD tools** are: Jenkins, TeamCity, CircleCI, Bamboo, GitLab, and Azure DevOps.

**Resources:**

- Jenkins:
    - [Jenkins, From Zero To Hero: Become a DevOps Jenkins Master](https://www.udemy.com/course/jenkins-from-zero-to-hero) <sup>Udemy course</sup>
- GitHub Actions:
    - [Learn GitHub actions](https://learn.microsoft.com/en-us/users/githubtraining/collections/n5p4a5z7keznp5) <sup>FREE</sup>
    - [GitHub Actions Tutorial by Tech World with Nana](https://www.youtube.com/watch?v=R8_veQiYBjI) <sup>FREE</sup>
    - [Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions) <sup>FREE</sup>

### 10. Learn Monitoring & Observability

Monitoring entails overseeing the entire development process from planning, development, integration and testing, deployment, and operations. It involves a complete and **real-time view** of the status of applications, services, and infrastructure in the production environment.

This is especially important when our software is in **production**, and we need to track all kinds of issues in our infrastructure and application.

The two most popular tools are **Prometheus** and **Grafana**, but also Cloud-based tools such as AWS CloudWatch, Azure Monitor, and Google Cloud Monitoring.

Here, you need to know how to set up monitoring and visualize data, create and set up alerting, and create automation during alerting.

**Resources:**

- [What Is Observability? Comprehensive Beginners Guide](https://devopscube.com/what-is-observability/) <sup>FREE</sup>    

### 11. Learn one Cloud provider

Cloud providers provide a layer of APIs to abstract infrastructure and provision it based on security and billing boundaries. The cloud runs on servers in data centers, but the abstractions cleverly give the appearance of interacting with a single "platform" or large application. The ability to quickly provision, configure and secure resources with cloud providers has been key to both the tremendous success, and complexity, of modern DevOps.

The most popular cloud providers in the market are **AWS** and **Azure**, as well as **Google Cloud**.

Here, you need to know how to manage users and administration, networks, virtual servers, etc.

**Resources:**

- [Serverless 101 - Serverless Land](https://serverlessland.com/learn/serverless-101) <sup>FREE</sup>
- Azure:
    - [Exam AZ-900: Microsoft Azure Fundamentals](https://learn.microsoft.com/en-us/certifications/exams/az-900) <sup>FREE</sup>
    - [Microsoft Azure Fundamentals Certification Course (AZ-900)](https://www.youtube.com/watch?v=NKEFWyqJ5XA) <sup>FREE</sup>
    - [AZ-900 | Microsoft Azure Fundamentals Full Course, Free Practice Tests, Website and Study Guides](https://www.youtube.com/watch?v=NPEsD6n9A_I&list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM) <sup>FREE</sup>
- AWS:
    - [Ultimate AWS Certified Cloud Practitioner - 2022](https://www.udemy.com/course/aws-certified-cloud-practitioner-new) <sup>Udemy</sup>
    - [AWS Developer by A Cloud Guru](https://acloudguru.com/learning-paths/aws-developer) <sup>Learning path</sup>
    - [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/) <sup>FREE</sup>

### 12. Learn Software Engineering Practices

As a DevOps engineer, you will probably work in a team with other developers in an Agile world, such as **Scrum**. So, it is very important to know different parts of **SDLC**, as well as the tools which are used there.

In addition, it would be good to know how **automation testing** is working, as you will need to set it up in a CI/CD way.

Here you need to know what **Scrum**, all phases of **SDLC**, how **automation testing** works, etc.

**Resources:**

- [What is Scrum?](https://www.atlassian.com/agile/scrum) <sup>FREE</sup>
- [Ways To Learn About Scrum](https://www.scrum.org/resources/ways-learn-about-scrum) <sup>FREE</sup>
- [Software Development Life Cycle (SDLC) Phases & Models](https://www.guru99.com/software-development-life-cycle-tutorial.html) <sup>FREE</sup>
- [The Beginner's Guide to Agile in Jira: Course description](https://university.atlassian.com/student/page/1117976-the-beginner-s-guide-to-agile-in-jira-course-description?sid_i=8) <sup>FREE</sup>
- [Learn SAFe](https://www.scaledagileframework.com/) <sup>FREE</sup>
- [Learn Automation Testing](https://blog.testproject.io/2020/03/26/automation-testing-for-beginners-ultimate-guide/) <sup>FREE</sup>
- [GitLab - Beginner's Guide to DevOps](https://page.gitlab.com/resources-ebook-beginners-guide-devops.html) <sup>FREE</sup>
- [Common SDLC Models](https://www.scaler.com/blog/software-development-life-cycle/#common-sdlc-models) <sup>FREE</sup>

### Bonus: Learn DevSecOps Fundamentals

Security must be integrated throughout the DevOps lifecycle rather than added as an afterthought.

Here, you will need to learn how to integrate security into the DevOps pipeline and how to automate security testing (SAST and DAST).

Also, you need to know how to manage secrets and credentials and how to set up security policies.

**Resources:**

- [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/) <sup>FREE</sup>
- [Supply Chain Levels for Software Artifacts (SLSA)](https://slsa.dev/) <sup>FREE</sup>
- [HashiCorp Vault Documentation](https://developer.hashicorp.com/vault/docs) <sup>FREE</sup>
- [Trivy Documentation](https://trivy.dev/latest/) <sup>FREE</sup>
- [Falco Runtime Security](https://falco.org/docs/) <sup>FREE</sup>
- [DevSecOps: A leader's guide](https://www.devsecops.org/) <sup>FREE</sup>
- [Container Security](https://www.oreilly.com/library/view/container-security/9781492056690/) book


## Additional resources

### Tools

- **Work Tracking**:** [Asana](https://asana.com/), [Monday](https://monday.com/), [Jira](https://www.atlassian.com/software/jira), [Trello](https://trello.com/), [Azure Boards](https://azure.microsoft.com/en-au/products/devops/boards/).
- **Source code control**: [Git](https://git-scm.com/), [Github](https://github.com/), [GitLab](https://about.gitlab.com/), [BitBucket](https://bitbucket.org/), [Azure DevOps](https://azure.microsoft.com/en-us/products/devops).
- **CI/CD**: [Jenkins](https://www.jenkins.io/), [Team City](https://www.jetbrains.com/teamcity/), [Github Actions](https://github.com/features/actions), [Travis CI](https://www.travis-ci.com/), [Bamboo](https://www.atlassian.com/software/bamboo), [Circle CI](https://circleci.com/), [Azure Pipelines](https://azure.microsoft.com/en-us/products/devops/pipelines/), [Octopus Deploy](https://octopus.com/), [Harness](https://www.harness.io/), [CloudBees CodeShip](https://www.cloudbees.com/products/codeship).
- **Source Code Analysis**: [SonarQube](https://www.sonarsource.com/products/sonarqube/), [Veracode](https://www.veracode.com/).
- **Artifact management**: [Artifactory](https://jfrog.com/artifactory/), [Docker Container Register](https://docs.docker.com/registry/), [npm](https://www.npmjs.com/), [Yarn](https://yarnpkg.com/), [NuGet](https://www.nuget.org/).
- **Configuration Management**: [Terraform](https://www.terraform.io/), [Ansible](https://www.ansible.com/), [Puppet](https://www.puppet.com/), [Chef](https://www.chef.io/).
- **Container orchestration**: [Docker](https://www.docker.com/), [Kubernetes](https://kubernetes.io/), [Red Hat OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift).
- **Monitoring**: [Prometheus](https://prometheus.io/), [Grafana](https://grafana.com/), [Splunk](https://www.splunk.com/), [Dynatrace](https://www.dynatrace.com/), [Kibana](https://www.elastic.co/kibana/).

![DevOps roadmap](devops%20tools.png)

### Books

- **[The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations](https://amzn.to/3IJPv0h)**, Gene Kim, Patrick Debois, John Willis, Jez Humble 

    The book introduces product development, quality assurance, IT operations, and information security. It is a great read for those who are new to DevOps or who want to learn more about how the various components of DevOps work together.

- **[Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://amzn.to/3XRShoA)**, Nicole Forsgren, Jez Humble, Gene Kim 

    This book presents both the findings and the science behind measuring software delivery performance. For promoting DevOps to senior management, it's a fantastic tool.

- **[Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation ](https://amzn.to/3XRShoA)**, Jez Humble, David Farley 

    It introduces automated architecture management and data migration. Many of the deployment pipeline concepts that have since become standard were established in this book. Config as Code, build and deployment automation, and efficient testing techniques are covered in some technical detail. Its mostly technical book.

- **[Team Topologies: Organizing Business and Technology Teams for Fast Flow](https://amzn.to/3Zb83fl)**, Matthew Skelton, Manuel Pais

    The book talks about how to organize teams in a way that enables fast flow of value to customers. It provides a set of four fundamental team topologies: Stream-Aligned Teams, Enabling Teams, Complicated-Subsystem Teams, and Platform Teams, which can be combined and adapted to suit different organizational contexts. 

- **[Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale](https://amzn.to/3Za5aLH)**, Jennifer Davis, Ryn Daniels

    The book provides effective ways to improve team coordination. It shows how to break down information silos, monitor relationships, and repair misunderstandings that arise between and within teams in your organization.

- **[The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://amzn.to/3Z6VSQG)**, Gene Kim, Kevin Behr, George Spafford

    It is a classic novel about effectiveness and communication. IT work is like manufacturing plant work, and a system must be established to streamline the workflow. One of the best books out there.

- **[Site Reliability Engineering](https://sre.google/books/)**, Betsy Beyer, Chris Jones, Jennifer Petoff, Niall Richard Murphy 

    This book explains the whole life cycle of Google’s development, deployment, and monitoring, and how to manage the world’s biggest software systems (also known as SRE). Anyone who considers themselves to be more on the "Ops" end of the DevOps side or who wants to know how to strengthen the bonds between various Dev and Ops teams should read SRE.
