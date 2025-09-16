# 🚗 Car Price Prediction using Linear Regression & Lasso

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

This is my **third Machine Learning project** after learning from Siddhardhan's YouTube channel 🚀.
The project predicts the **price of a car** using **Linear Regression** and **Lasso Regression** algorithms.

---

## 📚 Learning Journey

* Followed Siddhardhan's tutorials on YouTube to strengthen ML fundamentals.
* Implemented the project using **Google Colab**.
* Learned about **data preprocessing, regression model building, and performance evaluation**.

---

## 📊 Dataset Information

* Dataset contains car features and their corresponding selling price.
* Includes categorical and numerical features.
* Preprocessing involved handling missing values, encoding, and feature selection.

📌 *Note: The dataset is included in this repository in the `dataset.txt` file. You can also download a dataset from websites like Kaggle or UCI.*

---

## 🛠️ Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression, Lasso
from sklearn import metrics
```

---

## 🔄 Project Workflow

1. **Car Data** → Load dataset for analysis
2. **Data Preprocessing** → Handle missing values, encode categorical features, feature scaling
3. **EDA** → Visualize correlations & insights with Matplotlib & Seaborn
4. **Train-Test Split** → Divide dataset into training & testing sets
5. **Model Building** → Apply **Linear Regression** and **Lasso Regression**


---

## 📊 Model Results & Accuracy

* **Linear Regression**

  * (Training): *0.87*
  * (Testing): *0.83*

* **Lasso Regression**

  * (Training): *0.84*
  * (Testing): *0.87*

📌 *Note: Results may vary depending on dataset used.*

---

## 💻 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/car-price-prediction-ml.git
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook in Google Colab using the badge above ☝️ or locally:

   ```bash
   jupyter notebook notebooks/Car_Price_Prediction.ipynb
   ```

---

## 🎯 Conclusion

This project helped me:

* Understand **regression techniques** in ML
* Explore differences between **Linear Regression & Lasso**
* Learn how to evaluate models using multiple error metrics

Another great step in my **Machine Learning journey**! 🚀

---

## 🙌 Acknowledgments

Special thanks to **Siddhardhan** for his beginner-friendly ML tutorials on YouTube.
⭐️ If you found this helpful, consider giving this repo a **star**!

---
