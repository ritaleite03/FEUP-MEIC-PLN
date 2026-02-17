# NLP Text Classification with Transformers – Project 2

## 📌 Project Overview

Follow-up to **Project 1**, using **Hugging Face Transformers** to improve text classification performance.

**Objectives:**

- Select a **pre-trained transformer model** suitable for the dataset
- Fine-tune the model for text classification
- Optionally explore **domain adaptation, parameter-efficient fine-tuning (LoRA), or prompting**
- Compare transformer results with traditional ML models from Project 1

## 🗂 Project Structure

```
project_2/
├── data/                     # Raw datasets
├── results/                  # Model checkpoints and evaluation results
│   └── checkpoint-504/
├── project.ipynb             # Main notebook for preprocessing, fine-tuning, and evaluation
├── requirements.txt          # Required Python libraries
├── presentation.pdf          # Assignment presentation
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

   * Load and preprocess `data/`
   * Fine-tune the selected transformer model
   * Evaluate performance and generate predictions
   * Compare results with traditional ML models from Project 1

> All code, explanations, and results are contained within the notebook.

## 🛠 Technologies Used

| Technology                    | Purpose                                 |
| ----------------------------- | --------------------------------------- |
| **Python**                    | Scripting and workflow orchestration    |
| **Hugging Face Transformers** | Pre-trained models and fine-tuning      |
| **Scikit-learn**              | Baseline traditional ML models          |
| **Jupyter Notebook**          | Interactive coding and documentation    |
| **Pandas & NumPy**            | Data preprocessing and feature handling |
| **Matplotlib & Seaborn**      | Visualizations and evaluation plots     |
