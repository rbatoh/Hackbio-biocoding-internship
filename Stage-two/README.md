# HackBio Biocoding Internship - Stage 2 Task

## Overview
The project focused on various biological data analysis methods in microbiology, biochemistry & oncology, transcriptomics, and public health. Each task involves data analysis, visualization, and statistical testing.

## Task Descriptions & Implementations

### Task Code 2.1: Microbiology
**Objective:** Analyze growth curves for different strains and compare knock-out (-) and knock-in (+) strains.
**Dataset**: https://raw.githubusercontent.com/HackBio-Internship/2025_project_collection/refs/heads/main/Python/Dataset/mcgc.tsv
**This is the description of the Dataset**: https://github.com/HackBioInternship/2025_project_collection/blob/main/Python/Dataset/mcgc_METADATA.txt
- Plotted OD600 vs. Time growth curves for all strains.
- Determined the time to reach carrying capacity using a custom function.
- Generated scatter and box plots comparing carrying capacity times.
- Conducted statistical tests to compare knock-out and knock-in strains.

### Task Code 2.4: Biochemistry & Oncology
**Objective:** Investigate the functional and structural impact of mutations on proteins.
**Datasets Here**: https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/sift.tsv
                   https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/datasets/foldX.tsv               
- Imported and merged SIFT and FoldX datasets.
- Identified mutations affecting both structure and function.
- Determined amino acids with the most impact.
- Created frequency tables and visualizations (bar plot & pie chart).
- Analyzed structural and functional properties of high-impact amino acids.

### Task Code 2.6: Transcriptomics
**Objective:** Analyze gene expression data from an RNA-seq experiment.
**Dataset**: https://gist.githubusercontent.com/stephenturner/806e31fce55a8b7175af/raw/1a507c4c3f9f1baaa3a69187223ff3d3050628d4/results.txt
- Generated a volcano plot to visualize significant gene expression changes.
- Identified upregulated (Log2FC > 1, p-value < 0.01) and downregulated genes (Log2FC < -1, p-value < 0.01).
- Researched the functions of the top 5 upregulated and downregulated genes using GeneCards.

### Task Code 2.7: Public Health
**Objective:** Process and analyze NHANES health data.
**Dataset**: https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/nhanes.csv
**Data Dictionary**: https://github.com/HackBio-Internship/public_datasets/blob/main/R/nhanes_dd.csv
- Handled missing data appropriately.
- Created histograms for BMI, weight, weight in pounds, and age distributions.
- Calculated mean pulse rate, blood pressure range, variance, and standard deviation for income.
- Visualized weight vs. height relationships colored by gender, diabetes status, and smoking status.
- Conducted t-tests for:
  - Age and gender
  - BMI and diabetes
  - Alcohol consumption and relationship status

## Results & Interpretations
Each task script contains inline comments explaining observations and findings based on the data analysis performed.

## Contributing
Feel free to fork the repository and submit pull requests for improvements or additional analysis.




