# Azure Infrastructure as Code PoC

This repository contains a Proof of Concept for deploying Azure infrastructure using Infrastructure as Code (IaC) and the "Deploy to Azure" button.

## Deploy a Simple Azure Storage Account

Click the button below to deploy a basic Azure Storage Account to your active Azure tenant.


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/vinodkumarss/AZ-Iac-custom-deployment/refs/heads/azure-iac-poc/azuredeploy.json?token=GHSAT0AAAAAADFH4X2MMGLCD7CXTU2WLYHA2CD5QRQ)

---

## How it works:

1.  **ARM Template:** The `azuredeploy.json` file defines the Azure Storage Account resources.
2.  **GitHub Hosting:** The template is hosted in this GitHub repository.
3.  **"Deploy to Azure" Button:** This button is a direct link to the Azure portal, pre-populating the deployment experience with the ARM template from this repository. When you click it, the Azure portal loads the template, allowing you to review parameters and deploy.

