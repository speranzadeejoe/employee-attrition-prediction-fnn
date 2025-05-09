# Employee Attrition Prediction using Feedforward Neural Network (FNN)

This project predicts employee attrition using a deep learning model built with TensorFlow and Keras. It leverages HR data to classify whether an employee is likely to leave the organization.

---

## 📌 Project Overview

Employee attrition (also known as employee turnover) is a major concern in human resources. Predicting attrition helps companies retain talent and reduce hiring costs.

This model:
- Preprocesses a real-world HR dataset
- Encodes categorical variables
- Scales numerical features
- Trains a Feedforward Neural Network (FNN)
- Evaluates performance with accuracy and loss graphs

---

## 🧠 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 📂 Dataset

> The dataset includes HR features such as:
- Age, Gender, Department, Job Role
- Monthly Income, Years at Company, etc.
- Target: `Attrition` (Yes/No)

**Note:** This project uses a dataset structured similarly to IBM HR Analytics. Ensure `Attrition` is the target column.

---

## ⚙️ Model Architecture

- Input Layer (normalized features)
- Dense Layer (64 units, ReLU)
- Dropout Layer (0.4)
- Dense Layer (32 units, ReLU)
- Dropout Layer (0.3)
- Output Layer (1 unit, Sigmoid)

---
📈 Results
Final test accuracy:89.12

Loss and accuracy graphs plotted for training and validation sets

✅ Future Improvements
Hyperparameter tuning

Incorporate SMOTE for class imbalance

Feature selection using SHAP or mutual information

Compare with tree-based models (e.g., Random Forest, XGBoost)

🤝 Contributing
Feel free to fork the repository and open a pull request. Contributions are welcome!

📄 License
This project is licensed under the MIT License.

👤 Author
Speranza Deejoe
