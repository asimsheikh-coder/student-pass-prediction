# 🎓 Student Pass Prediction using Logistic Regression

## 📄 Abstract
This project demonstrates a **Logistic Regression** model for predicting whether a student will **pass or fail** an exam based on two factors:
- Hours studied  
- Previous test score  

Logistic Regression is one of the simplest and most interpretable algorithms in **supervised machine learning**, often used for **binary classification** problems.  
This project helps beginners understand how probabilities and decision boundaries work in classification.

---

## 🎯 Objectives
1. Understand the concept of **Logistic Regression**.  
2. Build a predictive model for pass/fail outcomes.  
3. Visualize data and the decision boundary.  
4. Evaluate accuracy and interpret probabilities.  
5. Make predictions for new student data.

---

## 🧩 Dataset
The dataset is synthetically created for demonstration purposes.  
Each record represents a student with the following features:

| Feature | Description |
|----------|--------------|
| Hours_Studied | Number of hours studied before the exam |
| Previous_Score | Student’s score in a previous test |
| Passed | Target label (1 = Pass, 0 = Fail) |

Example:

| Hours_Studied | Previous_Score | Passed |
|----------------|----------------|---------|
| 3 | 50 | 0 |
| 6 | 65 | 1 |
| 9 | 82 | 1 |

---

## ⚙️ Implementation Steps
| Step | Description |
|------|--------------|
| 1️⃣ | **Import Libraries** — Load necessary packages like `pandas`, `sklearn`, and `matplotlib`. |
| 2️⃣ | **Create Dataset** — Build a simple dataframe of students and their scores. |
| 3️⃣ | **Visualize Data** — Use Seaborn to plot the distribution of Pass/Fail. |
| 4️⃣ | **Train Model** — Apply `LogisticRegression()` from Scikit-learn. |
| 5️⃣ | **Evaluate Model** — Measure accuracy and display confusion matrix. |
| 6️⃣ | **Visualize Decision Boundary** — Show how the model separates Pass and Fail. |
| 7️⃣ | **Predict New Data** — Predict pass probability for new students. |

---

## 🧠 Logistic Regression — How It Works
Unlike Linear Regression, Logistic Regression predicts **probabilities** between 0 and 1 using the **sigmoid function**:

\[ P(y=1|x) = \frac{1}{1 + e^{-(b_0 + b_1x)}} \]

The output is converted into binary values:
- If P ≥ 0.5 → **Pass (1)**  
- If P < 0.5 → **Fail (0)**

---

## 📊 Results
✅ Model Accuracy: **~90–100%** on the sample dataset  
✅ Confusion Matrix and Classification Report included  
✅ Decision Boundary visualization using Matplotlib  

Example Prediction:
```
Student with 7.5 hrs and score 78 → Predicted: Pass (Prob Pass: 0.93)
```

---

## 🧪 Tools & Libraries Used
- **Python 3.x**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🚀 How to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/asimsheikh-coder/student-pass-prediction-using-logistic-regression.git
   cd student-pass-prediction-using-logistic-regression
   ```
2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. **Run the notebook**
   ```bash
   jupyter notebook Logistic_Regression_Student_Pass_Prediction.ipynb
   ```

---

## 🧑‍💻 Author
**Asim Sheikh**  
12th Grade Student | Aspiring AI Engineer  
📧 Email: asimusmansheikh0@gmail.com  
🌐 GitHub: [@asimsheikh-coder](https://github.com/asimsheikh-coder)

---

## 🔖 Citation
> Sheikh, A. *Student Pass Prediction using Logistic Regression*. 2025. GitHub Repository.  
> [https://github.com/asimsheikh-coder/student-pass-prediction-using-logistic-regression](https://github.com/asimsheikh-coder/student-pass-prediction-using-logistic-regression)

---

## 🏁 Conclusion
This project provides a clear and practical understanding of **Logistic Regression** for beginners.  
By modeling the probability of passing based on study effort, it connects machine learning directly to a relatable, real-world example.  
It’s a great first step toward understanding classification algorithms in AI.

---
