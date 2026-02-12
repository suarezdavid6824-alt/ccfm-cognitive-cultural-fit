# ccfm-cognitive-cultural-fit

Hybrid psychometric + NLP system for cognitive–cultural person–organization fit analysis



# Cognitive–Cultural Fit Model (CCFM)
**A Hybrid Psychometric and NLP/LLM Framework for Person–Organization Fit**

This repository contains the research prototype of the **Cognitive–Cultural Fit Model (CCFM)**, an interdisciplinary system that integrates:

- Psychometric latent scoring (θ)
- Narrative-based assessment using NLP and Large Language Models
- Controlled fusion of quantitative and linguistic signals
- Explainable and prescriptive reporting

The model is designed as a **decision-support tool** for organizational contexts such as:

Selection, onboarding, role design, and cultural risk monitoring.

---

## Academic Paper

The full academic paper describing the theoretical framework, methodology, system architecture, and proof of concept is available in:

paper/
└─ CCFM_Paper_Suarez_2026.pdf

---

## Repository Structure
notebooks/
└─ CCFM_full_pipeline.ipynb # End-to-end working pipeline

outputs/
├─ figure1_radar_demo.png # Example radar visualization
└─ fit_report_demo.pdf # Example generated report

src/
└─ Core modules (fusion, scoring, report builder)

assets/
└─ Figures and diagrams

---

## Demo Notebook

The main demonstration notebook is:

notebooks/CCFM_full_pipeline.ipynb

It implements:

- Psychometric scoring
- NLP + LLM inference
- Hybrid fusion
- Evidence extraction
- Compatibility computation
- Automated report generation

Running the notebook reproduces the full analytical pipeline.

---

## Setup (Local Execution)

### 1. Create virtual environment
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

### 2. Install dependencies

pip install -r requirements.txt

### 3. Run the notebook
Open Jupyter and execute:
notebooks/CCFM_full_pipeline.ipynb
Run cells sequentially.

## Outputs
The system generates:

- Standardized latent scores by dimension
- Person–Organization compatibility indices
- Radar chart visualizations
- Evidence traceability blocks
- Actionable recommendations
- Reports in Markdown and PDF/DOCX formats
Example outputs are provided in the outputs/ folder.

##Notes
- Current demonstrations are based on synthetic and simulated profiles.
- The system is intended for research and decision support purposes.
- It is not designed for automated exclusion.

##Author
David Suárez
Team Success Manager (Ecuador)
Research prototype for MSc applications in Cognitive Science and AI

##License
Code: MIT License (recommended)
Paper: Academic use only