# Azure Infrastructure as Code PoC

This repository contains a Proof of Concept for deploying Azure infrastructure using Infrastructure as Code (IaC) and the "Deploy to Azure" button.

## Deploy a Simple Azure Storage Account

Click the button below to deploy a basic Azure Storage Account to your active Azure tenant.


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvinodkumarss%2FAZ-Iac-custom-deployment%2Frefs%2Fheads%2Fazure-iac-poc%2Fazuredeploy.json?token=GHSAT0AAAAAADFH4X2MWAQCNLWKJ763PHXK2CD5HRQ)

---

## How it works:

1.  **ARM Template:** The `azuredeploy.json` file defines the Azure Storage Account resources.
2.  **GitHub Hosting:** The template is hosted in this GitHub repository.
3.  **"Deploy to Azure" Button:** This button is a direct link to the Azure portal, pre-populating the deployment experience with the ARM template from this repository. When you click it, the Azure portal loads the template, allowing you to review parameters and deploy.

