# Euphemisms attenuate norm violations: an EEG study

Project Description
This repository contains the data analysis code used in the study of neurocognitive mechanisms underlying the perception of euphemized descriptions of norm violations. The study utilized ERP components (N400, P600) to examine brain responses to euphemisms and non-euphemized terms.

Study Goals
Investigate how euphemisms influence behavioral evaluations and brain activity.
Explore differences in ERP components for euphemized and non-euphemized descriptions.
Assess the role of individual cognitive traits in the perception of euphemisms.
Repository Structure
plaintext
Копировать код
/BEHanalysis.ipynb       # Jupyter Notebook for behavioral data analysis
/ERPanalysis.ipynb       # Jupyter Notebook for ERP data analysis
/data/
/results/                # Results: plots, tables, and other outputs
/README.md               # Project description
/LICENSE                 # License information
Key Findings
Behavioral Results: Euphemisms reduced the perceived severity of norm violations.
ERP Results:
P600 was more pronounced for non-euphemized descriptions.
N400 showed no significant differences between conditions.
Individual Differences: No significant correlation was found between Need for Cognition and responses to euphemisms.
Usage
Installation
Clone the repository:
bash
Копировать код
git clone https://github.com/username/repository-name.git
Install dependencies:
bash
Копировать код
pip install -r requirements.txt
Running the Analysis
Behavioral Analysis:
Open BEHanalysis.ipynb and execute all cells to process behavioral data.
ERP Analysis:
Open ERPanalysis.ipynb and execute all cells to process ERP components.
Reproducibility
EEG data were recorded using a 64-channel EEG system (BRAINAMP DC).
Data preprocessing (filtering, ICA, artifact correction) was performed using MNE-Python.
The experimental design and stimulus materials are detailed in the supplementary materials.
License
This repository is distributed under the MIT License. See LICENSE for details.
