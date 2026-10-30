# Project Dossier: Enterprise Organizational Intelligence & Executive Mapping Analysis

**Domain:** Secondary Research, Corporate Intelligence, OSINT & Data Auditing  
**Applicability:** Research Analyst, Market Intelligence, Talent Research & Business Analysis Roles  
**Author:** Gagan Dhanapune  
**Deliverables:** Master Excel Workbook (`Gagan_Dhanapune_DataAnalyst.xlsx`), Verification Audit Matrix, and Methodology Dossier  

---

## 1. Project Overview & Objective

This project demonstrates rigorous **secondary market research, open-source intelligence (OSINT), corporate hierarchy modeling, and multi-source data verification**.

### Core Objectives:
1. **Corporate Structure Analysis:** Deconstruct internal reporting lines and leadership hierarchies across 5 diverse enterprise companies spanning FinTech, InsurTech SaaS, Industrial Automation, Aerospace & Defense Electronics, and Commercial Manufacturing.
2. **Key Stakeholder Identification:** Pinpoint primary operational decision-makers, departmental leaders, and executive sponsors across specialized engineering divisions.
3. **Data Quality Auditing:** Cross-reference disparate web sources, press releases, corporate announcements, and regulatory filings to identify stale data, executive turnover, and structural realignments.
4. **Structured Analytical Reporting:** Model and deliver a comprehensive multi-sheet Excel dataset featuring verification statuses, categorized hierarchies, and direct reference trails.

---

## 2. Research Scope & Entity Overview

The research surveyed 5 enterprise organizations across distinct industrial sectors:

| # | Enterprise Entity | Industry Sector | Functional Area | Facility / Target Location |
| :--- | :--- | :--- | :--- | :--- |
| 1 | **Alliant Credit Union** | Financial Services / Digital Banking | Cloud & Platform Infrastructure | Chicago, IL (Hybrid) |
| 2 | **CCC Intelligent Solutions** | Enterprise InsurTech SaaS / AI | Cloud Architecture & Platform Systems | Chicago, IL (On-site) |
| 3 | **Signode (Crown Holdings)** | Industrial Automation & Transit Packaging | Automation & Packaging Technologies (APT) | Roselle, IL (Flagship Hub) |
| 4 | **Teledyne Technologies Inc.** | Aerospace & Defense Electronics | RF / Microwave Engineering (Storm Microwave) | Woodridge, IL (Manufacturing Site) |
| 5 | **Focal Point LLC (Legrand)** | Architectural Lighting / Electrical | Mechanical Product Innovation & Engineering | Chicago, IL |

---

## 3. Research Methodology & Analytical Techniques

### A. Advanced Boolean Logic & OSINT Extraction
Executed systematic search algorithms across public business registries, professional directories, and corporate databases:
* `("Alliant Credit Union") AND ("CIO" OR "Chief Information Officer" OR "Head of Business Strategy") AND ("Chicago")`
* `("CCC Intelligent Solutions") AND ("CTO" OR "Chief Product Officer" OR "CIO") AND ("Platform")`
* `("Signode" OR "Crown Holdings") AND ("Roselle" OR "Chicago") AND ("Automation" OR "Packaging") AND ("President" OR "Director" OR "VP")`
* `("Teledyne Storm Microwave" OR "Teledyne") AND ("Woodridge") AND ("General Manager" OR "Engineering Director")`
* `("Focal Point" OR "Legrand") AND ("Chicago") AND ("Director of Engineering" OR "VP Innovation")`

### B. 4-Tier Cross-Verification Framework
To ensure analytical integrity beyond surface-level assumptions, all records were validated across 4 independent evidence tiers:
1. **Tier 1 (Official Disclosures):** Corporate executive portals, governance pages, and official leadership rosters.
2. **Tier 2 (Regulatory & Press Records):** Official corporate announcements, SEC disclosures, and verified press releases.
3. **Tier 3 (Trade & Industry Media):** Dedicated industry publications (*Packaging World*, *Supply Chain Executive*, *BusinessWire*, *NeoCon*, *EPS Magazine*).
4. **Tier 4 (Professional Profiles):** Professional networks and public career registries to assess tenure recency.

### C. Data Integrity Auditing & Anomaly Detection
Through systematic auditing, three critical data anomalies were identified and resolved:
* **Turnover Detection:** Uncovered that a key executive at Alliant Credit Union had departed for UFCU. Corrected the record to prevent reporting inaccurate organizational structure.
* **Geographic / Subsidiary Disambiguation:** Differentiated historical personnel at overseas subsidiaries (Signode India) from active domestic leadership at the Roselle, IL flagship facility. Replaced outdated entries with verified US operational executives.
* **Temporal Confidence Tagging:** Flagged records with uncorroborated recent public activity (>5 years without verified corporate mentions) as `UNVERIFIED` with explicit audit cautions.

---

## 4. Key Research Discoveries

### Summary of Identified Key Leaders & Structural Findings:

| Enterprise Entity | Primary Decision-Maker | Official Title | Hierarchy Tier | Research Insights & Verification Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Alliant Credit Union** | **Jamie Warder** | Chief Information Officer (CIO) | C-Suite | Appointed July 2024; oversees enterprise cloud, technology architecture, and digital operations. (*Verified*) |
| **CCC Intelligent Solutions** | **Josh Valdez** | Chief Product Officer & Interim CTO | C-Suite | Appointed Feb 2026; leads product strategy and enterprise AI-driven technology roadmap. (*Verified*) |
| **CCC Intelligent Solutions** | **Justin McWhirter** | Chief Information Officer (CIO) | C-Suite | Appointed Aug 2024; oversees enterprise infrastructure, cloud operations, and application delivery. (*Verified*) |
| **Signode (Crown Holdings)** | **Tom DiNardo** | VP, Global Automation | VP Level | Commercial & operational leader for automation systems at the Roselle flagship center. (*Verified*) |
| **Teledyne Technologies** | **Ron Brunette** | General Manager, Storm Microwave | Site GM / Head | Direct operational head of the Woodridge, IL specialized RF/microwave manufacturing facility. (*Verified*) |
| **Focal Point LLC (Legrand)** | **Colin Knight** | Senior Director of Engineering | Director Level | Functional head directing mechanical design and engineering teams in Chicago. (*Verified*) |

---

## 5. Analytical Deliverable Architecture (`Gagan_Dhanapune_DataAnalyst.xlsx`)

The dataset is structured across **8 specialized sheets**:
* **Sheet 1 (`Company & Job Postings`):** Scope baseline, operational requirements, and target entities.
* **Sheets 2–6 (`1 - Alliant` to `5 - Focal Point`):** Entity-specific dossiers containing individual stakeholder profiles, verified titles, hierarchy classifications, direct URLs, and analytical relevance summaries.
* **Sheet 7 (`Consolidated Contacts`):** Centralized master repository of 20 mapped executives, color-coded by organization, with explicit `Verification Status` designations (`VERIFIED`, `PARTIALLY VERIFIED`, `UNVERIFIED`).
* **Sheet 8 (`Research Methodology`):** Complete research audit log documenting source attribution, search syntax, and data cleaning rationale.

---

## 6. Core Analytical Competencies Demonstrated

* **Secondary Market & Corporate Research:** Autonomous discovery and synthesis of qualitative business intelligence from fragmented web data.
* **Critical Data Verification & OSINT:** Multi-source validation against corporate disclosures, SEC filings, and trade press.
* **Organizational Structure Reverse-Engineering:** Mapping corporate command hierarchies from C-Suite through operational management.
* **Structured Data Modeling & Synthesis:** Designing clean, standardized, audit-ready Excel models utilizing Python (`openpyxl`).

---
*Enterprise Organizational Intelligence Project | Author: Gagan Dhanapune*
