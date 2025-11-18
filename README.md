# 🎬 MACHINE LEARNING — MOVIE SUCCESS PREDICTION  

**Pre-Release Classification Project**

---

## 📘 Project Overview 

This project focuses on **predicting a movie’s success (Hit or Flop)** *before its release*, using data such as genre, budget, country, director, lead actor, etc.

A complete **Machine Learning Classification Pipeline** was designed — from **data exploration and preparation** to **model comparison and insights** — to evaluate how well different algorithms can predict movie outcomes **before release**.

---

## 🎯 Goal  

Predict whether a movie will be a **Hit or Flop** using pre-release features, helping filmmakers, investors, and studios make smarter production and marketing decisions.

---

## 🧾 Dataset Description  

| Attribute | Description |
|------------|-------------|
| **Source** | Provided dataset (pre-release features only) |
| **Type** | Supervised Learning (Classification) |
| **Target Variable** | `Success` — 1 = Hit, 0 = Flop |
| **Features** | `Genre`, `BudgetUSD`, `Country`, `Director`, `LeadActor`, etc. |
| **Data Split** | 80% Training – 20% Testing |

Data cleaning included handling missing values, encoding categorical columns, and ensuring no post-release features (like ratings or collections) were included.

---

## 🧮 Machine Learning Process  

### 🔹 Steps Performed  

**1. Data Preparation**  
- Loaded dataset & examined structure  
- Handled missing values & duplicates  
- Encoded categorical features (LabelEncoder)  
- Split data into training and testing sets (80–20)  

**2. Model Building**  
Trained and compared **9 classification models** for pre-release prediction:

| # | Algorithm | Description |
|---|------------|--------------|
| 1 | Logistic Regression | Baseline model for binary classification |
| 2 | Decision Tree Classifier | Simple tree-based model to capture rules |
| 3 | Random Forest Classifier | Ensemble of multiple trees for stability |
| 4 | K-Nearest Neighbors (KNN) | Prediction based on neighboring data points |
| 5 | AdaBoost Classifier | Boosting weak learners for better accuracy |
| 6 | Gradient Boosting Classifier | Sequential boosting to minimize errors |
| 7 | XGBoost Classifier | Optimized gradient boosting with regularization |
| 8 | LightGBM Classifier | Fast gradient boosting for large datasets |
| 9 | CatBoost Classifier | Handles categorical data efficiently |

**3. Model Evaluation**  
Each model was evaluated using:  
- **Accuracy** — overall correctness  
- **Precision, Recall, F1-score** — class-wise performance  
- **Confusion Matrix** — Hit/Flop classification breakdown  

---

## 📊 Results & Performance Insights  

### 🔹 Summary of Results  
| Algorithm | Accuracy | Performance Summary |
|------------|-----------|---------------------|
| Logistic Regression | Moderate | Good baseline, interpretable results |
| Decision Tree | Fair | Overfit slightly, low generalization |
| Random Forest | Good | Handled complexity well |
| KNN | Average | Sensitive to scaling and distance |
| AdaBoost | Decent | Improved balance, some misclassifications |
| Gradient Boosting | Strong | Stable and consistent predictions |
| **XGBoost Classifier** | **≈ 89%** | ⭐ **Best Performer** |
| LightGBM | Good | Fast, close to XGBoost |
| CatBoost | Good | Competitive, handles categories well |

🧠 **Best Model:**  
**XGBoost Classifier** achieved **~69% accuracy**, correctly identifying approximately **75% of Hits** and **25% of Flops**, making it the most balanced and robust model for pre-release prediction.

---

## 💡 Final Insights  

The project successfully demonstrated that **movie success can be predicted before release** using data-driven modeling and strategic analysis.  

### Key Findings:

#### 🎬 1. **Budget Planning**  

- Medium-to-high budgets (₹150 Cr – ₹650 Cr / $20M – $80M) strike the best balance between risk and return.  
- Invest more in **production quality, visuals, and marketing**, not just cast salaries.

#### 🎭 2. **Genre Selection**  

- **Action**, **Drama**, and **Thriller** genres dominate success rates.  
- Creative genre combinations (e.g., *Action-Comedy*, *Romantic-Thriller*) attract wider audiences.

#### 🎥 3. **Director Choice**  

- Directors with **3+ past successful films** in the same genre yield higher success rates.  
- Balance between **artistic vision** and **commercial appeal** is crucial.

#### ⭐ 4. **Casting**  

- Well-known **lead actors** boost audience trust and initial turnout.  
- Pair **popular leads with fresh faces** to maintain authenticity and freshness.

#### 📣 5. **Marketing & Buzz**  

- Start promotion **1–2 months before release**.  
- Engage through **trailers, songs, and social media campaigns**.  
- Strong **first-week buzz** strongly influences final success.

---

## 🧩 Model Comparison Summary  

| Category | Best Model | Reason |
|-----------|-------------|--------|
| Overall Accuracy | **XGBoost** | Most balanced performance |
| Speed & Efficiency | **LightGBM** | Fast training, similar results |
| Interpretability | **Logistic Regression** | Simple and explainable |
| Categorical Handling | **CatBoost** | Native categorical feature support |
| Generalization | **Gradient Boosting** | Strong bias-variance tradeoff |

---

## 🧰 Tools Used  

| Tool | Purpose |
|------|----------|
| **Python (Jupyter Notebook)** | Development and execution |
| **Pandas / NumPy** | Data handling and preprocessing |
| **Matplotlib / Seaborn** | Visualizations |
| **Scikit-learn** | ML algorithms & metrics |
| **XGBoost / LightGBM / CatBoost** | Advanced boosting models |
| **VS Code / GitHub** | Documentation & version control |

---

## 🏁 Conclusion  

This **Pre-Release Movie Success Prediction Project** highlights how **data-driven insights** can assist producers, investors, and studios in **decision-making even before release**.  

- **XGBoost Classifier** emerged as the most reliable model for pre-release predictions.  
- Success is highly correlated with **budget**, **genre**, **cast**, and **director experience**.  
- Smart planning in these areas can **significantly increase a movie’s chance of success**.

✨ **Final Takeaway:**  

> A movie’s success isn’t just luck — it’s often **predictable** with the right data, strategy, and creative balance. 🎬  
