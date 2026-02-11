# NLP Text Classification with Transformers – Project 2

---

## Overview

This is **Project 2** of the NLP text classification assignment, following up on Project 1.  

The goal is to **employ Hugging Face Transformers** to improve performance on the same text classification task as in the first assignment. The main objectives are:

- Select a **pre-trained transformer model** suitable for the task’s language and genre.  
- Fine-tune the model for the classification task.  
- Optionally explore **domain adaptation, parameter-efficient fine-tuning (e.g., LoRA), or prompting**.  
- Compare the performance of the transformer model(s) with traditional ML classifiers from Project 1.  

---

## Project Structure

```
project_2/
├── data/                     # Raw datasets
├── results/                  # Model checkpoints and results
│   └── checkpoint-504/
├── project.ipynb             # Main notebook for preprocessing, fine-tuning, and evaluation
├── requirements.txt          # Required Python libraries
├── presentation.pdf          # Assignment presentation
└── .gitignore
````

---

## Setup

1. Ensure you are running **Python 3.12.x**.  

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

---

## How to Use

1. Activate the virtual environment.
2. Open `project.ipynb` in Jupyter Notebook.
3. Follow the notebook step by step:

   * Load and preprocess `data/`
   * Fine-tune the selected transformer model
   * Evaluate model performance and generate predictions
   * Compare with traditional ML models from Project 1

> All code, explanations, and results are contained within the notebook.
