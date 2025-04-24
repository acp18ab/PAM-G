# Predictive Activity Modelling of Glucose (PAM-G)

This repository contains data and analysis code for the study titled **"Predictive Activity Modelling of Glucose (PAM-G): A Study of Type 1 Diabetes in Free-Living."** The study aims to model the effect of physical activity (PA) on blood glucose (BG) dynamics in individuals with Type 1 Diabetes Mellitus (T1DM) under real-life, unsupervised conditions, using retrospective clinical data and statistical techniques.

---

## 🔍 Overview

### 🧠 Background

PA significantly impacts glycemic control in T1DM, often inducing hypoglycemia depending on activity intensity and duration. This project presents a data-driven model that:
- Quantifies the effects of **non-standard PA** on BG levels.
- Uses **gradient analysis** to evaluate changes in BG following different levels of activity.
- Builds two predictive hypotheses for BG drop timing and intensity.

### 📈 Hypotheses Tested
1. **Hypothesis 1:** A further decline in BG gradient is expected following a period of non-standard PA when BG is already falling.
2. **Hypothesis 2:** Even when BG is initially rising, non-standard PA can result in a delayed BG drop.

---

## 🧪 Methods

- **Participants:** 8 individuals with T1DM, 60+ years of age, in free-living conditions.
- **Devices:**
  - PA: Philips Actiwatch (Activity Counts)
  - BG: Dexcom G6 CGM
- **Time Series Intervals:** Resampling PA and BG at 20, 40, and 60 minutes.
- **Analysis Techniques:**
  - Gradient calculation for PA and BG
  - Confusion matrix to evaluate prediction accuracy
  - Custom algorithms to detect BG trends post-PA

---

## 📁 Repository Contents

```
PAM-G/
├── IDxxxx.ipynb/            # Individual participant analysis
├── IDxxxx.csv/              # Individual participant Activity Data
├── IDxxxxGlucose.txt        # Individual participant Glucose Data
├── final_results.xlsx       # Analysis Results
└── README.md                # This file
```

---

## 🚀 Getting Started

### 🔧 Clone the Repository

```bash
git clone https://github.com/acp18ab/PAM-G.git
cd PAM-G
```

### 💻 Requirements

- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📄 How to Use

1. Run each ID to generate gradient plots and evaluate predictions.
2. Change the interval (20/40/60 minutes) inside the notebook for various test conditions.
3. Confusion matrices and performance metrics will appear automatically.

---

## ✅ Key Results

- **Accuracy (Hypothesis 1):** 83% – 100% across participants
- **Sensitivity:** Up to 100% for PA-induced hypoglycemia detection
- **Precision and Specificity** varied based on individual physiology and activity variability

---

## 📚 Citation

Please cite the following if you use this work:

> Ahmad Bilal et al., *Predictive Activity Modelling of Glucose (PAM-G): A Study of Type 1 Diabetes in Free-Living*, The University of Manchester, 2024.

---

## 📬 Contact

**Ahmad Bilal**  
📧 [ahmad.bilal@manchester.ac.uk](mailto:ahmad.bilal@manchester.ac.uk)  
🔗 [Research Profile](https://www.research.manchester.ac.uk/en/persons/ahmad.bilal)

---
