# Datamining_Class_Project_Keith_Crabb

Exploratory Data Analysis of the **Electric Transmission System Cyber Attack Dataset** (UAH / Oak Ridge National Lab)

## Overview

This repository contains a comprehensive Jupyter notebook performing EDA on the multiclass version of the **Power System Cyber Attack Dataset**. The analysis focuses on:

- Dataset structure and loading (ARFF format)
- Data cleaning and quality checks
- Class distribution and imbalance analysis
- Feature statistics and correlations
- Visualizations (class distribution, voltage histograms, correlation heatmaps, temporal patterns)
- Outlier detection and initial insights

The notebook is designed for researchers and students studying **anomaly detection** in critical operational technology (OT) infrastructure, particularly U.S. electric transmission systems.

## Dataset

**Electric Transmission System Cyber Attack Dataset**  
- Source: [Tommy Morris / UAH](https://sites.google.com/a/uah.edu/tommy-morris-uah/ics-data-sets)
- Format: 15 sampled ARFF files (multiclass.7z)
- Size (full): ~78k rows × 129 columns
- Content: Synchrophasor measurements (PMUs), relay logs, Snort alerts, and 37 scenario labels (normal, disturbances, cyber attacks)

## Features

- Automated download & extraction of multiclass.7z
- Loading and decoding of ARFF files
- Missing value & outlier analysis (z-score)
- Class imbalance visualization
- Feature correlation heatmap
- Temporal pattern exploration
- Full dataset concatenation option
- Well-documented code with algorithmic justifications

## Usage

### Option 1: Open in Google Colab (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/power_system_cyber_attack_eda.ipynb)

### Option 2: Local Run
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook Power_System_Cyber_Attack_EDA.ipynb
