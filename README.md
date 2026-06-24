# 🏥 Securing AI in Medical Imaging
### IT595 Master's Capstone in Cybersecurity Management | Purdue University Global

> A cybersecurity and governance framework for AI-enabled medical imaging systems — bridging clinical practice, patient privacy, and responsible AI adoption.

---

## 📌 Project Overview

This capstone project conducts a cybersecurity-focused assessment of AI-enabled medical imaging systems within a fictional integrated healthcare organization, **Horizon Valley Health System (HVHS)**. The project examines vulnerabilities across the imaging AI data lifecycle and proposes a tailored security and governance framework to protect patient data while enabling safe, ethical AI adoption in clinical environments.

**Presented:** March 17, 2026 | **Instructor:** Dr. Luitel | **Institution:** Purdue University Global

---

## 🏛️ Organizational Context

**Horizon Valley Health System (HVHS)** is a fictional integrated healthcare organization created for the purposes of this project. HVHS operates regional hospitals, outpatient clinics, and diagnostic imaging centers providing services across CT, MRI, PET, ultrasound, and X-ray modalities. The organization has begun integrating AI into its imaging workflows to assist clinicians with image analysis and clinical decision support — and needed a governance framework to do so responsibly.

---

## ⚠️ Risk Areas Addressed

Five core risks to patient data were identified and analyzed across the imaging AI data lifecycle:

| Risk ID | Threat | Vulnerability | Risk Rating |
|---|---|---|---|
| 001 | External hackers targeting healthcare AI | Poor data segmentation | **High** |
| 002 | Discriminatory or inaccurate AI output | Biased training data | **Medium–High** |
| 003 | Insider threats | Excessive access controls | **Medium–High** |
| 004 | Radiologist over-reliance on AI output | Insufficient human oversight | **Medium–High** |
| 005 | Compromised third-party AI vendors | Various vendor vulnerabilities | **High** |

---

## 📁 Repository Contents

```
📂 securing-ai-in-medical-imaging/
├── 📊 Dburton-IT595_Assignment-Unit10__Capstone_Slides_.pdf   # Presentation deck
└── 📄 Dburton-IT595_Assignment-Unit10__Governance_.docx       # Full governance document
```

### Slide Deck
Covers the full project arc: background, medical imaging data lifecycle, threat landscape, benefits and risks of healthcare AI, governance frameworks, and final recommendations.

### Governance Document
The primary deliverable — a detailed policy and governance framework that includes:

- **Mock Patient Notice of AI Data Use** — transparency notice for all patients
- **Patient Consent for AI Training Data Use** — explicit authorization form
- **AI Diagnostic Assistance Disclaimer** — addresses biased/inaccurate output risk
- **HIPAA Business Associate Agreement (BAA) Template** — for third-party AI vendors
- **Organizational IT & Cybersecurity Policy Framework** — seven policies covering:
  - Policy 1: Role-Based Access Control (RBAC)
  - Policy 2: Account Usage Monitoring
  - Policy 3: Employee Training for Credential Security
  - Policy 4: Diverse Dataset Collection for AI Model Training
  - Policy 5: Explainable AI Output
  - Policy 6: Data Segmentation Between PHI and AI Training Data
  - Policy 7: Encryption of Medical Imaging Data

---

## 🏗️ Frameworks & Standards Referenced

| Framework | Application |
|---|---|
| **NIST Cybersecurity Framework (CSF)** | Core security controls for healthcare AI systems |
| **NIST AI Risk Management Framework (AI RMF 1.0)** | Flexible AI risk governance aligned to existing practices |
| **NIST SP 800-53** | Security and privacy controls, including AC-06 (Least Privilege) |
| **HIPAA** | U.S. federal patient data protection requirements |
| **HIPAA Business Associate Agreement** | Vendor data handling contracts |
| **Privacy by Design** | Data protections embedded throughout the AI system lifecycle |
| **FIPPs** | Fair Information Practice Principles — awareness, consent, and access |

---

## 💡 Key Recommendations

1. **Encrypt and segment PHI** from AI training datasets to reduce external attack surface
2. **Implement explainable AI output** with disclaimers to address algorithmic bias and build clinician trust
3. **Enforce role-based access and account monitoring** with mandatory security training to mitigate insider threat
4. **Require human-in-the-loop validation** — AI as decision support, not replacement for clinical judgment
5. **Execute HIPAA BAAs with all AI vendors** and conduct third-party risk assessments before deployment
6. **Adopt a multi-layered governance approach** combining technical safeguards, organizational policy, and patient transparency

---

## 👩‍💻 About the Author

I'm a cybersecurity professional with a somewhat unconventional path — I started in **Nuclear Medicine** (A.S.) before pivoting to security and earning my **M.S. in Cybersecurity Management** from Purdue University Global. That background gives me a first-hand appreciation for how sensitive medical imaging environments are, what's actually at stake when patient data is exposed, and why security controls need to be practical for clinical staff — not just technically sound.

This project is the first in what I'm building as an **AI/ML-focused security portfolio on GitHub**, reflecting my interest in the intersection of cybersecurity, healthcare, and responsible AI. More projects to come.

---

## 📚 Selected References

- Alder, S. (2026). *What Is A HIPAA Business Associate Agreement?* HIPAA Journal.
- Cavoukian, A. & Information and Privacy Commissioner of Ontario. (2011). *Privacy by design.*
- Chustecki, M. (2024). Benefits and risks of AI in healthcare: Narrative review. *Interactive Journal of Medical Research, 13*, e53616.
- Chu et al. (2020). The potential dangers of artificial intelligence for radiology and radiologists. *JACR, 17*(10), 1309–1311.
- National Institute of Standards and Technology. (2023). *AI Risk Management Framework (AI RMF 1.0).*
- Tegomoh, B. (2025). *The Physician AI Handbook: Peer-reviewed evidence for every specialty.*

---

*This project was completed as the Unit 10 capstone for IT595 at Purdue University Global. Horizon Valley Health System is a fictional organization created solely for academic purposes.*
