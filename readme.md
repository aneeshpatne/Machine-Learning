# 🤖 Machine Learning Algorithms & Data Science

> A comprehensive collection of hands-on Jupyter notebooks showcasing machine learning algorithms, data preprocessing techniques, and real-world applications with practical implementations.

## 🎯 Overview

This repository contains **40+ Jupyter notebooks** covering essential machine learning concepts from basic data preprocessing to advanced algorithms. Each notebook includes complete implementations with real datasets, making it perfect for learning, reference, or teaching machine learning concepts.

## 📊 What's Inside

### 🔧 **Data Preprocessing & Engineering**

| Category                | Notebooks                                          | Description                                          |
| ----------------------- | -------------------------------------------------- | ---------------------------------------------------- |
| **Data Cleaning**       | `NaN handling/`                                    | Imputation techniques, missing value treatment       |
| **Feature Engineering** | `OneHotEncoding/`, `Feature Scaling/`              | Categorical encoding, normalization, standardization |
| **Data Analysis**       | `Data Correlation/`, `selectionANDFiltering.ipynb` | Correlation analysis, feature selection              |
| **Data Splitting**      | `Data Splitting/`                                  | Train-test split strategies                          |

### 🧠 **Machine Learning Algorithms**

#### **Supervised Learning**

| Algorithm                         | Applications                                              | Datasets                                                    |
| --------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- |
| **Linear Regression**             | Salary prediction, Beer consumption, Insurance claims     | `Salary_Data.csv`, `Beer_data.csv`, `insurance.csv`         |
| **Polynomial Regression**         | Non-linear relationships, Complex patterns                | `Beer_data.csv`, `insurance.csv`                            |
| **Decision Trees**                | Classification & Regression                               | `seeds.csv`, `Position_Salaries.csv`, `heart.csv`           |
| **Random Forest**                 | Drug classification, Hair loss prediction, Housing prices | `drug200.csv`, `hair_loss.csv`, `housing_price_dataset.csv` |
| **SVM & Support Vector Machines** | Position salary prediction, Seed classification           | `Position_Salaries.csv`, `seeds.csv`, `heart.csv`           |
| **K-Nearest Neighbors (KNN)**     | Heart disease classification, Pattern recognition         | `heart.csv`, `seeds.csv`                                    |
| **Naive Bayes**                   | Probabilistic classification                              | `seeds.csv`, `heart.csv`                                    |
| **XGBoost**                       | Gradient boosting for complex predictions                 | `hair_loss.csv`                                             |

#### **Unsupervised Learning**

| Technique                              | Purpose                                      | Implementation                      |
| -------------------------------------- | -------------------------------------------- | ----------------------------------- |
| **Principal Component Analysis (PCA)** | Dimensionality reduction, Feature extraction | `DimentionalityReduction/PCA.ipynb` |

## 🗂️ **Real-World Datasets**

The repository includes diverse datasets for practical learning:

- **Healthcare**: Heart disease classification, Drug effectiveness
- **Business**: Startup success prediction, Housing price estimation
- **Personal**: Hair loss analysis, Beer consumption patterns
- **Agricultural**: Seed classification, Crop analysis
- **Financial**: Insurance claims, Salary predictions

## 🚀 **Quick Start**

### Prerequisites

- Python 3.7+
- Jupyter Notebook

### Installation

1. **Clone the repository:**

```powershell
git clone https://github.com/aneeshpatne/Machine-Learning.git
cd Machine-Learning
```

2. **Install dependencies:**

```powershell
pip install jupyter pandas numpy scikit-learn matplotlib seaborn xgboost
```

3. **Launch Jupyter Notebook:**

```powershell
jupyter notebook
```

### 📋 **Required Libraries**

```python
# Core libraries used across all notebooks
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Machine Learning
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler, LabelEncoder, OneHotEncoder
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestClassifier, RandomForestRegressor
from sklearn.tree import DecisionTreeClassifier
from sklearn.svm import SVC, SVR
from sklearn.neighbors import KNeighborsClassifier
from sklearn.naive_bayes import GaussianNB
import xgboost as xgb
```

## 🎓 **Learning Path**

### **Beginner Track**

1. Start with `basics.ipynb` for fundamental concepts
2. Explore `Data Splitting/` for understanding train-test splits
3. Practice with `Linear Regression/salary.ipynb`
4. Learn preprocessing with `OneHotEncoding/` and `Feature Scaling/`

### **Intermediate Track**

1. Decision Trees (`Decision Tree/DT.ipynb`)
2. Random Forest implementations
3. K-Nearest Neighbors applications
4. Support Vector Machines

### **Advanced Track**

1. XGBoost for gradient boosting
2. Principal Component Analysis
3. Complex feature engineering
4. Model ensemble techniques

## 📈 **Key Features**

- ✅ **Complete Implementations**: Every notebook includes end-to-end machine learning pipelines
- ✅ **Real Datasets**: Work with actual data from various domains
- ✅ **Evaluation Metrics**: Comprehensive model evaluation with accuracy, precision, recall, F1-score
- ✅ **Visualizations**: Rich plots and graphs for data understanding
- ✅ **Best Practices**: Proper data splitting, feature scaling, and validation techniques
- ✅ **Comparative Analysis**: Multiple algorithms applied to same datasets

## 🔍 **Notebook Structure**

Each notebook follows a consistent structure:

```
📋 Problem Definition
📊 Data Loading & Exploration
🔧 Data Preprocessing
🎯 Model Implementation
📏 Training & Evaluation
📈 Results Visualization
💡 Key Insights
```

## 📸 **Sample Results**

The repository includes visualization examples in the `img/` directory showing:

- Model performance comparisons
- Data distribution plots
- Confusion matrices
- Feature importance charts

---

💡 **Perfect for**: Students, Data Science enthusiasts, ML practitioners, and anyone looking to understand machine learning through practical implementations.
