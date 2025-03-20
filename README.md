# ADHD Brain Activity Pattern Analysis - WiDS Datathon 2025

## Project Overview
A machine learning project for the WiDS Datathon Global Challenge, developed in collaboration with Ann S. Bowers Women's Brain Health Initiative (WBHI), Cornell University, and UC Santa Barbara. The project aims to predict ADHD diagnosis and biological sex using functional brain imaging data.

## Challenge Objective
To build a multi-outcome prediction model that:
1. Predicts ADHD diagnosis (Yes/No)
2. Predicts biological sex (Female/Male)
3. Analyzes brain activity patterns associated with ADHD across different sexes

## Dataset
The dataset is provided by:
- Healthy Brain Network (HBN)
- Child Mind Institute
- Reproducible Brain Charts project (RBC)

Data includes:
- Functional brain imaging data
- Socio-demographic information
- Emotional assessments
- Parenting information

## Project Structure
```
widsdatathon2025/
├── data/              # Data storage
│   ├── raw/          # Original, immutable data
│   └── processed/    # Cleaned and processed data
├── notebooks/        # Jupyter notebooks for analysis
├── src/             # Source code
│   ├── data_preprocessing/  # Data cleaning scripts
│   ├── features/           # Feature engineering code
│   └── models/            # Model training and evaluation
├── requirements.txt       # Project dependencies
└── README.md             # Project documentation
```

## Getting Started
1. Clone this repository
2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
[To be added as project develops]

## Contributors
[Your name and team members]

## Acknowledgments
- WiDS Datathon Global Challenge
- Ann S. Bowers Women's Brain Health Initiative
- Cornell University
- UC Santa Barbara
- Healthy Brain Network
- Child Mind Institute
