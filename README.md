# Titanic Survival Prediction Project

This project applies supervised machine learning techniques to predict passenger survival on the Titanic based on various features.

## 🚀 Project Goals
- Perform exploratory data analysis (EDA)
- Preprocess data and engineer features
- Train and evaluate different ML models (e.g., Logistic Regression, Random Forest, XGBoost)
- Optimize model performance
- Share findings and business insights

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📂 Project Structure
- `data/` - Processed dataset (only small files if needed)
- `notebooks/` - EDA and model development
- `scripts/` - Scripts for data preprocessing and modeling
- `models/` - Trained model files
- `README.md` - Project overview and results

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
- Historical Results are tracked against Insight.md file

## 📚 Acknowledgments
- Dataset from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview)

## 📝 License
This project is licensed under the [MIT License](LICENSE).
