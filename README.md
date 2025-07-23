# 💼 Employee Salary Classification

This project predicts whether an employee earns more than 50K per year using machine learning. It is built using Python, trained on the Adult Income dataset, and deployed using Streamlit for both single and batch prediction.

---

## 📌 Problem Statement

The goal is to classify an employee's income into two categories: `>50K` or `≤50K` based on demographic and work-related attributes such as age, education, occupation, and hours worked per week. This classification helps in understanding income distribution patterns and can be used in HR analytics.

---

## ⚙️ System Requirements

- Python 3.7+
- Jupyter Notebook / VS Code / any IDE
- Streamlit

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `joblib`
- `streamlit`

---

## 🚀 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Encoded categorical variables using `LabelEncoder`

2. **Model Training**
   - Trained a classification model (e.g., Random Forest)
   - Evaluated the model using accuracy and classification report

3. **Model Saving**
   - Saved the trained model and label encoders using `joblib`

4. **Streamlit Frontend**
   - Single input prediction using sidebar
   - CSV batch upload support for multiple predictions
   - Downloadable results

---

📸 Screenshots

---

<img width="1039" height="489" alt="Screenshot 2025-07-23 181527" src="https://github.com/user-attachments/assets/e168db83-a46b-402b-92f9-e0e0ef371c4a" />

<img width="800" height="498" alt="Screenshot 2025-07-23 181543" src="https://github.com/user-attachments/assets/30709c70-1ac4-4106-bde1-dab4af88bbed" />

<img width="1142" height="774" alt="Screenshot 2025-07-23 181635" src="https://github.com/user-attachments/assets/c6510310-054a-48cf-b24c-ab396dd8d37f" />

<img width="832" height="720" alt="Screenshot 2025-07-23 181655" src="https://github.com/user-attachments/assets/0bd579da-3480-4f29-9637-4f07aca7256e" />

<img width="1920" height="1080" alt="Screenshot 2025-07-23 182156" src="https://github.com/user-attachments/assets/c30dfd85-f5f3-4d1a-980d-7544eca00a10" />

---

✅ Results

---

Achieved high accuracy in predicting income category.

Supports both single prediction and batch prediction via CSV.

---

📝 Conclusion

---

This project demonstrates how machine learning and Streamlit can be combined to build real-time, user-friendly applications for classification tasks. It simplifies salary prediction by automating input handling, encoding, and prediction.

---

🔮 Future Scope

---

Add more feature engineering and model tuning

Deploy to the cloud for public access

Integrate user authentication and input logging

---

📚 References

---

UCI Adult Dataset: https://archive.ics.uci.edu/ml/datasets/adult

Scikit-learn Documentation : https://scikit-learn.org/stable/

Streamlit Docs: https://docs.streamlit.io/







