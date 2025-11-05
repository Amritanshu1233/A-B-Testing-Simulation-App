# 🧪 A/B Testing for Website Conversion Optimization

This Streamlit app simulates and analyzes A/B testing results to determine whether a new website variant (Version B) performs significantly better than the current version (Version A) based on conversion rates.

---

## 🎯 Objective

The goal of this project is to:
- Understand and simulate A/B testing using Python.
- Calculate conversion rates and confidence intervals.
- Perform a statistical Z-test to verify if the difference is statistically significant.
- Visualize conversion rates with error bars for clear decision-making.

---

## 🧠 Key Features

- Simulates random conversions for both variants (A & B) using **NumPy**.
- Computes:
  - Conversion Rate (CR)
  - 95% Confidence Intervals (CI)
  - Z-Statistic and P-value using **Statsmodels**
- Displays:
  - Conversion comparison bar chart with error bars.
- Determines statistical significance:
  - Rejects or accepts the Null Hypothesis.
- Clean, interactive user interface powered by **Streamlit**.

---

## 🧩 Technologies Used

| Library | Purpose |
|----------|----------|
| Streamlit | Interactive web app framework |
| NumPy | Random number generation & array operations |
| Pandas | Data organization & display |
| Matplotlib | Visualization of conversion rates |
| Statsmodels | Statistical testing (Z-test & confidence intervals) |
| SciPy | Scientific & mathematical support functions |

---

## 🧮 **Statistical Methods**

- Conversion Rate (CR) = Conversions ÷ Visitors  
- Confidence Interval (CI) calculated using `proportion_confint`
- Z-Test for Proportions determines if the observed difference is statistically significant.

A p-value < 0.05** → statistically significant improvement in Variant B.

---

## 📊 **Visualization Example**

The bar chart generated shows:
- Variant A and B conversion rates.
- 95% Confidence Intervals (error bars).
- Non-overlapping CIs indicate strong evidence that one version performs better.

---

## ⚙️ How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/Arijit123789/A-B-Testing-Project.git
   cd A-B-Testing-Project

   2.	Install dependencies
   pip install -r requirements.txt

   3.	Run the app
   streamlit run app.py

   🌐 Deploy Online (Streamlit Cloud)
	1.	Go to https://share.streamlit.io￼
	2.	Connect your GitHub account.
	3.	Select the repo → set main file as app.py.
	4.	Click Deploy 🚀

Your app will be live at:

📚 Learning Outcomes
	•	Performing A/B tests using Python.
	•	Understanding statistical significance in conversion optimization.
	•	Interpreting confidence intervals and p-values.
	•	Building deployable data-science web apps using Streamlit.

  👨‍💻 Author

Amritanshu
📧 Contact: [amritanshukumar137@gmail.com]
🗓️ Project Year: 2025
