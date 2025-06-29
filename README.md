
# ❤️ Heart Disease Prediction using Machine Learning

This project presents a **Heart Disease Prediction System** that leverages a classification model (Logistic Regression) to predict whether an individual is at risk of heart disease based on medical attributes.

---

## 📌 Overview

The model is trained on a real-world dataset containing information like age, sex, blood pressure, cholesterol levels, and more. The system analyzes these inputs and predicts the likelihood of heart disease.

### 🎯 Goal:
To build a machine learning classification model that can:
- Help in early detection of heart disease
- Serve as a foundation for healthcare analytics tools
- Improve predictive accuracy using proper preprocessing and evaluation

---

## 📊 Dataset

- Dataset Source: [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- Shape: 1025 rows × 14 features
- Target variable: `target` (1 = presence of heart disease, 0 = no disease)

---

## 🔍 Workflow

1. **Data Cleaning**  
   Checked for null values, datatypes, and basic stats

2. **Exploratory Data Analysis (EDA)**  
   - Histograms for distribution
   - Value counts for target class

3. **Feature Selection & Splitting**  
   - Features: All except `target`
   - Target: `target`
   - Split: 80% training, 20% testing

4. **Model Training**  
   - Algorithm: `Logistic Regression`
   - Accuracy (Train): **85%**
   - Accuracy (Test): **90%**

5. **Prediction Function**  
   - User-defined function to input medical data and return prediction (heart disease or not)

6. **Evaluation Metrics**  
   - Confusion Matrix
   - Precision, Recall
   - ROC Curve & AUC Score

---

## 📈 Results

- ✅ **Train Accuracy:** 85%
- ✅ **Test Accuracy:** 90%
- ✅ **AUC Score:** High (ROC curve shows good separation)
- ✅ Built an interactive prediction function

---

## 🧠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/Mihir-techie/Heart-Disease-Prediction

   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📌 Author

**Mihir Kumar Panigrahi**  
- 🔗 https://www.linkedin.com/in/mihir-kumar-panigrahi-9b4b6627a/
- 
- 

- 💻 Data Science Intern | AI Learner | Python Enthusiast

---

## 🏁 Future Improvements

- Add Streamlit or Flask UI for live prediction
- Use ensemble models for better accuracy
- Connect with a healthcare database

---

## 📃 License

This project is open source under the [MIT License](LICENSE).

