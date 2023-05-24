# Azure Landing Zone Catalogue
This repository contains an unofficial list of various Platform and Application implementations of Azure Landing Zone along with relevant links. Feel free to open an issue to propose new ones. 

📃 The offical list of Platfrom and Application landing zones can be found on Microsoft Learn [here](https://learn.microsoft.com/en-gb/azure/architecture/landing-zones/landing-zone-deploy). 

# ⚙️ Platform (Enterprise-scale) Landing Zone
ALZ (Azure Landing Zone) is the core platform implementation of Cloud Adoption Framework Azure Landing Zones conceptual architecture. An Azure landing zone provides cloud adoption teams with a well-managed environment to run their workloads. Take advantage of the best practices described in landing zone design areas to build a strong foundation. You can then extend the foundation by implementing processes related to security, governance, and compliance. It can be deployed using different methods. Some of the most popular ones are:
- [ALZ Bicep](https://github.com/Azure/ALZ-Bicep)
- [ALZ Terraform](https://github.com/Azure/terraform-azurerm-caf-enterprise-scale)
- [ALZ Portal Accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/#azure-landing-zone-accelerator)

A full list of implementation options for enterprise-scale landing zone can be found on Microsoft Learn website [here](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/enterprise-scale/implementation).

# 📌 Application Landing Zones
- AKS
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/landing-zone-accelerator)
  - [AKS Baseline](https://github.com/mspnp/aks-baseline) - start small and expand with the AKS baseline architecture
  - [AKS landing Zone accelerator](https://github.com/Azure/AKS-Landing-Zone-Accelerator) - includes a reference implementation to deploy an instance of the AKS baseline into an enterprise-scale landing zone to support your AKS platform within the specific environmental configuration required by the broader enterprise-scale landing zone solutions.
- Azure Integration Services landing zone accelerator
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/Integration-Services-Landing-Zone-Accelerator)
- API Management Landing Zone Accelerator
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/apim-landing-zone-accelerator)
- Azure High Performance Compute (HPC) Landing Zone Accelerator
  - [Mircosoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/azure-hpc/azure-hpc-landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/az-hop)
- Azure App Service Landing Zone Accelerator
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/app-services/landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/appservice-landing-zone-accelerator)
- Data Landing Zone - Cloud-Scale Analytics
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/architectures/data-landing-zone)
  - [Portal Deployment experience](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/tutorials/tutorial-create-data-landing-zone)
  - [GitHub repo](https://github.com/Azure/data-landing-zone)
- Azure RedHat OpenShift (ARO) Landing Zone Accelerator
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/azure-red-hat-openshift/landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/ARO-Landing-Zone-Accelerator)
- Azure Spring Apps Landing Zone Accelerator
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/spring-apps/landing-zone-accelerator)
  - [GitHub repo](https://github.com/Azure/azure-spring-apps-landing-zone-accelerator)
- Azure Container Apps Landing Zone Accelerator
  - [GitHub repo](https://github.com/Azure/ACA-Landing-Zone-Accelerator)
- Enterprise-scale Landing Zone for AVS
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/azure-vmware-solution-foundation-landing-zone) - Landing zone considerations for Azure VMWare Solution
  - [GitHub repo](https://github.com/Azure/Enterprise-Scale-for-AVS)
- Enterprise-scale support for Citrix on Azure
  -  [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/wvd/landing-zone-citrix/citrix-enterprise-scale-landing-zone)
  -  [Citrix DaaS on Microsoft Azure](https://docs.citrix.com/en-us/citrix-daas-azure.html) - Design guidance for Citrix DaaS on Microsoft Azure

# 📈 Scenario-specific Landing Zones
These landing zones have been developed in the broader context of common scenarios, such as:
- [Enterprise-scale for hybrid with Azure Arc](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/hybrid/enterprise-scale-landing-zone)
- [SAP on Azure landing zone accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/sap/enterprise-scale-landing-zone)
- [Enterprise Scale for Azure Virtual Desktop](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/wvd/enterprise-scale-landing-zone)
- [Enterprise-scale for AKS](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/landing-zone-accelerator)

# ⭕ Custom Purpose Azure Landing Zones
This list contains a list of specialised ALZs based on a certain need:
- Mission Landing Zone
  - [GitHub repo](https://github.com/Azure/missionlz)
  - [Azure Academy YouTube Video](https://www.youtube.com/watch?v=9BKgz9Rl1eo&ab_channel=AzureAcademy)
- Mission Edge Landing Zone
  - [GitHub repo](https://github.com/Azure/missionlz-edge)
- Mission Critical Azure Landing Zone
  - [Microsoft Learn Mission Critical Overview article](https://learn.microsoft.com/en-us/azure/well-architected/mission-critical/mission-critical-overview)
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-landing-zone)
  - [GitHub repo](https://github.com/Azure/Mission-Critical-Connected)
- CAF Migrate Landing Zone
  - [Microsoft Learn article](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-landing-zone)
