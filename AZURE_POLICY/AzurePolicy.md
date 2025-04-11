# Azure Policy

This repository contains Azure Policy definations and assignments.

## Azure built in policies & initiatives

[Azure Governance Policy Documentation](https://learn.microsoft.com/en-us/azure/governance/policy/)

## Repository Files Structure

azure-policy/
│
├── policies/
│   └── deny-public-ip/
│       ├── policy-definition.json
│       └── parameters.json
│
├── assignments/
│   └── deny-public-ip-assignment.json
│
└── workflows/
    └── deploy-policy.yml
