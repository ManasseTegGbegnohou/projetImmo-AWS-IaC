# projetImmo-AWS-IaC

## `Terraform` Configuration Files

- Terraform configuration files for the final project.
- [Services Repo](https://github.com/ManasseTegGbegnohou/projetImmo-AWS-services.git)
- [Wiki](https://github.com/ManasseTegGbegnohou/420-414-Epreuve-Finale-IaC/wiki)

---

## Requirements
- Install the AWS CLI
- Install Terraform
- Clone this repository

---

## Usage Instructions

- Set up your AWS CLI credentials:
  - On **Windows**: `C:/Users/yourUser/.aws/`
  - On **Linux**: `~/.aws/`
- Follow these steps to deploy the app:
```bash
cd projetImmo-AWS-IaC/terraform-config/
terraform init
terraform apply
```
- Wait 2 minutes for the EC2's user.data to setup
- You should now be able to acces the [website](projetImmo.manac.duckdns.org)

---

> ⚠️ This repository is a work in progress. AWS deployment is currently in the testing phase.
