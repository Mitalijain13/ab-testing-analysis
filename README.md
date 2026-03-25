# 📊 A/B Testing Analysis – Checkout Optimization

## 🧠 Problem Statement
An e-commerce company introduced a new checkout flow (Version B) to improve user conversion rates.  
The objective of this project is to evaluate whether the new design leads to a statistically significant and meaningful improvement in performance.

---

## 🎯 Objective
- Compare conversion rates between Version A (old) and Version B (new)
- Determine statistical significance of observed differences
- Analyze user behavior across segments
- Provide business recommendation based on insights

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Statistical Testing (Z-test / T-test)
- Matplotlib (Visualization)
- Jupyter Notebook

---

## 📊 Dataset Description
The dataset was simulated to represent real-world user behavior and includes:

- `user_id` → Unique user identifier  
- `group` → A (control) / B (test)  
- `user_type` → New / Returning users  
- `device` → Mobile / Desktop  
- `traffic_source` → Ads / Organic  
- `converted` → 1 (purchase) / 0 (no purchase)  
- `revenue` → Purchase amount  

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning
- Checked for missing values and duplicates
- Ensured dataset consistency

### 2. Conversion Rate Analysis
- Compared overall performance of Version A vs B

### 3. Statistical Testing
- Performed hypothesis testing to validate results
- Evaluated p-value for significance

### 4. Segmentation Analysis
- Analyzed performance across:
  - User type (new vs returning)
  - Device type
  - Traffic source

### 5. Revenue Analysis
- Measured average revenue impact of both versions

### 6. Visualization
- Created charts to compare performance visually

---

## 📈 Key Insights

- Version B improved overall conversion rate  
- The improvement is statistically significant  
- Conversion uplift is primarily driven by **new users**  
- **Returning users showed a decline in performance**  
- Mobile users responded better to Version B  

---

## 💡 Business Recommendation

A full rollout of Version B is not recommended.

👉 Suggested Strategy:
- Deploy Version B for **new users**
- Retain Version A for **returning users**

This ensures maximum conversion gains while minimizing risk.

---

## ⚠️ Limitations

- Dataset is simulated and may not reflect all real-world complexities  
- External factors (seasonality, campaigns) not considered  
- Experiment duration impact not evaluated  

---

## 🚀 Key Takeaways

- Statistical significance ≠ business success  
- Segmentation is critical in A/B testing  
- Data-driven decisions must consider user behavior differences  

---

## 🔗 Project Files

- 📁 Notebook: `ab_testing_analysis.ipynb`  
- 📁 Dataset: `ab_test_data.csv`  

---

## 🙌 Author

**Mitali Jain**  
Aspiring Data Analyst | SQL | Power BI | Python
