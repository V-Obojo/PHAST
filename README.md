# PHAST Framework (Physical & Hybrid Attack Surface Tactics) – Core Map  
**Last Updated:** September 23, 2025  

The **PHAST Core Map** is a structured threat intelligence framework that documents **150 actionable techniques** across five primary threat contexts:  

- **Financial Fraud (FF)**  
- **Terrorist Attacks (TA)**  
- **Live Threats (LT)**  
- **Online Scams (OS)**  
- **Data Leakage (DL)**  

Each technique is catalogued with:  
- **ID & Name** – unique reference (e.g., `FF-T001.01`).  
- **Description** – what the technique is and how it works.  
- **Procedure Examples** – Mostly *Nigeria-localized* use cases + *global parallels*.  
- **Primary Actors/Channels** – who typically carries it out and where.  
- **Common Indicators** – observable red flags or signs.  
- **Detection Sources** – logs, systems, or methods to identify the activity.  
- **Recommended Mitigations** – defensive steps and countermeasures.  
- **Cross-Context Links** – overlap with other contexts (e.g., SIM swap fraud appears in both FF and OS).  
- **Baseline PSS Factors** – Impact (I), Likelihood (L), Exploitability (E), Resilience (R), Confidence (C).  

---

## Purpose  

PHAST (Proactive Hybrid Adversary Simulation & Tracking) is designed to:  
- Support **analysts and SOC teams** with localized, context-rich adversary techniques.  
- Enable **cross-context mapping** between fraud, terrorism, scams, and data exposure.  
- Provide a **Nigeria-first but globally relevant** reference that blends regional threats (e.g., Yahoo Boys, BVN/CBN phishing, SIM registration leaks) with international parallels.  
- Serve as a **baseline for TIP/SIEM ingestion**, training, red-teaming, and policy response.  

---

## Structure  

- 📑 **Core Map** – one Markdown file (`PHAST_Framework_Core_Map_FULL.md`) containing all techniques.  
- 📌 **Table of Contents** – context-level links for quick navigation.  
- 🗂️ **Appendix** – PSS factor definitions, actor/channel taxonomy, and cross-context notes.  

---

## Usage  

- **Researchers & SOC Teams** → as a reference for incident triage and threat modeling.  
- **Policymakers & NGOs** → to understand evolving fraud, scam, and terror-financing techniques.  
- **Developers & Toolsmiths** → as a dataset for TIPs, SIEM correlation rules, or MITRE Navigator layers.  
- **Educators & Students** → for training, exercises, and contextualized case studies.  

---
