# The Migration Execution Guide

Prescriptive guidance for the structure and running of a successful migration project. 
[![](/images/list.png)](/images/list.png)

The guidance includes digital estate discovery, defining the migration scope with common business drivers, selection and implementation of migration tooling, project management, risk management and many other related templates.

Provide consistent, well-considered migration execution guidance at the business, project and technical levels.

Reduce the time required on Azure Migrate readiness by taking the complexity out of the different architectures, methodologies and prerequisite work.

Preempt support incidents, service outages and project delays by detailing a clear phase-by-phase migration journey with FastTrack for Azure best practices based on field experience, incident root cause analysis, the highlighting of common risks, and additional risk mitigation through request for change, and other templates with attributes that specifically address common mistakes and oversights during migrations.

## Artifacts

**Under construction - will be uploaded soon**
[Excel spreadsheet](https://github.com/Azure/migration/releases/download/v0.4/themeg.xlsx)

## Microsoft programs and funding to assist with migration projects

|Program |Description|
| ------------ | ------------ |
|[FastTrack for Azure](https://www.microsoft.com/azure/partners/fasttrack-for-azure)|FastTrack for Azure is a technical enablement program for organizations with cloud projects that enables the rapid, effective design, and deployment of Azure solutions in the cloud. It includes tailored guidance from Azure engineers that leverages proven practices and architectural guides.|
|[Microsoft Solution Assessments](https://www.microsoft.com/en-us/solutionassessments/)|To ensure you use data driven insights to plan your digital transformation.|
|[Azure migration and modernisation program](https://azure.microsoft.com/en-us/migration/migration-modernization-program/#overview)|End-to-end migration assistance with the migration of workloads like, SQL, SAP, AVD and application modernisation.|
|[Azure migration and modernisation program](https://www.microsoft.com/azure/partners/ammp)|Microsoft Partners to assist with your program of work.|

**Note**
*Microsoft programs and funding are subject to change. Please discuss with your Microsoft representative if you would like to participate in any of the programs.*

## What is involved with a typical migration project?
This resource includes guidance for all phases of the typical migration approach in the graphic below. The [design of a new, or validation of an existing landing zone](https://github.com/Azure/review-checklists) for migrated workloads is recommended, along with a [cloud operating model and operations plan](https://github.com/Azure/cloud-rolesandops) to manage migrated workloads. Neither of these are within the scope of this resource. FastTrack for Azure offer separate resources to assist with these areas.
[![](/images/migrationlifecycle.png)](/images/migrationlifecycle.png)

## How do we use the migration execution guide?
Work through the steps in the Excel spreadsheet, or navigate directly to a topic of interest. Refer to the below summary of the content in the guide.

|Step	|Item	|Description	|
| ------------ | ------------ | ------------ |
|1| Review the migration phases to get an understanding of the end-to-end procedure	|Migration Lifecycle|
|2| Review workshop questions	|Sample questions to use during workshops with the business and technical teams in order to populate the migration templates and make migration decisions.|
|3| Review the DACI matrix to understand the roles and responsibilities within a typical migration project	|Resource Management|
|4| Assign resources to roles and responsibilities using the Team worksheet	|Resource Management|
|5| Familiarize or refresh knowledge using recommended training resources and reference material	|Training|
|6| Reference the 'Tooling...' worksheets for a visual summary of the different discovery, assessment and migration strategies.	|Tooling|
|7| Use the Checklist to ensure that key business, project management and technical recommendations are followed, and common issues are avoided	|Best practice, field experience and incident root cause driven guidance.|
|8| Consider templates for your project:	||
||	Project Plan Template	|Project Management|
||	Digital Estate Discovery Template	|The purpose of the digital estate discovery is to present an inventory of applications and services to the business in order to determine the scope and nature of a migration project. Important dates should be captured and mapped to milestones in the project plan.|
||	Workload Template	|The purpose of the workload resource is to document and map the current technical attributes of the individual components of a workload to the future attributes of the migrated state. The information in this resource is used as input when configuring replication and migration options. It is also an important input to pre-and-post migration tasks that form the migration-day runbook.|
||	Wave Template	|The purpose of a wave plan is to document the workloads that will be grouped together in a single migration sprint. Dependent services are typically included in the same Migration Wave. In the portal, you can select up to 10 VMs at once for migration. To migrate more machines, add them to groups in batches of 10.|
||	Runbook Template	|The purpose of a migration-day runbook is to provide migration engineers with a proven list of tasks to perform during test and production migration windows. The migration runbook in this guide is an example of what should be created for every machine, in all environments, for each workload.|
||	Change Template	|The purpose of the request for change template is to provide migration specific details for consideration by the business, service management and migration teams for inclusion in their change management process. It is also an additional checkpoint to help ensure that important migration decisions are made and relevant tasks carried out. It is recommended to seek approval early, clarify expectations and roles of approvers in advance and to establish a Cloud Change Authority.|
||	Risk Register Template	|The risk register is a very important part of every migration project. The purpose of the example in this guide is to detail common risks that need to be evaluated along with any available mitigation, and plans to migrate services that are subject to these risks.|

------------
**Related FastTrack for Azure resources**
- [Landing Zone Review Checklist](https://github.com/Azure/review-checklists)
- [Cloud Roles and Operations Management](https://github.com/Azure/cloud-rolesandops)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.