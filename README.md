# ENGR 5005: Machine Learning for Engineering Applications

## Coding Project: Machine Learning Model Comparisons on Real-World Datasets

This project evaluates and compares different machine learning models (KNN, Decision Trees, Logistic Regression, Linear Regression, Bayesian Classifier) on various datasets like Breast Cancer, Mushroom, Robot Failures, Obesity, and more.

---

## Project Structure

```plaintext
Code Project/
├── dataset/                         # Datasets
│   ├── Breast_Cancer_Dataset/
│   │   └── wdbc.data
│   ├── Car_Evaluation_Dataset/
│   │   └── car.data
│   ├── Robot_Execution_Failures_Dataset
│   │   ├── lp1.data
│   │   ├── lp2.data
│   │   ├── lp3.data
│   │   ├── lp4.data
│   │   └── lp5.data
│   ├── Mushroom_Dataset/
│   │   └── agaricus-lepiota.data
│   ├── Spambase_Dataset/
│   │   └── spambase.data
├── Scripts/                    # Jupyter notebooks for each dataset
│   ├── Breast_Cancer_ML.ipynb
│   ├── Car_Evaluation_ML.ipynb
│   ├── Mushroom_ML.ipynb
│   ├── Robot_Execution_Failures_LP1_ML.ipynb
│   ├── Robot_Execution_Failures_LP2_ML.ipynb
│   ├── Robot_Execution_Failures_LP3_ML.ipynb
│   ├── Robot_Execution_Failures_LP4_ML.ipynb
│   ├── Robot_Execution_Failures_LP5_ML.ipynb
│   └── Spambase.ipynb
├── FinalReport.docx              # Report File
├── README.md                     # Where you are right now
├── requirements.txt              # Python dependencies
└── results.txt                   # Results of Efficiencies of each model

```

---

## 🚀 Getting Started

### 1. Install Python

- Download Python from [https://www.python.org/downloads](https://www.python.org/downloads)
- During installation, **check the box to "Add Python to PATH"**

### 2. Install Jupyter Notebook

Use `pip` (Python’s package manager) in your terminal or command prompt:

```bash
pip install notebook
```

---

## 🛠 How to Use

1. **Navigate to the project folder**  
   Open a terminal and change directory to the project folder:
   ```bash
   cd path/to/CodingProject
   ```
2. **Install required libraries**  
   On the terminal run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open any notebook from `Scripts/` folder**  
   Run each cell step-by-step.

---

## ⚠️ Notes

- **KNN** and **Decision Tree** models may take longer to execute due to loops trying different `k` values or `max_depth` values.
- If you want faster execution, feel free to modify the loops to use a fixed value (e.g., `k = 3` or `max_depth = 5`).
- Datasets like those in the `robot/` folder support dynamic switching by just changing the filename at the top of the notebook.

---

## 📥 Installing Dependencies

If you're using your own Python environment:

```bash
pip install -r requirements.txt
```
