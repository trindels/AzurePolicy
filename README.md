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
| [App Services - Network Restrictions - Allow Specific Addresses - Audit](./policyDefinitions/Microsoft.Web/sites/AppServices%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Audit.json) | App Services | 259ac8b5-7446-4f79-91e7-540604ebd9c6 |
| [App Services - Network Restrictions - Allow Specific Addresses - Deny](./policyDefinitions/Microsoft.Web/sites/AppServices%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Deny.json) | App Services | baeedaa8-3af9-41da-bb08-f9737c5039b6 |
| [App Services Slots - Network Restrictions - Allow Specific Addresses - Audit](./policyDefinitions/Microsoft.Web/sites/slots/AppServices%20Slots%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Audit.json) | App Services | ad72c3b7-8b3d-4e1e-b359-32aae82e2833 |
| [App Services Slots - Network Restrictions - Allow Specific Addresses - Deny](./policyDefinitions/Microsoft.Web/sites/slots/AppServices%20Slots%20-%20Network%20Restrictions%20-%20Allow%20Specific%20Addresses%20-%20Deny.json) | App Services | 381be48d-97ab-4f8a-85dd-dc3af0274782 |
| [SQL Servers - Vulnerability Scanning - Bring Your Own Storage](./policyDefinitions/Microsoft.Sql/servers/vulnerabilityAssessments/SQL%20Servers%20-%20Vulnerability%20Scanning%20-%20BYOS.json) | SQL | 5cea7083-d842-4297-94fb-17fb10939d23 |
| [Assign User-Assigned Managed Identity to Virtual Machines (At Scale) - Bring Your Own Identity](./policyDefinitions/Microsoft.Compute/virtualMachines/Assign%20User-Assigned%20Managed%20Identity%20to%20Virtual%20Machines%20(At%20Scale).json) | Compute | d367bd60-64ca-4364-98ea-276775bddd94 |
| [Configure Linux Azure VMs to run Azure Monitor Agent with BYO UAMI](./policyDefinitions/Microsoft.Compute/virtualMachines/extensions/Configure%20Linux%20VMs%20to%20run%20Azure%20Monitor%20Agent%20with%20BYO%20user-assigned%20managed%20identity%20(At%20Scale).json) | Monitoring | ae8a10e6-19d6-44a3-a02d-a2bdfc707742 |
| [Configure Windows Azure VMs to run Azure Monitor Agent with BYO UAMI](./policyDefinitions/Microsoft.COmpute/virtualMachines/extensions/Configure%20Windows%20Azure%20VMs%20to%20run%20Azure%20Monitor%20Agent%20with%20BYO%20user-assigned%20managed%20identity%20(At%20Scale).json) | Monitoring | 637125fd-7c39-4b94-bb0a-d331faf333a9 |
| [Associate Linux Machines with a Data Collection Rule (With Tag Filtering)](./policyDefinitions/Microsoft.Insights/dataCollectionRules/Associate%20Linux%20Machines%20with%20a%20Data%20Collection%20Rules%20(With%20Tag%20Filtering).json) | Monitoring | 2ea82cdd-f2e8-4500-af75-67a2e084ca74 |
| [Associate Windows Machines with a Data Collection Rule (With Tag Filtering)](./policyDefinitions/Microsoft.Insights/dataCollectionRules/Associate%20Windows%20Machines%20with%20a%20Data%20Collection%20Rules%20(With%20Tag%20Filtering).json) | Monitoring | eab1f514-22e3-42e3-9a1f-e1dc9199355c |
