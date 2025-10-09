# REAL-ESTATE-AWS-IaC

## This repo contains the `Terraform` AWS Infrastructure and instructions to deploy a full-stack web app on AWS EC2

- Visit the [wiki](https://github.com/ManasseTegGbegnohou/420-414-Epreuve-Finale-IaC/wiki) for more information about the infrastructure.
- This repository [Web App Repository](https://github.com/ManasseTegGbegnohou/projetImmo-AWS-services.git) contains the network and containers configuration of the app.

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
- Change the DuckDNS domain and token in `projetImmo-AWS-IaC/terraform-config/user-data.sh`:
```
# Domain Ip Update
echo url="https://www.duckdns.org/update?domains=yourDomain&token=yourToken=$MY_PUBLIC_IP" | curl -k -K -
```
- Follow these steps to deploy the app:
```bash
cd projetImmo-AWS-IaC/terraform-config/
terraform init
terraform apply
```
- Wait 3 to 5 minutes for the EC2's user-data.sh script to complete its setup.
- You should now be able to access the [web app](https://projetImmo.manac.duckdns.org)

---

> ⚠️ This repository is a work in progress. AWS deployment is currently in the testing phase.
