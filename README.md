# Is This an ACT? — AI/SaMD Applicable Clinical Trial Determination Tool

**An interactive decision tool for ClinicalTrials.gov registration determinations involving AI and Software as a Medical Device (SaMD) studies**

Developed by **Tamiko Eto, MA, CIP** | [TechInHSR LLC](https://techinhsr.com)

---

## Overview

Research compliance professionals at academic medical centers, hospitals, and IRBs face an increasingly difficult question when AI or software-based tools are involved in clinical studies: Does this study require registration on ClinicalTrials.gov as an Applicable Clinical Trial (ACT) under FDAAA §801?

This tool provides a structured, step-by-step decision framework to guide that determination — incorporating two significant 2026 regulatory developments that have complicated the analysis:

- **FDA's January 2026 withdrawal** of the SaMD Clinical Evaluation guidance, removing the primary interpretive framework for AI/software validation in clinical studies
- **NIH's reclassification of Basic Experimental Studies with Humans (BESH)** under NOT-OD-26-032 (effective May 25, 2026), which creates a false sense of exemption that does not extend to FDA device obligations

The tool walks users through a four-question decision framework, surfaces real-world gray-zone scenarios at each decision point, and generates a printable documentation memo at the end for the study file.

---

## Features

- **Structured intended use capture** — Mad-lib format that guides users through each component of the intended use statement (function, input, output, intended user, population, setting) rather than asking for open-ended text
- **Four-question ACT framework** — Sequential decision logic keyed to FDAAA §801 with regulatory citations at each branch
- **"I'm not sure" guided pathway** — Three-question sub-tree for users uncertain whether their tool meets the medical device definition
- **CDS exemption check** — Walks through FDA's January 2025 four-criteria test with a counterexample (fails) and a positive example (holds)
- **Correct IDE categorization** — Distinguishes SR, NSR (abbreviated IDE), IDE-exempt, and non-device pathways; clarifies that NSR ≠ IDE-exempt
- **BESH warning** — Conditional flag that fires when NIH funding is indicated, with documentation of why BESH designation does not override FDA device obligations
- **Documentation memo** — Printable output with study information, structured intended use statement, question-by-question determination, and recommended next steps tailored to the outcome
- **"See an example" accordions** — Real-world gray-zone scenarios embedded at each key decision point, expandable on demand
- **Single-file, no dependencies** — Opens in any browser; no installation, no internet connection required after download

---

## How to Use

### Online (GitHub Pages)

Access the live tool at: **[https://etotamiko-lab.github.io/act-determination-tool/](https://github.com)**

No installation required. Works in any modern browser.

### Offline / Download

1. Download `index.html` from this repository
2. Open it in any web browser
3. No internet connection, server, or installation required

---

## Who This Is For

- **Research compliance professionals** at academic medical centers, hospitals, and research institutions
- **IRB administrators** reviewing protocols involving AI or software-based tools
- **Regulatory affairs staff** advising on ClinicalTrials.gov registration obligations
- **Research administrators** responding to investigator pre-submission questions
- **Investigators** seeking to understand their registration obligations before submitting a protocol

---

## Regulatory Framework

This tool is built on the following regulatory framework, current as of **May 2026**:

| Citation | Relevance |
|---|---|
| FDAAA §801 · 42 U.S.C. §282(j)(1)(A) | Applicable Clinical Trial definition and registration requirements |
| 21 U.S.C. §321(h) | Medical device definition |
| 21 CFR 812.2 | IDE applicability and exemptions |
| 21 CFR 812.2(b) | NSR device study — abbreviated IDE, IRB as authority |
| 21 CFR 812.2(c) | IDE-exempt categories |
| 21 CFR 812.20 | Full IDE application requirements |
| FDA CDS Guidance (Jan 2025) | Clinical Decision Support exemption criteria |
| 21st Century Cures Act §3060 | CDS software statutory framework |
| NIH NOT-OD-26-032 | BESH reclassification (effective May 25, 2026) |
| NIH NOT-OD-26-067 | BESH implementation guidance (April 2026) |
| FDA GMLP Principles | Good Machine Learning Practice |

> **Note:** FDA's SaMD Clinical Evaluation guidance was withdrawn January 7, 2026. No replacement has been issued as of the date of this tool's publication. The tool reflects the current regulatory gap.

---

## Acknowledgments

The underlying decision framework draws on the **Eto Three-Stage AI HSR Review Framework** (Eto, Miller, Lifson & Vidal, *Frontiers in Systems Biology*, 2026; DOI: 10.3389/fsysb.2026.1804193) and related TechInHSR tools including the AI HSR Decision Tree and AI Medical Device Classification Tool.

---

## Related Tools

All tools are available free for non-commercial use via TechInHSR:

- [AI HSR Decision Tree](https://techinhsr.com) — Is this AI project human subjects research?
- [AI Medical Device Classification Tool](https://techinhsr.com) — Step-by-step SaMD determination
- [AI HSR Risk Reference Tool v2.0](https://techinhsr.com) — 21-category IRB reviewer prompt framework

---

## Disclaimer

This tool provides **preliminary structured guidance only**. It does not constitute legal advice, regulatory advice, or a formal determination. The final ACT determination must be made by your IRB, regulatory affairs office, or legal counsel in consultation with applicable regulations and institutional policies.

For informal FDA device guidance: **FDA Division of Industry and Consumer Education (DICE)** — 1-800-835-4709  
For human subjects research questions: **OHRP** — www.hhs.gov/ohrp

---

## Licensing & IP

**Copyright © 2026 Tamiko Eto, MA, CIP | TechInHSR LLC. All rights reserved.**

This tool — including its decision logic, framework structure, regulatory analysis, case study scenarios, and documentation memo format — represents original intellectual property developed by Tamiko Eto and TechInHSR LLC.

### Non-Commercial Use (Free)

This work is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**You are free to:**
- ✅ Use this tool for non-commercial research, education, and institutional compliance purposes
- ✅ Share this tool with colleagues and institutions with attribution
- ✅ Adapt or build upon this tool for non-commercial purposes

**Under the following conditions:**
- 📋 **Attribution** — You must give appropriate credit: *"Developed by Tamiko Eto, MA, CIP | TechInHSR LLC (techinHSR.com)"*
- 🚫 **NonCommercial** — You may not use this tool or derivatives for commercial purposes without a separate written license
- 🔄 **ShareAlike** — If you adapt or build upon this tool, you must distribute your contributions under the same CC BY-NC-SA 4.0 license

### Commercial Use

Commercial use of this tool — including use in paid consulting engagements, commercial training programs, proprietary institutional products, or revenue-generating services — requires a **separate written commercial license** from TechInHSR LLC.

For commercial licensing inquiries: **info@techinhsr.com**

### What Constitutes Commercial Use

The following are examples of uses that require a commercial license:
- Incorporating this tool into a paid consulting product or service offering
- Using this tool or its framework in a commercial training or certification program
- Adapting or rebranding this tool for sale or licensing to third parties
- Using this tool in a commercial software product or platform

### IP Notice

The underlying decision framework, including the four-question ACT determination logic, the BESH/FDA parallel-track analysis, the intended use mad-lib structure, and the IDE categorization framework, constitutes original intellectual property of TechInHSR LLC. Prior publication or independent development does not constitute authorization for commercial use.

---

## Citation

If you use or reference this tool in a publication, presentation, or institutional document, please cite as:

> Eto, T. (2026). *Is This an ACT? AI/SaMD Applicable Clinical Trial Determination Tool*. TechInHSR LLC. https://[github-pages-url]. Licensed under CC BY-NC-SA 4.0.

---

## Contact

**Tamiko Eto, MA, CIP**  
Founder & Principal Consultant, TechInHSR LLC  

🌐 [techinHSR.com](https://techinhsr.com)  
✉️ info@techinhsr.com  
🔗 [LinkedIn](https://linkedin.com/in/tamikoeto)  
📝 [Substack](https://techinHSR.substack.com)

---

*Protecting human research participants in the age of artificial intelligence.*
