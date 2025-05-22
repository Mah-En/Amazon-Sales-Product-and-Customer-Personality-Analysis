

# 📊 Amazon Sales and Customer Personality Analysis

Mahla Entezari
Shahid Beheshti University
📧 [MahlaEntezari.sbu@gmail.com](mailto:MahlaEntezari.sbu@gmail.com)

---

## 🧠 Abstract

This project explores Amazon's sales data and customer personality metrics using data science techniques. The objective is to derive actionable insights to inform marketing strategies, inventory planning, and revenue optimization. The analysis combines sales trends with demographic and behavioral insights of customers to provide a comprehensive business intelligence view.

---

## 📂 Dataset Overview

### 1. **Amazon Sales Dataset**

Sourced from Kaggle, this dataset includes:

* Product prices
* Discounts
* Ratings
* Reviews
* Sales volumes

### 2. **Customer Personality Dataset**

Also from Kaggle, this dataset includes:

* Demographics (age, education, marital status)
* Financial details (income)
* Lifestyle metrics (number of children, recency)
* Marketing campaign responses

📌 **Sources**:

* [Amazon Sales Dataset](https://www.kaggle.com/datasets/mahlaentezari/amazon-dataset)
* [Customer Personality Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data)

---

## 🛠️ Methods

### 🔍 Data Preprocessing

* Handled missing values and duplicates
* Normalized formats
* Feature engineering: Aggregated sales per month, income brackets, etc.

### 📈 Exploratory Data Analysis

Used pandas, seaborn, and matplotlib to:

* Understand distributions
* Reveal customer behavior patterns
* Identify seasonality and trends

### 📊 Statistical Testing

* **Shapiro-Wilk** and **Kolmogorov-Smirnov** tests confirmed non-normality of the data.
* These tests justified the use of non-parametric methods in follow-up analysis.

---

## 📊 Visualizations

### 🧩 Correlation Matrix

**Key Insights:**

* Income correlates with wine and meat spending.
* Kidhome shows a negative correlation with spending.
* Recency and complaints have negligible influence.

---

### 📌 KDE Plot

Visual comparison of actual data distribution vs. normal distribution to assess skewness.

---

### 📉 Histograms

| Plot                    | Insight                                        |
| ----------------------- | ---------------------------------------------- |
| Income Distribution     | Right-skewed with few high-income outliers     |
| Age Distribution        | Normally distributed, peak between 40–60 years |
| Income vs Wine Spending | Strong positive correlation                    |

---

### 📊 Bar Plots

| Plot                    | Insight                                              |
| ----------------------- | ---------------------------------------------------- |
| Education Levels        | Most customers have Graduation, PhD, or Master       |
| Campaign Acceptance     | Higher education leads to higher campaign acceptance |
| Avg Income by Education | Higher education → Higher income                     |

---

### 📦 Box Plots

| Plot                            | Insight                                        |
| ------------------------------- | ---------------------------------------------- |
| Age                             | Median age 40–60, some older outliers          |
| Income                          | Majority < 150,000, some high-income outliers  |
| Income by Education             | PhDs and Masters have higher earning potential |
| Spending by Kidhome             | No children = higher spending                  |
| Campaign Participation          | Higher educated customers engage more          |
| Wine Spending by Marital Status | Married/together = more wine purchases         |

---

## 🧾 Results & Recommendations

* **Target Market**: Customers aged 40–60 with Graduation, Master's, or PhD education.
* **Wine Marketing**: Focus on high-income, married customers.
* **Campaign Strategy**:

  * Personalize campaigns for singles/divorced.
  * Consider removing irrelevant marital categories (e.g., “YOLO”).
* **Segmentation**: Education and income are key indicators for spending behavior.

---

## 📚 References

1. Amazon Sales Dataset - [Kaggle](https://www.kaggle.com/datasets/mahlaentezari/amazon-dataset)
2. Customer Personality Dataset - [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data)
3. Visualization Resource - [From Data to Viz](https://www.data-to-viz.com/)
4. Cole Nussbaumer Knaflic, *Storytelling with Data*

---

## 💻 How to Run

1. Clone this repository.
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn scipy jupyter
   ```
3. Launch the notebook:

   ```bash
   jupyter notebook Mahla_Entezari-Assignment-1.ipynb
   ```
