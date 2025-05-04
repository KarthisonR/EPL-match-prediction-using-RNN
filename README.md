# ⚽ EPL Match Prediction Using RNN

This project uses a Recurrent Neural Network (RNN) to predict the outcomes of English Premier League (EPL) football matches. By analyzing historical match data, the model aims to forecast whether a match will result in a home win, draw, or away win.

---

## 📁 Repository Contents

- `EPL match prediction notebook.ipynb` - Jupyter Notebook with the complete pipeline: preprocessing, modeling, training, and evaluation.
- `dataset.csv` - Dataset of historical EPL match data.
- `model.h5` - Saved trained RNN model.
- `README.md` - Project overview and usage guide (this file).

---

## 📊 Dataset Overview

The dataset includes historical match data with the following typical features:

- `Date`: Match date
- `HomeTeam`, `AwayTeam`: Teams involved
- `FTHG`, `FTAG`: Full-time home/away goals
- `FTR`: Full-Time Result (H = Home Win, D = Draw, A = Away Win)
- Other features: may include shots, possession, odds, etc.

> Note: Dataset structure may vary.

---

## 🧠 Model Architecture

The RNN model includes:

- **Embedding Layer**: Encodes categorical data
- **LSTM/GRU Layer**: Captures sequential dependencies
- **Dense Layers**: For classification
- **Output Layer**: Softmax for multi-class prediction (H/D/A)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/KarthisonR/EPL-match-prediction-using-RNN.git
cd EPL-match-prediction-using-RNN
