# Phishing Email Detection & Awareness System

## Description
This project contains the professional Phishing Detection and Employee Awareness Framework I made while performing a technical social engineering teardown on a malicious email vector. This assignment satisfies the requirements for the **Future Interns Cyber Security Internship**.
The goal of this project is to analyze raw email artifacts, isolate behavioral and domain red flags, establish a corporate risk classification framework, and build an actionable employee education guide to defend the human perimeter.

---

## Audit Scope & Target Specifications
- **Project Scope:** Phishing Email Analysis & Corporate Training Guide
- **Evidence Reference File:** `phishing_email_sample.txt.rtf`

---

##  Security & Analysis Tools Used
To accurately dissect the threat landscape without exposing systems to exploitation, the analysis leveraged standard open-source investigative methodologies:

1. **Email Header Analyzer Subsystems (MXToolbox & Google Toolbox)**
   - **Purpose:** Used to investigate envelope infrastructure data, transport delays, and cryptographic authentication logs ($SPF$, $DKIM$, $DMARC$).
   - **Analysis Approach:** Inspected raw transmission paths to evaluate sender spoofing flags and infrastructure credibility anomalies.

2. **Passive Browser Security Inspectors**
   - **Purpose:** Utilized to safely deconstruct destination URLs and examine structural registry elements without interacting with the active target server.
   - **Analysis Approach:** Isolated look-alike domain keywords, identified unencrypted cleartext transport protocols (`http://`), and evaluated risk parameters safely.

---

## Core Analysis Approach
The threat assessment was completed using a systematic, industry-standard lifecycle:
* **Evidence Isolation:** Documented raw email payloads within isolated, text-only configurations to ensure safe inspections.
* **Heuristic Triage:** Analyzed structural text triggers including generic salutations, fear-based urgency, and strict artificial resolution windows.
* **Risk Categorization:** Built an institutional threat matrix defining **Safe**, **Suspicious**, and **Phishing** states based on technical and behavioral criteria.
* **Remediation Mapping:** Translated technical compromises into clear corporate operational **Do's and Don'ts** for standard user training.

---

##  Repository Deliverables
* `/reports/` - Contains the publication-ready ** PHISHING DETECTION & AWARENESS REPORT.pdf`**.
* `/evidence-samples/` - Hosts the raw textual proof artifacts (`phishing_email_sample.txt.rtf`) evaluated during triage.

---

## Step-by-Step Self-Assessment Checklist
- [x] Extracted and isolated raw phishing text into standard, text-based evidence logs.
- [x] Identified and broken down multiple behavioral, language, and technical red flags.
- [x] Established a distinct three-tier organizational risk classification matrix.
- [x] Generated actionable employee training guidelines, checklists, and operational behavioral parameters.
