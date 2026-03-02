# 📊 Transaction Distribution Analysis Project  
### Statistical Modeling & Probability-Based Decision Making  

---

## 🌟 Overview  

This project focuses on analyzing transactional data using statistical distributions and probability theory.  
The goal is to understand how transaction behavior can be modeled mathematically to support better business decisions.

Using Python and statistical libraries, the dataset was examined to identify suitable probability distributions for transaction occurrence, frequency, and monetary value patterns.

---

## 🎯 Objective  

- Model transaction behavior using appropriate statistical distributions  
- Evaluate data normality and skewness  
- Estimate probabilities of high-value transactions  
- Transform skewed data to improve interpretability  
- Extract insights useful for operational and financial planning  

---

## 🗂 Dataset Description  

The dataset consists of transactional records containing:

- Transaction identifiers  
- Customer identifiers  
- Transaction amount (₹)  
- Transaction date  
- Weekly transaction count  
- Geographic region  
- Transaction status (Success / Fail)  

The data represents real-world financial transaction behavior with varying frequencies and amounts.

---

## 🧠 Statistical Techniques Applied  

This project applies both discrete and continuous probability distributions:

- **Bernoulli Distribution** → Binary transaction success modeling  
- **Binomial Distribution** → Weekly transaction success modeling  
- **Poisson Distribution** → Daily transaction frequency modeling  
- **Log-Normal Distribution** → Modeling skewed transaction amounts  
- **Power Law Distribution** → Modeling extreme-value behavior  
- **Box-Cox Transformation** → Variance stabilization  
- **Z-score Analysis** → Detection of unusually high transactions  
- **PDF & CDF Visualization** → Understanding probability behavior  
- **Q-Q Plot Analysis** → Normality assessment  

---

## 📈 Key Observations  

- Transaction success behaves as a binary outcome and follows Bernoulli behavior.  
- Weekly aggregated results align with Binomial characteristics.  
- Daily transaction frequency follows Poisson behavior.  
- Transaction amounts are strongly right-skewed.  
- Q-Q plot confirms non-normal distribution.  
- Log-Normal distribution provides the best overall fit for transaction amounts.  
- Box-Cox transformation reduces skewness and improves symmetry.  

---

## 🏆 Final Distribution Insight  

Although different variables follow different distributions, the **dominant financial variable — transaction amount — best fits a Log-Normal distribution.**

This is consistent with real-world financial systems where:

- Most transactions are small  
- Few transactions are extremely large  
- Data exhibits heavy right-tail behavior  

Therefore, the dataset overall is best described as a **mixture of discrete event distributions and a Log-Normal monetary distribution.**

---

## 📊 Business Applications  

The modeling results can support:

- Fraud detection through probability thresholds  
- Risk assessment of high-value transactions  
- Capacity planning using Poisson estimates  
- Weekly performance evaluation  
- Revenue forecasting  

---

## 🛠 Technologies Used  

- Python  
- NumPy  
- Pandas  
- SciPy  
- Statsmodels  
- Matplotlib  
- Seaborn  

---

## 📌 Conclusion  

This project demonstrates how statistical distributions can transform raw transactional data into actionable insights.  
By identifying the appropriate probability models, we gain a clearer understanding of financial behavior patterns and risk structures.

The analysis confirms that real-world transaction systems rarely follow a simple normal distribution — instead, they exhibit skewness and heavy-tail characteristics best captured by Log-Normal modeling.
