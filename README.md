# Awesome-Application-Deployment-Management

## Top Application Deployment & Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Endpoint Management, Software Deployment & Self-Hosted Device Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Deployment & Management**. These tools enable IT teams to deploy software, patch systems, enforce policies, and manage devices at scale—ranging from cloud-native endpoint management platforms to self-hosted deployment orchestration tools that keep control on your own infrastructure.



**Examples** include Microsoft Intune, Jamf Pro, VMware Workspace ONE, ManageEngine Endpoint Central, Kandji, JumpCloud, and the open-source leaders Tactical RMM and MeshCentral (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-device SaaS fees, and controlling the deployment pipeline. The open-source landscape is anchored by **Tactical RMM** (the self-hosted remote monitoring and management platform with agent-based deployment), **MeshCentral** (the mature remote device management and control platform), and **Rudder** (the continuous configuration management and compliance tool), with **Fleet** serving osquery-based device visibility needs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Microsoft Intune](https://www.microsoft.com/en-us/security/business/microsoft-intune)** | Cloud-based unified endpoint management for Windows, macOS, iOS, Android, and Linux. | **Plan 1**: **$8/user/month** (annual commitment). **Plan 2**: +$4/user/month. **Intune Suite**: +$10/user/month. Included in Microsoft 365 E3/E5 and EMS E3/E5 . | No standalone free tier. Included with qualifying Microsoft 365 subscriptions. Trial available. |

| **[Jamf Pro](https://www.jamf.com/products/jamf-pro/)** | Apple-focused MDM with deep macOS and iOS management capabilities. | **iOS/iPadOS/tvOS**: **$3.33/device/month** (billed annually). **macOS**: **$7.17/device/month** . Volume licensing via resellers (e.g., CDW at $33.99/device/year for iOS at 2,500–4,999 licenses) . | No free tier. Trial available. |

| **[VMware Workspace ONE](https://www.vmware.com/products/workspace-one.html)** | Unified endpoint management and digital workspace platform. | **Standard (Shared Cloud)**: **$117.99/user/year** (list via CDW) . **Education On-Premise**: $95.75/device/year . | No free tier. Trial available. |

| **[ManageEngine Endpoint Central](https://www.manageengine.com/products/desktop-central/)** | Unified endpoint management with patching, software deployment, and MDM. | **Professional**: **$1.09/endpoint/month** ($6,545/year for 500 endpoints). **Enterprise**: $1.37/endpoint/month. **UEM**: $1.59/endpoint/month. **Security**: $2.30/endpoint/month . | **Free Edition**: Up to **25 endpoints** permanently. **30-day free trial** with full features . |

| **[Kandji (now Iru)](https://www.kandji.io/)** | Apple-focused MDM with automated compliance and vulnerability management. | **Quote-only**. AWS Marketplace lists **Apple MDM at $25,000/year** baseline . Buyer-reported macOS pricing: **$3.20–$8/device/month** depending on volume and add-ons . | No free tier. Demo via sales. |

| **[JumpCloud](https://jumpcloud.com/)** | Directory-as-a-Service with device management, SSO, and MDM. | **Starter**: ~**$11/user/month** (annual). **Plus**: ~**$21/user/month** . | No permanent free tier. Trial available. |

| **[Ivanti Neurons](https://www.ivanti.com/)** | AI-powered endpoint management and security platform. | **Patch Management Cloud**: **£10.89/device/year** (1,500 devices). **Discovery Cloud**: £4.77/device/year. **Workspace Cloud**: £7.96/device/year . Quote-based for full platform. | No public free tier. Trial via sales. |

| **[PDQ Deploy](https://www.pdq.com/)** | Windows-focused software deployment and patch management. | **Starting at $1,657.50/year** (PDQ Deploy & Inventory bundle) . | **Free version** available with limited features. Trial for full version. |

| **[NinjaOne](https://www.ninjaone.com/)** | Unified IT operations platform with RMM, patching, and endpoint management. | **$1.50–$3.75/device/month** depending on volume (10,000 endpoints = $1.50; ≤50 endpoints = $3.75) . | **14-day free trial**. No permanent free tier. |



## Open-Source GitHub Projects



- **[Tactical RMM](https://github.com/amidaware/tacticalrmm)** [![GitHub Stars](https://img.shields.io/github/stars/amidaware/tacticalrmm?style=social&color=white)](https://github.com/amidaware/tacticalrmm/stargazers)  

  **The self-hosted RMM and deployment platform.** Open-source remote monitoring and management tool built on Django, Vue, and Go—providing agent-based device management, software deployment, patching, scripting, and remote control without per-device SaaS fees. Best for MSPs and IT teams wanting full control over their RMM infrastructure.



- **[MeshCentral](https://github.com/Ylianst/MeshCentral)** [![GitHub Stars](https://img.shields.io/github/stars/Ylianst/MeshCentral?style=social&color=white)](https://github.com/Ylianst/MeshCentral/stargazers)  

  **The mature remote device management platform.** Self-hosted web-based remote management with agent-based control, file transfer, terminal access, and device grouping. Best for teams needing remote control and basic management without commercial RMM licensing.



- **[Rudder](https://github.com/Normation/rudder)** [![GitHub Stars](https://img.shields.io/github/stars/Normation/rudder?style=social&color=white)](https://github.com/Normation/rudder/stargazers)  

  **The continuous configuration management platform.** Ensures systems are configured correctly and remain compliant over time—handling package installation, service management, and policy enforcement across Linux, Windows, and network devices. Best for teams wanting declarative, GitOps-style configuration management with audit trails.



- **[Fleet](https://github.com/fleetdm/fleet)** [![GitHub Stars](https://img.shields.io/github/stars/fleetdm/fleet?style=social&color=white)](https://github.com/fleetdm/fleet/stargazers)  

  **The osquery-based device visibility platform.** Open-source device management and security built on osquery—providing real-time visibility into laptops, servers, and containers with policy enforcement and vulnerability detection. Best for security-focused teams wanting detailed device telemetry without commercial MDM lock-in.



### Additional Strong Open-Source Options



- **Ansible** — Agentless configuration management and application deployment. Best for infrastructure automation across servers and network devices.

- **Puppet** — Configuration management with declarative manifests and a mature ecosystem. Best for large-scale enterprise configuration enforcement.

- **Chef** — Infrastructure automation with a Ruby-based DSL. Best for teams wanting programmable infrastructure-as-code.

- **Frameworks for building custom systems**: Use **Tactical RMM** for agent-based device management and deployment, **Rudder** for configuration compliance, and **Ansible** for server provisioning. Pair **Fleet** when detailed device telemetry is required.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **SaaS pricing models vary dramatically**: Intune charges per user; Jamf and Kandji charge per device; ManageEngine charges per endpoint; JumpCloud charges per user. Model your actual deployment (user count vs. device count) before committing.

- **Apple-focused tools are more expensive**: Jamf macOS at **$7.17/device/month** and Kandji at **$3.20–$8/device/month** reflect the premium for deep Apple management . Cross-platform tools like Intune or ManageEngine may be more cost-effective for mixed fleets.

- **ManageEngine offers a genuinely free tier**: Up to **25 endpoints permanently**—rare among commercial endpoint management platforms .

- **Open-source RMM requires infrastructure**: Tactical RMM and MeshCentral need servers, databases, and maintenance—free software is not free operations.



---



**Made for IT administrators, MSPs, and organizations managing device fleets and software deployment.**  

Let's make application deployment and management more open, transparent, and appropriately priced.
