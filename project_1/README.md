# NLP Text Classification – Project 1

## Overview

This project focuses on **NLP text classification** as part of the Machine Learning course. The main objectives are:

- Understand the dataset, including provenance, language, genres, and annotations.
- Perform **exploratory data analysis** with visualizations.
- Preprocess text and create feature representations, including **sparse (TF-IDF) and dense (word embeddings)**.
- Train and evaluate **traditional ML classifiers** (e.g., Naive Bayes, Logistic Regression, Decision Trees, Random Forest, SVM, MLP, XGBoost).
- Report results using **Precision, Recall, F1, Macro-F1**, and perform error analysis on misclassifications.
  
> **Note:** Deep learning architectures (CNNs, RNNs, Transformers) are **not allowed** in this assignment.

## Project Structure

```
project/
├── data/                # Raw datasets
├── data_prepared/       # Preprocessed datasets ready for modeling
├── project.ipynb        # Main notebook with preprocessing, modeling, and evaluation
├── requirements.txt     # Required Python libraries
├── README.md            # This file
├── presentation.pdf     # Assignment presentation
└── .gitignore
````

## Setup

1. Ensure you are running **Python 3.12.x**  

2. Create a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows
````

3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Open the main notebook:

```bash
jupyter notebook project.ipynb
```

## How to Use

1. Activate the virtual environment.
2. Open `project.ipynb` in Jupyter Notebook.
3. Follow the notebook step by step:

   * Load and explore `data/`
   * Preprocess and transform text into features
   * Train classifiers and evaluate results
   * Perform error analysis and generate reports/plots

> All necessary code and explanations are included in the notebook.
