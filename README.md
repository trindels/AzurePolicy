# AzurePolicy

## Description

This repository contains custom Azure Policy definitions that can be used to enforce specific governance and compliance requirements within your Azure environment.

## Usage

To use these custom definitions, follow these steps:

1. Clone this repository to your local machine.
2. Import the desired policy definition(s) into your Azure Policy environment.
3. Assign the imported policy definition(s) to the desired Azure resource(s) or resource group(s).
4. Monitor the compliance status of your resources using the Azure Policy compliance dashboard.

For more information on Azure Policy and how to use custom definitions, refer to the official Azure documentation.

## Policy Definitions

| Name | Category | Policy ID |
|------|----------|-----------|
| [App Services - Network Restrictions - Allow Specific Addresses - Audit](./policyDefinitions/AppServices%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Audit.json) | App Services | 259ac8b5-7446-4f79-91e7-540604ebd9c6 |
| [App Services - Network Restrictions - Allow Specific Addresses - Deny](./policyDefinitions/AppServices%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Deny.json) | App Services | baeedaa8-3af9-41da-bb08-f9737c5039b6 |
| [App Services Slots - Network Restrictions - Allow Specific Addresses - Audit](./policyDefinitions/AppServices%20Slots%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Audit.json) | App Services | ad72c3b7-8b3d-4e1e-b359-32aae82e2833 |
| [App Services Slots - Network Restrictions - Allow Specific Addresses - Deny](./policyDefinitions/AppServices%20Slots%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Deny.json) | App Services | 381be48d-97ab-4f8a-85dd-dc3af0274782 |
