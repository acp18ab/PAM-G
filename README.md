# Predictive Activity Modelling of Glucose (PAM-G)

This repository contains the data and analysis code for the study titled **"Predictive Activity Modelling of Glucose (PAM-G): A Study of Type 1 Diabetes in Free-Living."** The research explores the impact of daily physical activity on blood glucose (BG) levels in individuals with Type 1 Diabetes Mellitus (T1DM), offering a replicable framework for predicting BG changes during and after physical activity.

## Key Highlights

- **Paper Overview**:  
  The study demonstrates a reliable correlation between increased physical activity levels and changes in BG. Retrospective data from eight participants were analyzed to improve insulin dosage and carbohydrate adjustments, minimizing hypoglycemia risk.

- **Analysis Approach**:  
  - The `confusion_matrix.ipynb` notebook performs the data analysis.  
  - By providing overall physical activity levels with ±x thresholds and analyzing each day separately, a confusion matrix is generated to evaluate the prediction accuracy of BG changes.  
  - The notebook includes predictions over 20-, 40-, and 60-minute intervals using two tested hypotheses.

## Repository Contents
- **Data**: Contains retrospective activity and glucose data for eight participants.  
- **Code**: Python scripts and Jupyter Notebook files for reproducing the analysis.  

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/acp18ab/PAM-G.git
   cd PAM-G
2. Open confusion_matrix.ipynb in Jupyter Notebook to explore the analysis.
