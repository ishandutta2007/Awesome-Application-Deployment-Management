# Awesome-Application-Deployment-Management

## Top Application Deployment & Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Endpoint Management, Software Deployment & Self-Hosted Device Orchestration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Application Deployment & Management**. These tools enable IT teams to deploy software, patch systems, enforce policies, and manage devices at scale—ranging from cloud-native endpoint management platforms to self-hosted deployment orchestration tools that keep control on your own infrastructure.

**Examples** include Microsoft Intune, Jamf Pro, VMware Workspace ONE, ManageEngine Endpoint Central, Kandji, JumpCloud, and the open-source leaders Tactical RMM, MeshCentral, and Ansible.

**Open-source emphasis**: This section includes active projects for self-hosting, avoiding per-device SaaS fees, and controlling the deployment pipeline. The open-source landscape spans configuration managers, agent-based RMMs, remote management tools, and MDM/packaging utilities.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Unified Endpoint Management (UEM) and application deployment sector is estimated at **$7.5B–$8.5B in 2025** and projected to surpass **$10B+ by 2026**, growing at a ~16–23% CAGR driven by hybrid workforce requirements and zero-trust security compliance. The market is **moderately concentrated**: mega-cap cloud and platform suites (led by Microsoft Intune and Omnissa/Workspace ONE) capture the lion's share of enterprise procurement via bundled licensing, while a vibrant, fragmented tier of specialized OS platforms (Jamf, Kandji) and MSP-tailored RMMs (NinjaOne, ManageEngine) compete vigorously across SMB and mixed-device fleets.

## SaaS/Hosted Platforms

| Product | Description | Valuation / Revenue | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Intune](https://www.microsoft.com/en-us/security/business/microsoft-intune)** | Cloud-based unified endpoint management for Windows, macOS, iOS, Android, and Linux. | **$3.1T+ Market Cap** (Microsoft) / ~$245B+ Annual Revenue | **$8.00/user/month** (Plan 1, annual commitment); Plan 2 is **+$4.00/user/month** add-on; Intune Suite is **+$10.00/user/month**; included in Microsoft 365 E3/E5. | **30-day free trial** (up to 25 user licenses with full feature evaluation); no permanent free tier. |
| **[ManageEngine Endpoint Central](https://www.manageengine.com/products/desktop-central/)** | Unified endpoint management with patching, software deployment, and MDM. | **~$12.5B Valuation** (Zoho Corp) / ~$1B+ Annual Revenue | **$1.09/endpoint/month** ($6,545/year starting tier for 500 endpoints, Professional Edition); Enterprise starts at $1.37/endpoint/month. | **Free Edition permanently free for up to 25 endpoints** (full management & inventory); also offers a **30-day free trial** for unlimited endpoints. |
| **[NinjaOne](https://www.ninjaone.com/)** | Unified IT operations platform with RMM, patching, and endpoint management. | **$12.3B Valuation** / ~$500M+ ARR | **$1.50–$3.75/device/month** (starting tier ~$3.75/device/month for ≤50 endpoints; scales down to ~$1.50/device/month for 10,000+ endpoints). | **14-day free trial** (unlimited features and full remote access on test endpoints); no permanent free tier. |
| **[VMware Workspace ONE](https://www.vmware.com/products/workspace-one.html)** | Unified endpoint management and digital workspace platform (Omnissa). | **$4.0B Valuation** (acquired by KKR) / ~$1.5B ARR | **$117.99/user/year** (~**$9.83/user/month** list via CDW for Standard Shared Cloud); Education on-prem starting at $95.75/device/year. | **30-day free trial** (capped evaluation up to 100 test devices); no permanent free tier. |
| **[JumpCloud](https://jumpcloud.com/)** | Directory-as-a-Service with device management, SSO, and MDM. | **$2.6B Valuation** / ~$150M–$200M ARR | **$11.00/user/month** (Starter Package, billed annually); Device-only management packages start at **$9.00/device/month**; Plus tier is **$21.00/user/month**. | **30-day free trial** (unlimited access to all directory and device features); legacy accounts have 10 users/10 devices. |
| **[Ivanti Neurons](https://www.ivanti.com/)** | AI-powered endpoint management, patching, and discovery platform. | **~$2.0B Valuation** / ~$1.0B–$1.5B Annual Revenue | **£10.89/device/year** (~**$14.00/device/year** or ~$1.17/device/month for Patch Management Cloud starting tier at 1,500 devices); Workspace Cloud at £7.96/device/year. | **30-day vendor-assisted trial** (or module-specific trials up to 60 days / 50 seats upon sales approval); no self-service permanent free tier. |
| **[Jamf Pro](https://www.jamf.com/products/jamf-pro/)** | Apple-focused MDM with deep macOS, iOS, iPadOS, and tvOS management capabilities. | **~$1.7B Market Cap** (NASDAQ: JAMF) / ~$625M Annual Revenue | **$3.33/device/month** for iOS/iPadOS/tvOS (billed annually); **$7.17/device/month** for macOS (billed annually). | **14-day free trial** (full access to device management workflows); no permanent free tier. |
| **[Kandji (now Iru)](https://www.kandji.io/)** | Apple-focused MDM with automated compliance, vulnerability, and application management. | **$850M Valuation** / ~$60M ARR | **$3.20/device/month** (reported entry macOS tier at minimum volume commits; AWS Marketplace platform baseline starts at **$25,000/year**). | **14-day free trial** (capped at up to 10 evaluation devices via sales onboarding); no permanent free tier. |
| **[PDQ Deploy](https://www.pdq.com/)** | Windows-focused software deployment and patch management. | **~$300M Valuation** / ~$45M–$60M Annual Revenue | **$1,657.50/admin/year** (~**$138.13/admin/month**, PDQ Deploy & Inventory bundle starting tier). | **Permanent Free Mode** (unlimited target computers and custom package builds forever; restricts pre-built package library); full Enterprise trial is **14 days**. |

## Open-Source GitHub Projects

- **[Ansible](https://github.com/ansible/ansible)** [![GitHub Stars](https://img.shields.io/github/stars/ansible/ansible?style=social&color=white)](https://github.com/ansible/ansible/stargazers)  
  **Agentless configuration management and deployment automation.** Radically simple IT automation engine that automates cloud provisioning, configuration management, and application deployment across Linux, Windows, and network infrastructure.

- **[Salt](https://github.com/saltstack/salt)** [![GitHub Stars](https://img.shields.io/github/stars/saltstack/salt?style=social&color=white)](https://github.com/saltstack/salt/stargazers)  
  **High-speed event-driven orchestration and remote execution.** Scalable infrastructure management engine supporting event-driven automation, software deployment, and configuration enforcement across massive server fleets.

- **[Chef](https://github.com/chef/chef)** [![GitHub Stars](https://img.shields.io/github/stars/chef/chef?style=social&color=white)](https://github.com/chef/chef/stargazers)  
  **Infrastructure-as-code automation platform.** Powerful Ruby-based DSL for declaring system configurations, ensuring reproducible infrastructure, and deploying applications consistently across diverse environments.

- **[Puppet](https://github.com/puppetlabs/puppet)** [![GitHub Stars](https://img.shields.io/github/stars/puppetlabs/puppet?style=social&color=white)](https://github.com/puppetlabs/puppet/stargazers)  
  **Declarative configuration management and compliance system.** Enterprise-proven declarative manifest ecosystem for managing operating system states, software packages, and system security policies at scale.

- **[MeshCentral](https://github.com/Ylianst/MeshCentral)** [![GitHub Stars](https://img.shields.io/github/stars/Ylianst/MeshCentral?style=social&color=white)](https://github.com/Ylianst/MeshCentral/stargazers)  
  **The mature remote device management platform.** Self-hosted, web-based remote management tool with agent-based control, seamless file transfer, hardware KVM/AMT support, terminal access, and device grouping without licensing fees.

- **[Fleet](https://github.com/fleetdm/fleet)** [![GitHub Stars](https://img.shields.io/github/stars/fleetdm/fleet?style=social&color=white)](https://github.com/fleetdm/fleet/stargazers)  
  **The osquery-based device visibility and management platform.** Open-source endpoint management and security engine built on osquery—providing real-time visibility into laptops, servers, and containers with policy enforcement and MDM capabilities.

- **[Tactical RMM](https://github.com/amidaware/tacticalrmm)** [![GitHub Stars](https://img.shields.io/github/stars/amidaware/tacticalrmm?style=social&color=white)](https://github.com/amidaware/tacticalrmm/stargazers)  
  **The self-hosted RMM and deployment platform.** Open-source remote monitoring and management platform built on Django, Vue, and Go—providing agent-based device management, software deployment, patch orchestration, and remote desktop access.

- **[Munki](https://github.com/munki/munki)** [![GitHub Stars](https://img.shields.io/github/stars/munki/munki?style=social&color=white)](https://github.com/munki/munki/stargazers)  
  **Web-server-driven macOS software deployment and package manager.** Enables administrators to manage software installs, removals, and updates on macOS devices using simple web-server repos and Apple package formats.

- **[Foreman](https://github.com/theforeman/foreman)** [![GitHub Stars](https://img.shields.io/github/stars/theforeman/foreman?style=social&color=white)](https://github.com/theforeman/foreman/stargazers)  
  **Complete lifecycle management for physical and virtual systems.** Provides automated bare-metal provisioning, configuration management orchestration (Ansible, Puppet, Salt), and patch management across enterprise Linux and multi-cloud environments.

- **[MicroMDM](https://github.com/micromdm/micromdm)** [![GitHub Stars](https://img.shields.io/github/stars/micromdm/micromdm?style=social&color=white)](https://github.com/micromdm/micromdm/stargazers)  
  **Modular, lightweight Apple Mobile Device Management server.** Open-source Go-based MDM protocol implementation providing native Apple MDM command orchestration and configuration profile management for iOS and macOS.

- **[FOG Project](https://github.com/FOGProject/fogproject)** [![GitHub Stars](https://img.shields.io/github/stars/FOGProject/fogproject?style=social&color=white)](https://github.com/FOGProject/fogproject/stargazers)  
  **Open-source network computer cloning and deployment solution.** Web-based imaging and deployment tool facilitating PXE boot, disk cloning, snap-in software deployment, and printer management for Windows and Linux fleets.

- **[AutoPkg](https://github.com/autopkg/autopkg)** [![GitHub Stars](https://img.shields.io/github/stars/autopkg/autopkg?style=social&color=white)](https://github.com/autopkg/autopkg/stargazers)  
  **Automated software packaging and distribution framework.** Automation recipe system for fetching, preparing, and packaging macOS software releases for distribution into Munki, Jamf Pro, and other deployment systems.

- **[Nudge](https://github.com/macadmins/nudge)** [![GitHub Stars](https://img.shields.io/github/stars/macadmins/nudge?style=social&color=white)](https://github.com/macadmins/nudge/stargazers)  
  **Enforce macOS software updates through customizable user nudging.** Swift-based open-source tool that prompts and encourages users to update their macOS operating system version before deadlines.

- **[Rudder](https://github.com/Normation/rudder)** [![GitHub Stars](https://img.shields.io/github/stars/Normation/rudder?style=social&color=white)](https://github.com/Normation/rudder/stargazers)  
  **The continuous configuration management and compliance platform.** Ensures systems are configured correctly and remain compliant over time—handling package installation, service management, and policy enforcement with audit trails across Linux and Windows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **SaaS pricing models vary dramatically**: Intune charges per user; Jamf and Kandji charge per device; ManageEngine charges per endpoint; JumpCloud charges per user. Model your actual deployment (user count vs. device count) before committing.
- **Apple-focused tools are more expensive**: Jamf macOS at **$7.17/device/month** and Kandji at **$3.20/device/month** reflect the premium for deep Apple management. Cross-platform tools like Intune or ManageEngine may be more cost-effective for mixed fleets.
- **ManageEngine offers a genuinely free tier**: Up to **25 endpoints permanently**—rare among commercial endpoint management platforms.
- **Open-source RMM requires infrastructure**: Tactical RMM and MeshCentral need servers, databases, and maintenance—free software is not free operations.

---

**Made for IT administrators, MSPs, and organizations managing device fleets and software deployment.**  
Let's make application deployment and management more open, transparent, and appropriately priced.
