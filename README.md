
# 🧠 Disease Prediction using Support Vector Machines (SVM)

This project aims to predict three major diseases — **Diabetes, Heart Disease, and Parkinson’s Disease** — using **Support Vector Machine (SVM)** models. Built with Python and trained on medical datasets, this tool assists in early detection based on patient input data.

---

## 📌 Project Overview

- 🔍 Predicts:
  - Diabetes
  - Heart Disease
  - Parkinson’s Disease
- 🧪 Algorithm Used: Support Vector Machine (SVM)
- 📊 Libraries: `Pandas`, `NumPy`, `scikit-learn`, `Streamlit` *(optional for UI)*

---

## 🧰 Tech Stack

| Category      | Tools / Frameworks                   |
|---------------|--------------------------------------|
| Programming   | Python 3.x                           |
| ML Framework  | scikit-learn                         |
| Data Handling | Pandas, NumPy                        |
| UI (Optional) | Streamlit                            |
| IDE           | Jupyter Notebook / VS Code           |

---

## 📂 Folder Structure

```
disease-prediction-using-svm/
├── diabetes.csv
├── heart.csv
├── parkinsons.csv
├── diabetes_model.sav
├── heart_model.sav
├── parkinsons_model.sav
├── svm_diabetes.py
├── svm_heart.py
├── svm_parkinsons.py
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/gauthamkn/disease-prediction-using-svm.git
cd disease-prediction-using-svm
```

2. **Install required libraries**
```bash
pip install pandas numpy scikit-learn
```

3. **Run the models**
```bash
python svm_diabetes.py
python svm_heart.py
python svm_parkinsons.py
```

4. *(Optional UI)* If using Streamlit:
```bash
pip install streamlit
streamlit run streamlit_app.py
```

---

## 📊 Sample Results

- **Accuracy Achieved:**
  - Diabetes: ~90%
  - Heart Disease: ~89%
  - Parkinson’s: ~92%
- Confusion Matrix and classification reports available in the respective `.py` files.

---

## 📌 Methodology

- Data Preprocessing: Handled missing values, normalization.
- Model Training: Trained an SVM classifier for each disease.
- Evaluation: Accuracy, Precision, Recall, F1-score.
- *(Optional)* Created a Streamlit UI for user-friendly predictions.

---

## 🎯 Future Improvements

- Add more ML models for comparison (Random Forest, XGBoost)
- Improve the UI with visualization support
- Enable live API calls for real-time predictions
- Include feature importance and medical data insights

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repo, raise issues, or submit pull requests.

---

## 📬 Contact

**Gautham Nambiar**  
📧 Email: gauthamkn999@gmail.com  
🔗 GitHub: @gauthamkn]-https://github.com/gauthamkn

---

> ⚠️ *Disclaimer:* This project is for educational purposes only and should not be used for actual medical diagnostics.
