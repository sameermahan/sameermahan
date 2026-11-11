# Sameer Mahan | Cybersecurity Portfolio

Hi, I’m Sameer. I’m based in Orange County, California, and I’m pursuing my M.S. in Cybersecurity and Information Assurance at Western Governors University. My background is in technology support and data analysis. Here, I document how I investigate security incidents, configure cloud controls, and design networks.

[Certifications](#certifications) · [Projects](#projects) · [About me](#about-me)

## Certifications

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-B42338?style=for-the-badge)
![CompTIA CySA+](https://img.shields.io/badge/CompTIA-CySA%2B-B42338?style=for-the-badge)
![ISC2 Certified in Cybersecurity](https://img.shields.io/badge/ISC2-Certified%20in%20Cybersecurity-334155?style=for-the-badge)

<!-- To make a badge clickable, wrap its image in a link to your public verification URL. -->

## Projects

### Azure Access Control and VM Backup

`Cloud Security Lab`

**Objective**  
Limit cross-department access in a simulated Azure migration and establish a daily backup policy for virtual machines.

**Methodology**

- Reviewed Azure role assignments for Accounting, Marketing, and IT at the resource-group level.
- Checked departmental Key Vault permissions, including the distinction between managing a vault and reading its secrets.
- Created a VM backup policy in a Recovery Services vault and captured its configuration in the Azure portal.

**Tools Used**  
`Azure RBAC` · `Azure Key Vault` · `Azure Backup` · `Recovery Services vault`

**Outcome**  
Configured the `SWBTL` policy to run daily at 7 p.m. Eastern and retain instant-restore snapshots for three days. Two screenshots show the configured settings and the policy listed in the vault.

[Read the walkthrough](projects/azure-cloud-security/README.md) · [View the backup configuration](projects/azure-cloud-security/assets/azure-backup-configuration.png)

---

### Windows Cryptomining Incident Response

`Incident Response Lab`

**Objective**  
Investigate high CPU usage on a simulated Windows endpoint, identify the process responsible, and restore endpoint protection.

**Methodology**

- Investigated the XMRig process alongside disabled Defender protection and outbound traffic to TCP port `3333`.
- Stopped the mining process and corrected the local Group Policy setting that had disabled antivirus protection.
- Restored Defender and updated outbound firewall rules for the traffic identified in the exercise.

**Tools Used**  
`Task Manager` · `Microsoft Defender` · `Local Group Policy` · `Windows Firewall`

**Outcome**  
Stopped the miner and restored Defender protection in the lab. The incident chronology records the actions in order, and the indicator register explains why the outbound connection mattered alongside the host evidence.

[Read the walkthrough](projects/windows-incident-response/README.md) · [View the incident chronology](projects/windows-incident-response/investigation/incident-chronology.md)

---

### Network Segmentation for a Healthcare and Finance Merger

`Security Architecture Proposal`

**Objective**  
Design a network that lets two merging organizations share necessary services while restricting access to financial and healthcare systems. The project had a $50,000 planning cap.

**Methodology**

- Mapped public services, finance, healthcare, and administration into separate trust zones.
- Identified where traffic needed to cross those boundaries and proposed firewall, VPN, and identity controls.
- Prioritized controls by risk, cost, and the effort required to maintain them.

**Tools Used**  
`Network topology diagram` · `Risk register` · `Budget worksheet`

**Outcome**  
Produced a proposed topology showing where access should be restricted. The accompanying risk register connects each design decision to a specific concern, including lateral movement and overly broad administrative access.

[Read the proposal](projects/enterprise-network-security/README.md) · [View the proposed topology](projects/enterprise-network-security/assets/proposed-network-architecture.svg)

<!-- Add your next project here. Copy a project section above and update its title, type, objective, methodology, tools, outcome, and links. -->

## About me

My work in technology support taught me to troubleshoot with the person experiencing the problem. Leading a nonprofit that supported Afghan refugee families taught me to listen carefully and coordinate people around a practical goal. I bring both habits to security investigations and design decisions.

- **Education** — M.S. in Cybersecurity and Information Assurance, WGU (in progress)
- **Undergraduate degree** — B.A. in Public Health, Biology minor, University of Washington Bothell
- **Interests** — Cloud security, incident response, and security architecture

[GitHub](https://github.com/sameermahan) · [Data portfolio](https://github.com/sameermahan/sameer-portfolio)

**Portfolio website** — Coming soon.
