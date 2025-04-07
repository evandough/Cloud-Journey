# Azure Key Vault With Role Based Access Control (RBAC)

## Introduction

Do you remember the [Service Connection](Journey/004/Readme.md) that was created? It's basically the bridge that lets **Azure DevOps** securely talk to external systems - like **Azure**. I wanted a way to securely store secrets when automating VM creation, so I created a **Key Vault** in **Azure**. 

### Step 1 — Create A Resource Group To Store Key Vault

I created a resource group that would be specific to environments I wanted to automate based on Microsoft's [naming convention documentation](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)

### Step 2 — Create Key Vault

I created a Key Vault, [here is an overview of Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview), and the permission model I used was **Azure role-based access control (RBAC)**

### Step 3 - Assign Roles

You'll assign Azure roles to users, groups, or apps. 

## ☁️ Cloud Outcome

Verified I was able to create and view secrets in the Key Vault. Tested Azure DevOps pipeline to ensure proper access. 
