## 🚢 Titanic Survival Prediction Using Logistic Regression

### 📁 Project Structure


titanic-survival-prediction-logistic-regression/
├── data/                   # (Optional) Data files
├── notebooks/              # Jupyter notebooks
├── titanic_model.py        # Python script (if any)
├── README.md               # Project description
└── requirements.txt        # Python dependencies


### 🧠 Objective

To predict the **survival of passengers** on the Titanic using logistic regression and explore the key features affecting their chances.


### 📊 Dataset

* Source: [Titanic Dataset – GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
* Description: The dataset contains data on passengers including age, sex, class, fare paid, and whether they survived.


### ✅ Features Used

* `Pclass` – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
* `Sex` – Gender of the passenger
* `Age` – Age in years
* `Fare` – Ticket fare
* `Embarked` – Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### 🛠️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Scikit-learn (LogisticRegression, train\_test\_split, etc.)
* Matplotlib & Seaborn (for visualization)


### 📌 Steps Performed

1. **Data Loading** – Load dataset from URL
2. **Data Cleaning** – Handle missing values, drop irrelevant features
3. **Feature Engineering** – Encode categorical variables
4. **Train-Test Split** – Divide dataset for training and testing
5. **Feature Scaling** – Normalize numeric features
6. **Model Training** – Train logistic regression model
7. **Evaluation** – Use accuracy, confusion matrix, and classification report



### 📈 Model Evaluation

* **Accuracy:** *e.g., 82.5%*
* **Confusion Matrix:** Visualized with Seaborn heatmap
* **Precision / Recall / F1-Score:** Evaluated using `classification_report()`

---

### 🙋‍♂️ Author

Linkedin
https://www.linkedin.com/in/sameersameersito/


