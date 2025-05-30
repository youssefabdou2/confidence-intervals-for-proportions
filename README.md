

# 🔥 Confidence Interval for Proportion – Forest Fires Dataset

This project demonstrates how to calculate a **confidence interval for a population proportion** using real-world data from a forest fire dataset. The focus is on estimating the proportion of **small forest fires**, which helps the Parks Department make **cost-effective staffing and resource decisions**.

---

## 📊 Objective

To estimate, with 95% confidence, the **true proportion** of forest fires considered *small* using the `is_small` column (binary: 1 for small, 0 for not small). The analysis guides how the Parks Department can plan for resource allocation more efficiently.

---

## 🔍 Methodology

### 1. **Understand the Data**

* `is_small` column contains:

  * `1` for small fires
  * `0` for non-small fires

### 2. **Visualize the Distribution**

* Use a quick bar chart to explore the balance between small and not-small fires.
* Observation: Distribution is roughly balanced around 0.5, indicating higher variability.

### 3. **Calculate Key Statistics**

* **Sample Proportion ($\hat{p}$)**:

  $$
  \hat{p} = \text{mean of the is\_small column} \approx 0.48
  $$
* **Complement (1 - $\hat{p}$)**:

  $$
  1 - \hat{p} = 0.52
  $$
* **Sample Size (n)**:

  $$
  n = \text{count of entries} 
  $$

### 4. **Set Confidence Level**

* **Z-score for 95% confidence**:

  $$
  z = 1.96
  $$

### 5. **Calculate Margin of Error**

* Formula:

  $$
  \text{ME} = z \times \sqrt{\frac{\hat{p}(1 - \hat{p})}{n}}
  $$

### 6. **Compute Confidence Interval**

* **Lower Bound**: $\hat{p} - \text{ME} \approx 0.4347$
* **Upper Bound**: $\hat{p} + \text{ME} \approx 0.5208$
* ✅ **95% Confidence Interval**: **(0.4347, 0.5208)**

---

## 🎯 Interpretation

* The Parks Department can be **95% confident** that the true proportion of small forest fires is between **43.47% and 52.08%**.
* Since **0.5** is within this interval, it's reasonable to estimate that **about half of the fires are small**.
* This allows for **strategic resourcing**, like assigning smaller crews and using hand tools for small fires.

---

