# NLP Text Classification – Project 1

## 📌 Project Overview

Traditional **NLP text classification** using machine learning classifiers.

**Objectives:**

* Explore the dataset: provenance, language, genres, annotations
* Preprocess text and create **sparse (TF-IDF) and dense (word embeddings)** features
* Train and evaluate **ML classifiers**: Naive Bayes, Logistic Regression, Decision Trees, Random Forest, SVM, MLP, XGBoost
* Evaluate using **Precision, Recall, F1, Macro-F1**
* Perform **error analysis** on misclassifications

> Deep learning architectures (CNNs, RNNs, Transformers) were **not used** in this assignment.

## 🗂 Project Structure

```
project/
├── data/                # Raw datasets
├── data_prepared/       # Preprocessed datasets ready for modeling
├── project.ipynb        # Main notebook with preprocessing, modeling, and evaluation
├── requirements.txt     # Required Python libraries
├── README.md            # This file
├── presentation.pdf     # Assignment presentation
└── .gitignore
```

## ⚙ Setup

1. Ensure **Python 3.12.x** is installed

2. Create a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Open the main notebook:

```bash
jupyter notebook project.ipynb
```

## 🚀 How to Use

1. Activate the virtual environment
2. Open `project.ipynb` in Jupyter Notebook
3. Follow the notebook sequentially:

   - Load and explore `data/`
   - Preprocess and transform text into features
   - Train classifiers and evaluate results
   - Perform error analysis and generate plots/reports

> All code and explanations are included in the notebook.

## 🛠 Technologies Used

| Technology               | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| **Python**               | Scripting and data manipulation           |
| **Scikit-learn**         | Traditional ML classifiers and evaluation |
| **Jupyter Notebook**     | Interactive coding and documentation      |
| **Pandas & NumPy**       | Data preprocessing and handling           |
| **Matplotlib & Seaborn** | Visualizations and EDA                    |
