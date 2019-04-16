# API Management DevOps

A guide to implements DevOps for Azure API Management.

## About API Management

There are several aspects to API Management

- Infrastructure:
  - API Managemeent can run in internal and external mode. In internal mode, API Management receives a private IP from the subnet where it was deployed and can communicate internal services or even on-prem services reachable thorugh a VPN gateway. This is the most common scenario of enterprise scenario and recommended for HIPPA and PCI compliance.
- API Management
  - In API Manages users create API defitions and Products where the Products are a collection of API definitions
- API Development
  - The recommended approach to develop APIs is to use swagger. Swagger definitions can be used to  
- API DevOps
  - Deploying Products, API Definitions and APIs via a provper CI/CD pipeline using Azure DevOps. 

This guide covers API DevOps and assumes that you have some familiarity with the other aspects of API Management.

## Assumptions

