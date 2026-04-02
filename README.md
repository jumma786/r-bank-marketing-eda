# 📊 Bank Marketing EDA in R

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a real-world bank marketing dataset using R.

The objective is to analyze customer data and identify key factors that influence whether a client subscribes to a term deposit.

---

## 🎯 Business Objective

Banks conduct marketing campaigns to promote financial products like term deposits.
This analysis helps to:

* Understand customer behavior
* Identify high-potential customer segments
* Improve marketing campaign effectiveness
* Increase subscription (conversion) rates

---

## 🛠 Tech Stack

* **Language:** R
* **Environment:** RStudio
* **Libraries:**

  * dplyr
  * ggplot2
  * Hmisc

---

## 📂 Dataset Information

* Dataset: Bank Marketing Dataset
* Format: CSV
* Records: ~45,000+ rows
* Features include:

### 👤 Customer Information

* Age
* Job
* Marital Status
* Education

### 💰 Financial Information

* Credit Default
* Housing Loan
* Personal Loan

### 📞 Campaign Information

* Contact Type (Cellular/Telephone)
* Month & Day of Contact
* Campaign Contacts
* Call Duration

### 📊 Previous Campaign Data

* Previous Contacts
* Days Since Last Contact
* Previous Outcome

### 📈 Economic Indicators

* Employment Variation Rate
* Consumer Price Index
* Consumer Confidence Index
* Euribor Rate
* Number of Employees

### 🎯 Target Variable

* `y` → Subscription (Yes/No)

---

## 🔍 Analysis Performed

* ✔ Data Cleaning & Preprocessing
* ✔ Handling Missing/Unknown Values
* ✔ Exploratory Data Analysis (EDA)
* ✔ Distribution Analysis
* ✔ Categorical & Numerical Analysis
* ✔ Data Visualization using ggplot2

---

## 📈 Key Insights

* Older customers show higher subscription rates
* Contact method significantly impacts success
* Customers with successful previous campaigns are more likely to convert
* Certain months have higher engagement levels
* Target variable is highly imbalanced (majority "No")

---

## 📊 Sample Visualizations

<img width="714" height="475" alt="image" src="https://github.com/user-attachments/assets/3d663578-ee2b-407d-8d2c-f7899cd40be4" />

<img width="700" height="430" alt="image" src="https://github.com/user-attachments/assets/f0e9a638-4b1e-41b5-9c5b-84546c5f413e" />


<img width="683" height="471" alt="image" src="https://github.com/user-attachments/assets/c9409ded-332a-4b75-a4f9-774fa32a4be2" />


<img width="709" height="454" alt="image" src="https://github.com/user-attachments/assets/f2e10b8d-901a-40ce-8c39-c0f9611e461a" />


<img width="699" height="473" alt="image" src="https://github.com/user-attachments/assets/e9862c6a-338b-4c52-9565-ccea6d502f15" />

<img width="682" height="456" alt="image" src="https://github.com/user-attachments/assets/ff127057-efa0-4c67-bbc2-5406ac78bfe7" />


<img width="707" height="461" alt="image" src="https://github.com/user-attachments/assets/66608df2-97f3-4601-87a5-a95029f8dd8e" />


<img width="699" height="455" alt="image" src="https://github.com/user-attachments/assets/e4ef190c-73a1-46c3-bdf1-3bdb7e051932" />

<img width="709" height="468" alt="image" src="https://github.com/user-attachments/assets/2745c8e0-35be-4ad6-9145-f65860adcae6" />

---

## 🚀 How to Run

```r id="3m0g9p"
# Install required packages (if not installed)
install.packages(c("dplyr", "ggplot2", "Hmisc"))

# Load libraries
library(dplyr)
library(ggplot2)
library(Hmisc)

# Load dataset
data <- read.csv("bank-marketing-data.csv")

# Open and run the RMarkdown file
# eda-bank-marketing.Rmd
```

---

## 📁 Project Structure

```id="1a7z9x"
r-bank-marketing-eda/
│
├── bank-marketing-data.csv
├── eda-bank-marketing.Rmd
├── README.md
└── images/
```

---

## ⚠️ Important Note

* The `duration` variable is highly predictive but should not be used in real-time prediction models, as it is only known after the call is completed.

---

## 👨‍💻 Author

**Jumma Mohammad Teli**
📍 Birmingham, UK
💼 Data Analyst | Python | SQL | Power BI | R

---

## 🌟 Project Highlights

* Real-world dataset
* Strong business-focused analysis
* Clean and structured EDA workflow
* Visualization-driven insights
* Portfolio-ready project

---

## 🔥 Future Improvements

* Build predictive models (Logistic Regression, Random Forest)
* Handle class imbalance (SMOTE, sampling techniques)
* Deploy dashboard using Power BI or Tableau
* Automate reporting pipeline

---




