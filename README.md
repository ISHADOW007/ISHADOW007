<div align="center">

# Satyam Govind Rao

**Software Engineer · Java & Spring Boot · Backend Systems, Cloud and DSA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satyamgovindrao/)
[![LeetCode](https://img.shields.io/badge/LeetCode-423_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/satyamgrao007/)
[![Email](https://img.shields.io/badge/Email-satyamgrao007@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:satyamgrao007@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://cp.certmetrics.com/amazon/en/public/verify/credential/7b3c173f482b47dc90ac9df4e20e2c5a)

</div>

---

I'm a Computer Science graduate (B.Tech, AI & ML, KIET Group of Institutions, 2026) and a **Full Stack Developer Intern at Founder Code Technology**, where I build React screens and the Spring Boot REST APIs behind them.

I like backend problems where correctness matters: a payment that must never be charged twice, an event that must never be lost, services that have to agree with each other. Most of my projects are about building Java services that stay correct under retries and failures, then shipping them to AWS with Docker, Kubernetes and CI/CD.

---

## By the Numbers

| | |
|---|---|
| **423** | LeetCode problems solved in C++ (276 Medium, 89 Hard) |
| **6** | Spring Boot microservices in Distributed Lovable |
| **5** | Jenkins CI/CD pipelines, one per service |
| **40+** | JUnit and Mockito tests in FastPay |
| **11** | Services deployed on AWS EKS (Online Boutique) |
| **881 / 1000** | AWS Certified Cloud Practitioner score |

---

## Featured Project

### [Distributed Lovable](https://github.com/ISHADOW007/distributed-lovable) — AI App Builder

**The problem.** Building even a small web app takes setup, boilerplate and deployment work before you see anything running.

**What it does.** A user describes an app in plain English, and the platform generates the code and opens a live preview for that project.

**How I built it.**

- **6 Spring Boot microservices** (Account, Workspace, Intelligence, Config, Discovery, API Gateway) with shared JWT authentication and OpenFeign for service-to-service calls.
- **AI code generation** with Spring AI, RAG and Tool Calling: the current project's file tree goes into the prompt, and the model's reply is turned back into real file changes.
- **Free and Pro plans** with Stripe, with plan limits checked before a project or AI request runs.
- **Infrastructure as code:** the AWS EKS cluster is created with Terraform.
- **CI/CD:** a Jenkins pipeline per service builds, tests, scans (SonarQube, Trivy) and pushes images, then ArgoCD deploys the change to Kubernetes.
- **Monitoring** with Prometheus and Grafana.

`Java` `Spring Boot` `Spring Cloud` `Spring AI` `PostgreSQL` `Kafka` `Redis` `React` `Docker` `Kubernetes` `AWS EKS` `Terraform` `Jenkins` `ArgoCD`

[App](https://github.com/ISHADOW007/distributed-lovable) · [Terraform](https://github.com/ISHADOW007/lovable-terraform) · [GitOps](https://github.com/ISHADOW007/lovable-gitops)

---

## Projects

### [FastPay](https://github.com/ISHADOW007/distributed_Fastpay) — Payment Gateway
A payment gateway focused on correctness. Each payment moves through a state machine, with PostgreSQL persistence and a settlement flow that produces reconciliation records. Duplicate payments are prevented with idempotency keys plus optimistic and pessimistic locking, events are delivered reliably with the Kafka Outbox Pattern, and Redis handles rate limiting. Covered by 40+ JUnit and Mockito tests, including payment failures and concurrent requests.

`Java` `Spring Boot` `Spring Data JPA` `PostgreSQL` `Redis` `Kafka` `JUnit` `Mockito`

[GitHub](https://github.com/ISHADOW007/distributed_Fastpay)

### [Online Boutique on AWS EKS](https://github.com/ISHADOW007/Production-Grade_GitOps-Driven_Microservices-Demo) — Cloud Deployment
Deployed Google's open-source 11-service Online Boutique app on AWS EKS. Infrastructure is created with Terraform, GitHub Actions builds and scans each service, ArgoCD handles automatic deployments, and Prometheus and Grafana provide monitoring.

`AWS EKS` `Kubernetes` `Terraform` `GitHub Actions` `ArgoCD` `Prometheus` `Grafana`

[GitHub](https://github.com/ISHADOW007/Production-Grade_GitOps-Driven_Microservices-Demo)

### DevTinder — Developer Networking Platform
A full-stack app where developers browse profiles and connect, with Google and GitHub OAuth 2.0 sign-in, JWT sessions, real-time Socket.IO chat and role-based communities.

`React` `Node.js` `MongoDB` `Socket.IO` `JWT` `OAuth 2.0`

[Frontend](https://github.com/ISHADOW007/devTinder-frontend) · [Backend](https://github.com/ISHADOW007/devTinder-backendNew)

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Data**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**AI & Testing**

![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6366F1?style=flat-square)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## Currently

- Interning as a Full Stack Developer at Founder Code Technology (since May 2026).
- Solving LeetCode problems in C++ to keep my DSA sharp.
- Writing better READMEs for each project, including what I built and what I would improve next.

---

## GitHub Activity

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=ISHADOW007&theme=dark&hide_border=true)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ISHADOW007&layout=compact&theme=dark&hide_border=true)

</div>

---

<div align="center">

**Open to Software Engineer, Java Backend and DevOps roles**

</div>
