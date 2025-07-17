# 🛠️ DevOps Tools List

A categorized list of essential DevOps tools used in the software development lifecycle, from planning to monitoring and feedback.

---

## 1. 📋 Planning and Collaboration
- **Jira** – Agile project tracking and issue management
- **Trello** – Visual task management and team collaboration
- **Confluence** – Documentation and knowledge base
- **Slack** – Team communication
- **Microsoft Teams** – Collaboration and video conferencing

---

## 2. 🛠️ Source Code Management (SCM)
- **Git** – Distributed version control system
- **GitHub** – Git repository hosting, CI/CD, collaboration
- **GitLab** – Git hosting with built-in DevOps lifecycle tools
- **Bitbucket** – Git solution from Atlassian with pipelines

---

## 3. 🧪 Continuous Integration / Continuous Delivery (CI/CD)
- **Jenkins** – Extensible open-source automation server
- **GitHub Actions** – Native CI/CD automation in GitHub
- **GitLab CI** – Built-in continuous integration in GitLab
- **CircleCI** – Fast CI/CD pipelines
- **Travis CI** – CI service used to build and test projects

---

## 4. 🐳 Containerization
- **Docker** – Container engine for packaging applications
- **Podman** – Daemonless container engine
- **Buildah** – Building OCI container images
- **CRI-O** – Kubernetes native container runtime

---

## 5. ☸️ Container Orchestration
- **Kubernetes** – Open-source container orchestration platform
- **OpenShift** – Enterprise Kubernetes platform by Red Hat
- **Amazon EKS** – Managed Kubernetes on AWS
- **Azure AKS** – Managed Kubernetes on Azure
- **Rancher** – Kubernetes cluster management

---

## 6. ⚙️ Infrastructure as Code (IaC)
- **Terraform** – Cloud-agnostic IaC tool
- **AWS CloudFormation** – Declarative infrastructure for AWS
- **Pulumi** – IaC using general-purpose languages
- **Ansible** – Agentless configuration management
- **Chef** – Automation for infrastructure configuration
- **Puppet** – Declarative language for system configuration

---

## 7. 🧹 Configuration Management
- **Ansible**
- **SaltStack**
- **Chef**
- **Puppet**

---

## 8. 🔐 Security and Compliance (DevSecOps)
- **Trivy** – Vulnerability scanner for containers
- **Aqua Security** – Container and cloud-native security
- **Anchore** – Container security and compliance
- **OWASP ZAP** – Web app security scanner
- **Snyk** – Security for dependencies and containers
- **HashiCorp Vault** – Secrets management

---

## 9. 🔍 Monitoring and Logging
- **Prometheus** – Monitoring and alerting toolkit
- **Grafana** – Visualization and analytics
- **Elasticsearch** – Search and analytics engine
- **Logstash** – Server-side data processing pipeline
- **Kibana** – Data visualization for Elasticsearch
- **ELK Stack** – Elasticsearch, Logstash, and Kibana
- **Datadog** – Cloud monitoring as a service
- **New Relic** – Performance monitoring

---

## 10. 🚦Testing and Quality Assurance
- **Selenium** – Browser automation
- **JMeter** – Load testing tool
- **Postman** – API testing and automation
- **SonarQube** – Code quality and security analysis
- **Cypress** – End-to-end testing framework

---

## 11. 🛰️ Artifact Repository and Binary Management
- **Nexus** – Repository for artifacts
- **JFrog Artifactory** – Universal artifact manager
- **Docker Hub** – Registry for Docker container images
- **Harbor** – Cloud-native registry for Kubernetes

---

## 12. 🧩 Service Mesh
- **Istio** – Connect, secure, and observe microservices
- **Linkerd** – Lightweight service mesh
- **Consul** – Service discovery and configuration

---

## 13. 🔐 Identity and Access Management (IAM)
- **AWS IAM** – Identity and access for AWS resources
- **Azure AD** – Identity for Microsoft cloud services
- **Keycloak** – Open-source identity provider

---

## 14. ☁️ Cloud Platforms
- **Amazon Web Services (AWS)**
- **Microsoft Azure**
- **Google Cloud Platform (GCP)**
- **IBM Cloud**
- **Oracle Cloud**

---

## 15. 🧠 Artificial Intelligence / ChatOps (Optional Modern Stack)
- **ChatGPT** – AI-assisted DevOps support and explanations
- **Opsgenie** – Alerting and incident management
- **PagerDuty** – On-call scheduling and incident response

---

## ✅ DevOps Pipeline Flow (Overview)
```mermaid
graph TD
A[Plan] --> B[Develop]
B --> C[Build]
C --> D[Test]
D --> E[Release]
E --> F[Deploy]
F --> G[Operate]
G --> H[Monitor]
