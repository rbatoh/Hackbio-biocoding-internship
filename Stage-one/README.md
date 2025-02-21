# HackBio Biocoding Internship - Stage One Task

## Overview

In this project, I implemented several functions to tackle various bioinformatics and computational biology tasks as part of the Stage One requirements for the HackBio Biocoding Internship. The tasks include translating DNA to protein, simulating and generating a logistic population growth curve, calculating the time to reach 80% of maximum growth (carrying capacity) and computing the Hamming distance between two usernames.

## Functions Implemented

### 1. DNA to Protein Translation

This function takes a DNA sequence as input and translates it into a protein sequence based on the genetic code. It processes the DNA sequence in codons (triplet nucleotides) and maps them to their corresponding amino acids.

### 2. Logistic Population Growth Simulation

The logistic growth model simulates population growth over time using the following parameters:
- **Carrying Capacity**: The maximum population size that the environment can sustain.
- **Growth Rate**: The intrinsic growth rate of the population.
- **Lag Phase Length**: A randomized duration for the lag phase of growth.
- **Exponential Phase Length**: A randomized duration for the exponential growth phase.

This function generates 100 different growth curves of 'Population Size vs Time' and stores them in a DataFrame, allowing for easy analysis and visualization.

### 3. Time to Reach 80% Growth

This function calculates the time required for a population to reach 80% of its carrying capacity, using the logistic growth equation. This provides insight into the growth dynamics of the simulated populations.

### 4. Hamming Distance Calculation

This function computes the Hamming distance between two strings (Slack username and twitter handle), which measures the difference between them by counting the positions at which the corresponding symbols are different. The function pads the shorter string with spaces to ensure both strings are of equal length before calculation.

## Files
To use the functions implemented in this project, you can import them into your Python environment.
The Python code for this project can found here:
Stage one task.ipynb

 
