# projetImmo-AWS-IaC

## This repo contains the `Terraform` AWS Infrastructure to deploy a FullStack React web app

- [Wiki](https://github.com/ManasseTegGbegnohou/420-414-Epreuve-Finale-IaC/wiki)
- [Web App Repository](https://github.com/ManasseTegGbegnohou/projetImmo-AWS-services.git)

---

## Requirements
- Install the AWS CLI
- Install Terraform
- Clone this repository

---

## Deployement Instructions

- Copy and paste your AWS CLI credentials in this file:
  - On **Windows**: `C:/Users/yourUser/.aws/credentials`
  - On **Linux**: `~/.aws/credentials`
- Follow these steps to deploy the app:
```bash
cd projetImmo-AWS-IaC/terraform-config/
terraform init
terraform apply
```
- Wait 2 minutes for the EC2's user-data.sh to setup
- You should now be able to access the [web app](https://projetImmo.manac.duckdns.org)
- 
---

> ⚠️ This repository is a work in progress. AWS deployment is currently in the testing phase.
