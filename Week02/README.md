
**Prepared by:** Carla Mae R. Villafranca 
**Submitted to:** John Randolf M. Penaredondo, MIT  
**Course & Program:** Bachelor of Science in Information Technology (BSIT)  
**Project Track:** Week 2 Portfolio Project — Enterprise Infrastructure Planning  

---

## Project Overview
Every successful IT infrastructure begins with proper planning. Before purchasing computers, installing servers, configuring networks, or deploying cloud services, a System Administrator must first understand the organization's business requirements and design an infrastructure that supports business operations. 

This project documents the comprehensive, from-scratch technical infrastructure design for a newly established startup company, engineered to mirror a professional proposal ready for executive review.

---

## Learning Objectives
By completing this portfolio deployment, the following objectives have been met:

### Knowledge
* Explained the roles, tasks, and core responsibilities of a System Administrator.
* Identified and mapped the hardware, software, and networking configurations of a small business.
* Mastered the purpose of structural IT documentation and infrastructure blueprinting.

### Skills
* Analyzed organizational IT footprints and department-specific constraints.
* Prepared industry-standard asset inventories using Markdown.
* Designed an enterprise-grade network topology.
* Created structured technical documentation using Git-versioned Markdown files.

### Attitude
* Demonstrated engineering professionalism, structured asset tracking, concise technical communication, high attention to structural detail, and analytical critical thinking.

---

## Company Scenario
The documentation models the infrastructure blueprint for **LagunaTech Solutions Inc.**, an agile custom software development and digital transformation agency. 

### Current Baseline Matrix:
* **Staff Capacity:** 20 Full-Time Employees occupying a single physical commercial office floor.
* **Physical Status:** The space contains zero pre-existing computers, servers, network drops, internet lines, or security governance frameworks.

### Departmental Workforce Distribution:
* **Information Technology (IT):** 5 Employees
* **Human Resources (HR):** 4 Employees
* **Finance:** 5 Employees
* **Sales & Marketing:** 6 Employees
* **Total Office Count:** 20 Nodes

---

## Hardware Inventory Summary
Below is a condensed summary of the procurement hardware mapped to support the 20-seat single-floor cluster.

| Asset ID Group | Hardware Type | Qty | Target Allocation | System Justification |
| :--- | :--- | :--- | :--- | :--- |
| LTS-HW-LAP-01/05 | High-Compute Laptops | 5 | IT Department | Supports local hypervisors, heavy compilation, and on-call mobility. |
| LTS-HW-LAP-06/11 | Thin & Light Laptops | 6 | Sales & Marketing | Optimized for mobility, client presentations, and cloud CRM updates. |
| LTS-HW-DSK-01/09 | Pro Desktop Towers | 9 | HR & Finance | Dedicated stationary setups for local payroll ledgers and financial tools. |
| LTS-HW-MON-01/20 | 24" FHD Displays | 20 | All Staff | Standardized dual-screen configurations to scale workspace efficiency. |
| LTS-HW-SRV-001 | 1U Rackmount Server | 1 | IT / Server Closet | Hosts directory identities, local Git repositories, and testing beds. |
| LTS-HW-NAS-001 | 4-Bay Storage NAS | 1 | Shared Network | Implements automated local workspace image harvesting. |
| LTS-HW-UPS-01/03 | Smart Power UPS Line | 3 | Server / Admin Banks | Safeguards critical components against sudden regional line drops. |

---

## Software Inventory Summary
Standardized, secure operating environments are managed across all endpoints using the following base configurations:

| Software | Version Core | License Scheme | Enterprise Core Function |
| :--- | :--- | :--- | :--- |
| **Windows 11 Pro** | 23H2 / 24H2 | Volume / OEM | Core endpoint platform enabling BitLocker encryption and domain pairing. |
| **Ubuntu Server** | 24.04 LTS | Open Source (GPL) | High-reliability backbone OS running local database containers and utilities. |
| **Microsoft Office** | 2024 / M365 | Commercial Business | Standard office productivity tool for billing templates, data arrays, and logs. |
| **VS Code** | Latest Stable | Open Source (MIT) | Extensible text editor environment for active software engineering projects. |
| **Git & GitHub Desktop** | Latest Stable | GPLv2 / Freeware | Distributed version tracking and branch control engine across development assets. |
| **VirtualBox** | 7.1.x | Open Source (GPLv2) | Local Type-2 virtualization workspace for system deployment sandboxes. |
| **Microsoft Defender** | Native OS | Bundled Enterprise | Edge endpoint protection engine tracking real-time signature behavior. |
| **AnyDesk** | Latest Stable | Fleet Commercial | Remote connection software for immediate helpdesk remediation loops. |

---

## Embedded Network Diagram
The structural map below outlines the perimeter defenses and network segments established for the company. The physical layout separates departmental traffic using isolated VLAN policies, controlled by a hardware firewall.

![LagunaTech Solutions Network Topology](diagrams/network-topology.png)

*Note: If the diagram graphic does not render natively in your browser, you can access the vector file directly via [diagrams/network-topology.pdf](diagrams/network-topology.pdf).*

---

## Technologies Used
The following developer tools, technical frameworks, and design applications were used to create this portfolio plan:
* **Documentation & Markup:** [Markdown Spec](https://daringfireball.net)
* **Topology & CAD Modeling:** [Draw.io / Diagrams.net](https://diagrams.net)
* **Version Control System:** [Git Source Engine](https://git-scm.com)
* **Hosting Platform:** [GitHub Repositories](https://github.com)

---

## Challenges Encountered
During the architectural design phase of this enterprise deployment plan, two distinct technical challenges emerged:
1. **Resource Mapping and Allocation Justification:** Balancing a fixed 20-employee organizational matrix with an accurate hardware and line budget required mapping physical assets cleanly without over-provisioning infrastructure nodes.
2. **Network Traffic Isolation Security:** Organizing logical access paths using standard Draw.io shapes required deep critical thinking to ensure the Finance department's accounting lanes were isolated while keeping them reachable for IT helpdesk administration.

---

## Reflection
Designing this infrastructure plan from scratch highlighted that a system administrator's job is rooted heavily in strategic blueprinting long before any physical equipment is deployed. 

The process taught me to transition away from looking at hardware through a consumer lens, instead looking at it through an operational framework focused on high availability, data redundancy, and robust endpoint defense. Balancing departmental needs against architectural controls helped build the analytical perspective needed to manage business uptime, manage technical debt, and deploy secure enterprise networks.

---

## 📚 References
* Laguna State Polytechnic University. (2026). *ITEP 414 – System Administration and Maintenance Self-Paced Learning Module*. LSPU Press.
* Nemeth, E., Snyder, G., Hein, T. R., Whaley, B., & Mackin, D. (2017). *UNIX and Linux System Administration Handbook* (5th ed.). Addison-Wesley Professional.
* Cisco Systems. (2023). *Small Business Network Design Best Practices Guide*. Retrieved from [Cisco Reference Library](https://cisco.com).

