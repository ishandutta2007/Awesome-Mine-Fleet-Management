# Awesome-Mine-Fleet-Management

## Top Mobile Device Management (MDM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Device Enrollment, Policy Enforcement, App Distribution, Remote Actions, Compliance & Multi-Platform Endpoint Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Device Management (MDM)** and broader unified endpoint management. These systems enroll, configure, secure, and manage smartphones, tablets, laptops, and other devices at scale—covering policies, app deployment, remote lock/wipe, compliance, and inventory.



**Examples** include Microsoft Intune, Jamf, Kandji, VMware Workspace ONE, ManageEngine Mobile Device Manager Plus, Scalefusion, Hexnode, Miradore, SOTI MobiControl, and IBM MaaS360 (the category leaders).



**Open-source emphasis**: Open-source MDM has matured significantly. **Fleet**, **MicroMDM / NanoMDM**, **MDMesh**, and **myMDM** provide production-capable, self-hosted alternatives spanning Apple, Android, Windows, Linux, and more. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft Intune](https://www.microsoft.com/en-us/security/business/microsoft-intune)**  

  Cloud-based endpoint management tightly integrated with Microsoft 365 and Entra ID, covering Windows, macOS, iOS, Android, and compliance policies at enterprise scale.



- **[Jamf](https://www.jamf.com/)**  

  Leading Apple-focused device management platform for macOS, iOS, iPadOS, and tvOS—widely used in education and enterprise Apple fleets.



- **[Kandji](https://www.kandji.io/)**  

  Modern Apple device management with strong automation, zero-touch enrollment, and streamlined admin experience for macOS and iOS.



- **[VMware Workspace ONE / Omnissa](https://www.omnissa.com/)**  

  Unified endpoint management platform supporting multi-platform devices, app delivery, and identity-driven access.



- **[ManageEngine Mobile Device Manager Plus, Scalefusion, Hexnode, Miradore](https://www.manageengine.com/)**  

  Feature-rich MDM/UEM solutions popular with mid-market and multi-OS environments, offering policy, app, and security controls.



- **[SOTI MobiControl, IBM MaaS360](https://www.soti.net/)**  

  Enterprise-grade mobile and IoT device management platforms with strong industry and rugged-device capabilities.



- **[Other commercial MDM & UEM platforms](https://www.microsoft.com/en-us/security/business/microsoft-intune)**  

  Additional solutions for device lifecycle, compliance, and endpoint security.



## Open-Source GitHub Projects



- **[Fleet](https://github.com/fleetdm/fleet)**  

  Leading open-source device management platform built on osquery. Supports MDM, software deployment, patching, and visibility across macOS, Windows, Linux, Chromebooks, iOS, and Android—with GitOps-friendly configuration and strong transparency.



- **[MicroMDM](https://github.com/micromdm/micromdm)**  

  Open-source Apple MDM server focused on API-driven management of macOS and iOS devices. Battle-tested and widely used as a foundation for custom Apple device workflows (maintenance-mode; see NanoMDM for newer direction).



- **[NanoMDM](https://github.com/micromdm/nanomdm)**  

  Minimalist, modern Apple MDM server and library heavily inspired by MicroMDM—designed for simplicity, performance, and embedding in larger systems.



- **[myMDM](https://mymdm.org/)**  

  Open-source multi-platform MDM (AGPL) aiming for full policy engine, agents for Apple, Windows, Android, Linux, and ChromeOS, enrollment, app management, and identity federation in one console.



- **[MDMesh](https://github.com/MDMesh-app/MDMesh)**  

  Modern self-hosted Android MDM focused on fleet control, kiosk mode, app delivery, and signed auto-updates with a contemporary admin console.



- **[Other open Apple MDM tooling](https://github.com/micromdm)**  

  Supporting projects around SCEP, DEP/ADE, and Apple device enrollment that complement MicroMDM/NanoMDM.



- **[osquery & related endpoint visibility](https://github.com/osquery/osquery)**  

  Foundational open-source endpoint query engine used by Fleet and many security/IT teams for inventory and compliance checks.



- **[Headwind MDM & Android open MDM forks](https://github.com/search?q=Android+MDM+OR+Headwind+MDM)**  

  Open Android device management projects and forks that some organizations adapt for kiosk and fleet use cases.



### Additional Strong Open-Source Options



- **Fleet**: Best-in-class open multi-platform device management and visibility with MDM capabilities.

- **Apple-focused**: MicroMDM / NanoMDM for pure Apple fleets that want full control and API-first design.

- **Android-focused**: MDMesh and related projects for self-hosted Android device owner management.

- **Multi-platform ambitions**: myMDM aiming for broad OS coverage under an open-core model.

- **Composable stacks**: NanoMDM or MicroMDM + osquery/Fleet + identity provider for custom Apple + Linux/Windows environments.

- Fully open self-hosted MDM is production-viable for many organizations, especially those already invested in GitOps and infrastructure-as-code.



**Frameworks for building custom systems**:  

**Fleet** is the strongest open multi-OS device management platform.  

**NanoMDM / MicroMDM** remain the go-to open foundations for Apple MDM.  

**MDMesh** and **myMDM** expand options for Android and broader multi-platform coverage.  

Commercial platforms (Intune, Jamf, Kandji, Workspace ONE, etc.) provide polished admin experiences, extensive app catalogs, advanced compliance integrations, and vendor support preferred by many large enterprises.  

Hybrid approaches are common: open-source for core policy and visibility, commercial for specific platform depth or managed service needs. Fully open stacks work well when IT teams can operate and secure the infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- MDM systems control devices that hold corporate and personal data. Misconfiguration can lock users out, wipe devices, or create security gaps. Always test enrollment and policy changes carefully and respect local privacy regulations (especially for BYOD).

- Open-source MDM offers transparency and freedom from vendor lock-in but requires you to manage certificates (APNs, SCEP), infrastructure, updates, and security. Commercial platforms shift operational burden to the vendor. Evaluate total cost of ownership, platform coverage, and support needs before choosing.



---



**Made for IT admins, security teams, Apple and Android fleet managers, and endpoint engineers.**  

Let's keep device management open, transparent, and controllable—through both excellent open-source platforms and complementary commercial MDM solutions.
