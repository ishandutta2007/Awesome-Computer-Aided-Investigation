# Awesome-Computer-Aided-Investigation

# Top Computer-Aided Investigation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Case Management, Link Analysis, Evidence Review, Digital Forensics Investigation, OSINT & Investigative Intelligence*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer-Aided Investigation**. These systems support case management, link/chart analysis, evidence processing, timeline reconstruction, and collaborative investigation for law enforcement, corporate compliance, fraud, and digital forensics teams.

**Examples** include Case Closed Software, Case IQ, i2 Analyst's Notebook, IBM i2, Nuix Investigate, Magnet Review, Veritone Investigate, CaseGuard, CaseFleet, and CasePacer (the category leaders).

**Open-source emphasis**: Full commercial investigation suites dominate regulated and high-volume environments. Strong open building blocks exist—**OpenCTI**, **Cortex**, legacy **TheHive** components, **Maltego Community**, **Autopsy**, and related DFIR tools. This section expands those while remaining realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Case Closed Software](https://www.caseclosedsoftware.com/)**  
  Investigation and case management software for law enforcement and public-sector investigative workflows.

- **[Case IQ](https://www.caseiq.com/)**  
  Case management and investigative platform focused on fraud, misconduct, compliance, and corporate investigations with documentation and link analysis.

- **[i2 Analyst's Notebook / IBM i2](https://www.ibm.com/products/i2-analysts-notebook)**  
  Industry-standard link analysis and charting software for visualizing entities, relationships, timelines, and investigative narratives.

- **[Nuix Investigate](https://www.nuix.com/)**  
  Investigative analytics platform for processing, searching, and analyzing large volumes of unstructured evidence and data.

- **[Magnet Review](https://www.magnetforensics.com/)**  
  Digital evidence review and investigation platform from Magnet Forensics for collaborative case review and analysis.

- **[Veritone Investigate](https://www.veritone.com/)**  
  AI-assisted investigation platform for analyzing media, audio, and other evidence sources in investigative workflows.

- **[CaseGuard](https://www.caseguard.com/)**  
  Redaction, evidence processing, and investigation support software for law enforcement and legal teams.

- **[CaseFleet](https://www.casefleet.com/)**  
  Litigation and investigation case management with timelines, fact management, and collaboration features.

- **[CasePacer](https://www.casepacer.com/)**  
  Case management software for legal and investigative teams focused on matter tracking and workflow.

## Open-Source GitHub Projects
- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  
  Leading open-source threat intelligence and knowledge platform—entities, relationships, observables, and investigation-oriented graphs (Apache 2.0).

- **[Cortex](https://github.com/TheHive-Project/Cortex)**  
  Open-source observable analysis and active response engine commonly paired with case management for automated enrichment.

- **[TheHive (legacy open versions)](https://github.com/TheHive-Project/TheHive)**  
  Collaborative security incident and case management platform (older versions open; current distribution commercial via StrangeBee).

- **[Maltego Community / open transforms](https://www.maltego.com/)**  
  Link analysis and OSINT platform with community edition and many open transforms for entity and relationship mapping.

- **[Autopsy](https://github.com/sleuthkit/autopsy)**  
  Open-source digital forensics platform built on The Sleuth Kit for disk analysis, timeline, and evidence examination.

- **[The Sleuth Kit](https://github.com/sleuthkit/sleuthkit)**  
  Foundational open-source digital forensics library and tools used by Autopsy and other investigation workflows.

- **[GRR Rapid Response / Velociraptor](https://github.com/google/grr)** / [Velociraptor](https://github.com/Velocidex/velociraptor)  
  Open-source endpoint investigation and remote forensics frameworks for live response and evidence collection.

- **[MISP](https://github.com/MISP/MISP)**  
  Open-source threat intelligence sharing platform that supports investigative enrichment and IOC correlation.

- **[Hunchly and OSINT capture open practices](https://www.hunch.ly/)**  
  Web evidence capture approaches (commercial tool with open methodology influence) for preserving online investigation trails.

- **[Documentation and DFIR open playbooks](https://github.com/TheHive-Project)**  
  Guides for building investigation labs with OpenCTI, Cortex, Autopsy, and related open DFIR stacks.

### Additional Strong Open-Source Options
- Using **OpenCTI + Cortex** for knowledge graphs, observables, and automated enrichment in cyber and threat investigations.
- Running **Autopsy / The Sleuth Kit** for digital media and disk forensics.
- Applying **Maltego Community** and open transforms for link analysis and OSINT.
- Leveraging **Velociraptor** or **GRR** for endpoint-scale investigation and live response.
- Accepting that enterprise link analysis (i2), large-scale e-discovery/investigation processing (Nuix), regulated LE case management, and polished multi-user evidence review still favor commercial platforms (Case IQ, IBM i2, Nuix, Magnet, Case Closed, etc.).
- Focusing open-source efforts on transparency, reproducibility, and integration with STIX/TAXII and open DFIR standards.

**Frameworks for building custom systems**: Collect evidence (Autopsy/Velociraptor) → enrich observables (Cortex) → model entities and cases (OpenCTI / legacy TheHive patterns) → visualize links (Maltego or graph tools). Suitable for SOC/DFIR teams, research, and smaller investigative units. Law enforcement and large corporate investigation programs typically rely on commercial computer-aided investigation platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Investigation tools handle sensitive evidence and personal data. Open-source deployments require strict chain-of-custody, access control, and legal compliance. This list is not legal, forensic, or law-enforcement advice.

---
**Made for investigators, DFIR analysts, compliance teams, and open-source security advocates.**
Let's keep investigations rigorous, reproducible, and as open as practical.
