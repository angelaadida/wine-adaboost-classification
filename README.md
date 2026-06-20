# 🍷 Wine Classification — AdaBoost Classifier

Multi-class classification project using **AdaBoost** to classify wines into 3 categories based on 13 chemical properties — achieving **92% accuracy**.

---

## 🎯 Problem Statement

Given 13 chemical features of wine samples, classify each wine into one of 3 classes (0, 1, 2) representing different wine cultivars.

- **Dataset**: Scikit-learn Wine Dataset
- **Samples**: 178 records, 13 features
- **Classes**: 3 wine cultivars
- **Train/Test split**: 80/20

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| `alcohol` | Alcohol content |
| `malic_acid` | Malic acid content |
| `ash` | Ash content |
| `alcalinity_of_ash` | Alcalinity of ash |
| `magnesium` | Magnesium content |
| `total_phenols` | Total phenols |
| `flavanoids` | Flavanoids |
| `nonflavanoid_phenols` | Non-flavanoid phenols |
| `proanthocyanins` | Proanthocyanins |
| `color_intensity` | Color intensity |
| `hue` | Hue |
| `od280/od315_of_diluted_wines` | OD280/OD315 ratio |
| `proline` | Proline content |

---

## 🔄 ML Pipeline

### 1. EDA
- Dataset exploration (shape, info, describe)
- Missing value check — no missing values
- Correlation heatmap
- Feature distributions

### 2. Preprocessing
- 80/20 train/test split
- StandardScaler normalization

### 3. Model: AdaBoost Classifier
```
Parameters:
  random_state : 42
```

---

## 🏆 Results

| Metric | Score |
|--------|-------|
| **Accuracy** | **92%** |
| R² Score | 0.86 |
| MSE | 0.08 |
| MAE | 0.08 |

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Model | Scikit-learn (AdaBoostClassifier) |
| Evaluation | Accuracy Score, Confusion Matrix, Classification Report |
| Preprocessing | StandardScaler |

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open `Adaboost_classifier_week6_1.ipynb` in Jupyter Notebook and run all cells.

> Dataset loaded from `sklearn.datasets.load_wine()` — no download needed.

---

## 📁 Project Structure

```
wine-adaboost-classification/
│
├── Adaboost_classifier_week6_1.ipynb   # Main notebook
└── README.md
```

---

## 👩‍💻 Author

**Angela** — Data Scientist | AI • ML • GenAI • RAG  
📍 Kuala Lumpur, Malaysia  
🔗 [GitHub](https://github.com/angelaadida)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
