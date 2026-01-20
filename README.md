# 🎯 Job Seniority Prediction: ML Pipeline for Career Intelligence

Supervised learning classifier predicting job seniority levels from posting content with 74% accuracy.

**[📓 View Full Analysis Notebook](job-seniority-prediction.ipynb)**

---

## 📊 Project Overview

Built an end-to-end ML pipeline to predict job seniority (Entry/Mid/Senior/Lead) from **3,794 real job postings** using NLP feature engineering and ensemble methods.

**Key Achievement:** 74% accuracy — 18 points above baseline

**Business Value:**
- Job seekers: Auto-filter postings for realistic matches
- Recruiters: Benchmark requirements against market standards
- Career coaches: Identify skill gaps for advancement

---

## 🎯 Results Summary

| Model | Accuracy | F1-Score |
|-------|----------|----------|
| **Random Forest** | **74%** | **0.73** |
| Gradient Boosting | 73% | 0.72 |
| Neural Network | 72% | 0.71 |
| SVM | 70% | 0.69 |
| Baseline (Majority Class) | 56% | - |

**Top Predictive Features:**
- Skills mentioned (TF-IDF vectors)
- Experience requirements (regex extraction)
- Job title keywords
- Salary range indicators

---

## 🛠️ Tech Stack

**Languages & Libraries:**
- Python 3.8+
- Pandas, NumPy - Data manipulation
- Scikit-learn - ML models & pipeline
- Matplotlib, Seaborn - Visualization

**Techniques:**
- NLP: Text preprocessing, TF-IDF vectorization
- Feature Engineering: Regex extraction, dimensionality reduction (TruncatedSVD)
- ML: Multi-class classification, ensemble methods, hyperparameter tuning, cross-validation

---

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/job-seniority-prediction.git
cd job-seniority-prediction

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook job-seniority-prediction.ipynb
```

---

## 📁 Repository Contents

- `job-seniority-prediction.ipynb` - Complete ML pipeline analysis
- `requirements.txt` - Python dependencies
- `README.md` - Project documentation

**Note:** Dataset collected via Kaggle API - see notebook for collection code

---

## 💡 Key Insights

1. **Job titles alone are insufficient** - same title means different things across companies
2. **Skill combinations matter most** - specific technical skills + experience keywords drive predictions
3. **Class imbalance is real** - Entry/Mid levels predict well, rare senior roles need more data
4. **Location doesn't matter much** - seniority expectations surprisingly consistent nationwide

---

## 📬 Contact

**Author:** Niveda Jawahar 
**LinkedIn:** [https://www.linkedin.com/in/nivedajawahar/]
**Email:** nivedajawahar@gmail.com

---

*Data Science Master's Student @ University of Maryland, College Park*
