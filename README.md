# Sonar Rock vs Mine

## Repository Description

This project implements a machine learning model to classify sonar signals as either **rocks** or **mines**. The dataset consists of sonar returns bounced off different surfaces, where each sample is represented by multiple numerical features corresponding to signal energy at various frequencies.

The goal is to build a predictive model capable of distinguishing between metallic objects (mines) and natural formations (rocks) based on sonar data. The project includes data preprocessing, exploratory data analysis, model training, and evaluation.

---

## Key Features

- Data cleaning and normalization  
- Feature analysis and visualization  
- Implementation of classification model: **Logistic Regression**  
- Model evaluation using accuracy  
- Simple and beginner-friendly structure  

---

## Project Structure
```bash
.
├── rock_vs_mine.ipynb # Main Jupyter Notebook (core project)
├── requirements.txt # Dependencies
└── README.md
```

> Note: Only the **Jupyter Notebook (`rock_vs_mine.ipynb`)** is included in this repository.

---

## Setup Project

### 1. Create and activate virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 2. Options:

#### Option 1: Run with Jupyter Notebook (Recommended)
##### Install Jupyter:
```bash
pip install notebook
```
##### Launch Jupyter:
```bash
jupyter notebook
```

##### Then open: rock_vs_mine.ipynb

#### Option 2: Convert to Python Script

If you prefer running a .py file:

##### Convert notebook to script:
```bash
jupyter nbconvert --to script rock_vs_mine.ipynb
```
##### This will generate:
rock_vs_mine.py
##### Run the script:
```bash
python3 rock_vs_mine.py
```