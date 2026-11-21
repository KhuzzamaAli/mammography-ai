# mammography-ai
# Mammography AI — Subtype & External Generalization Study

## Project Overview
This repository supports graduate research and coursework in **BME 790** (Biomedical Engineering) at the Hashemite University. It investigates deep learning performance for breast cancer detection on digital mammography across molecular and histologic cancer subtypes, focusing on subgroup sensitivity, calibration, and external generalization.

## Data Used
The planned analysis uses open-access mammography resources, primarily the **Chinese Mammography Database (CMMD)** (biopsy-confirmed breast cancer cases with recorded subtypes) alongside public screening mammography benchmarks and literature screening records (PubMed, Scopus, and IEEE Xplore). Patient-level splitting is emphasized to prevent data leakage across multiple views or exams.

## How to Run the Analysis
1. Clone the repository locally:
   `git clone https://github.com/KhuzzamaAli/mammography-ai.git`
2. Navigate into the project directory:
   `cd mammography-ai`
3. Create and activate a dedicated Python environment, install the required packages listed below, and run the subtype evaluation scripts or notebooks once configured with the local CMMD dataset path.

## Software and Versions Needed
- **Python**: 3.10+
- **PyTorch**: 2.x (with `torchvision`) for pretrained mammography inference
- **Scientific & Data Stack**: `numpy` (>= 1.24), `pandas` (>= 2.0), `scikit-learn` (>= 1.3), `pydicom` (>= 2.4)
- **Reference & Note Management**: Zotero 7, Microsoft Word, and Microsoft OneNote for literature tracking and research logs

## Contact
- **Author**: Khuzzama Al-Dabaibah (MSc Student in Biomedical Engineering, Hashemite University)
- **Email**: khuzzamaali@gmail.com
- **ORCID iD**: `0009-0008-9975-940X`
- **LinkedIn**: `https://www.linkedin.com/in/khuzzamaaldabaibah00`








