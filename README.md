# 🚢 Titanic Survival Prediction Project

This project applies supervised machine learning techniques to predict passenger survival on the Titanic based on a variety of passenger attributes.

---

## 🎯 Project Goals

- Perform thorough Exploratory Data Analysis (EDA)
- Preprocess and clean the dataset
- Engineer meaningful features to boost model performance
- Train and evaluate multiple ML models (Logistic Regression, Random Forest, XGBoost)
- Compare model performance using cross-validation and Kaggle submissions
- Share findings and insights through visualizations and documented conclusions

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- XGBoost
- Jupyter Notebook

---

## 📁 Project Structure

```text
├── data/         # Processed dataset (small files only)
├── notebooks/    # Jupyter notebooks (EDA, modeling, experimentation)
├── models/       # Trained model artifacts (optional)
├── requirements.txt
├── Insights.md   # Detailed performance evaluations and model comparisons
└── README.md     # Project overview and setup instructions
```

## 🔧 Environment Setup / Installation Guide

Follow the steps below to set up your development environment.

### 1. Install Homebrew 

#### For macOS

Run the following command in the terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once installed, add Homebrew to your shell profile (if not already added):

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

#### For Windows
Homebrew is not supported natively on Windows, but works in WSL. 

You can also skip Homebrew and install Python directly using the official installer if you’re not using WSL.


```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once installed, add Homebrew to your shell profile (if not already added):

```bash
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```

#### For Linux / Debian / Ubuntu

Run the following command in the terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once installed, add Homebrew to your shell profile (if not already added):

```bash
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```

### 2. Install Python

```bash
brew install python
```

### 3. Install CMake, a prerequisite for XGBoost

```bash
brew install cmake
```

### 4. Install XGBoost and all other required packages

```bash
pip install -r requirements.txt
```

## 📈 Results
Final model evaluations, cross-validation scores, and Kaggle leaderboard results are documented in:

➡️ [Insight.md](Insights.md)

## 📚 Acknowledgments
- Dataset from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview)

## 🤖 AI Assistance

Some parts of this project (including code structuring, statistical explanations, and documentation) were guided using ChatGPT as a learning assistant to accelerate understanding and ensure best practices. All modeling decisions, analysis, and validation were reviewed and implemented manually.

## 📝 License
This project is licensed under the [MIT License](LICENSE).
