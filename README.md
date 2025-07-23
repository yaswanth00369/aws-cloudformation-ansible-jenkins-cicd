# 🚀 AWS CloudFormation Deployment using Ansible and Jenkins CI/CD

This repository provides a complete solution for deploying AWS resources such as EC2 and S3 using **CloudFormation Templates** triggered via **Ansible Playbooks**. The deployment is fully automated using **Jenkins CI/CD pipelines**.

---

## 🔧 Tech Stack

🧰 Ansible

☁️ Amazon Web Services (CloudFormation: EC2 & S3)

🛠️ Jenkins

🗃️ GitHub (Source Control Management)

---

## 📌 Objective

✅ Automate the provisioning of AWS infrastructure (EC2 instance and S3 bucket) using CloudFormation stacks.

✅ Store reusable Ansible playbooks and CloudFormation templates in GitHub.

✅ Use Jenkins CI/CD pipelines to trigger the Ansible playbooks.

✅ Leverage Jenkins IAM Role or credentials securely for AWS authentication.

---

## 🧪 How It Works

🔁 The Jenkins pipeline is triggered — either manually or via a Git webhook (e.g., on a push).

🤖 Jenkins agent with Ansible executes the assigned playbook for provisioning.

🏗️ Ansible triggers AWS CloudFormation stack deployment (EC2 or S3).

🌐 AWS infrastructure is provisioned and ready to use in your cloud environment.

---

## 📁 Folder Structure

```
├── AWS-CF-Templates
│ ├── EC2-CFT.yaml # CloudFormation template for EC2
│ └── S3-CFT.yaml # CloudFormation template for S3
│
├── Ansible-PlayBooks
│ ├── EC2-Playbook.yaml # Ansible playbook for EC2 stack deployment
│ └── S3-Playbook.yaml # Ansible playbook for S3 stack deployment
│
├── Jenkinsfile-EC2 # Jenkins pipeline for EC2 deployment
├── Jenkinsfile-S3 # Jenkins pipeline for S3 deployment
```
---

## 🚀 S3 Stack Details

### Ansible Playbook Execution from Jenkins Pipeline

<img width="767" height="426" alt="image" src="https://github.com/user-attachments/assets/44d9af74-c248-45de-92df-1da17e98e3a9" />

### AWS Stack Details

<img width="1299" height="694" alt="image" src="https://github.com/user-attachments/assets/a90d54b5-d718-4fd9-b490-6b80ae3a3231" />

---

## 🚀 EC2 Stack Details

### Ansible Playbook Execution from Jenkins Pipeline

<img width="1299" height="426" alt="image" src="https://github.com/user-attachments/assets/1719ed1a-1a18-4276-b4a2-302e8f9a7a89" />

### AWS Stack Details

<img width="1299" height="694" alt="image" src="https://github.com/user-attachments/assets/359d102a-ae26-4f2c-9dff-f25847124ae6" />


