# Variable Groups

## Introduction

A **Variable Group** is a centralized collection of variables that can be shared across multiple pipelines in Azure DevOps. Meaning you can use the same values across all pipelines, reducing configuration errors and easily manage different values for dev, staging, and production environments.

## Use Case

**Variable Groups** store sensitive values (connection strings, API keys, passwords) securely with encryption and access controls & you can link secrets from an Azure Key Vault as variables. NO HARD CODING SECRETS!

## Cloud Research / Documentation

- [Variable Group](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/variable-groups?view=azure-devops&tabs=azure-pipelines-ui%2Cyaml#create-a-variable-group)


## Next Steps
- We'll give certain pipelines permissions to reference the Variable Groups and reference secrets in YAML and Classic pipelines.
  - Link to future knowledge if you'd like: https://learn.microsoft.com/en-us/azure/devops/pipelines/library/variable-groups?view=azure-devops&tabs=azure-pipelines-ui%2Cyaml#use-variable-groups-in-pipelines  


