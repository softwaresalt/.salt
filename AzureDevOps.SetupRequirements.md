# Azure DevOps for Data Strategy Engagements

## Setup Requirements

### For Organizations with existing Azure Tenant

1. If you don't yet have a subscription, add a subscription to the existing tenant and include Azure DevOps in your subscription.
1. If you have a subscription already, add Azure DevOps to your existing subscription.
1. If you have existing Visual Studio Enterprise or Professional subscriptions, those will include Basic Plan capabilities.  You'll only need to pay for monthly user licenses for anyone without those subscriptions.
1. See the [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/) to determine your monthly DevOps license costs.  If you don't need professional Microsoft support, it'll cost ~$3/user/month.
1. Once you set up Azure DevOps on your subscription, you'll need to create an Organization.  Start [here](https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/organization-management) to learn how to set up your organization.
1. Once you've set up your organization, you'll need to [provide access to users](https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/add-organization-users).

### Org Level Extensions

At the organization level, the following extensions should be added:

- Personas (by Agile Extensions)
- Azure DevOps Open in Excel (by Microsoft DevLabs)
- Azure DevOps Dashboard Migration (by Microsoft DevLabs)
- Cascading Lists (by Microsoft DevLabs)
- Multivalue control (by Microsoft DevLabs)
- Process Importer (by Microsoft DevLabs)
- Feature timeline and Epic Roadmap (by Microsoft DevLabs)
- Reactivations Report (by Microsoft DevLabs)
- Retrospectives (by Microsoft DevLabs)
- Split! (by Microsoft DevLabs)
- Team Calendar (by Microsoft DevLabs)
- Estimate (by Microsoft DevLabs)
- ADO Security Scanner (by Microsoft)
- Wiql Editor (by Otto Streifel)
- Sprint Goal (by Kees Schollaart)

### Processes

Before you create your new project, you'll need to create an inherited process for your project to use.

1. Understand the [process inheritance model](https://learn.microsoft.com/en-us/azure/devops/organizations/settings/work/inheritance-process-model)
1. At the org level, select the Boards / Process setting and create an inherited process from the Agile process template. Name the new process Agile_DS (DS=Data Strategy).
1. [Set the process permissions](https://learn.microsoft.com/en-us/azure/devops/organizations/security/set-permissions-access-work-tracking?view=azure-devops#process-permissions) for the scrum master so that s/he can customize the process template to meet the process requirements for Data Strategy engagement.

### Engagement Project

1. You will need to [create a new project](https://learn.microsoft.com/en-us/azure/devops/organizations/projects/create-project) to manage all of your project related work.  Be sure to select your new, inherited Agile process as the process template your new project will use.
1. And then you'll need to [add users and provide access](https://learn.microsoft.com/en-us/azure/devops/organizations/security/add-users-team-project) to your DevOps project.
