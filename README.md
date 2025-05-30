🔥 Confidence Interval for Proportion – Forest Fires Dataset
This project demonstrates how to calculate a confidence interval for a population proportion using real-world data from a forest fire dataset. The focus is on estimating the proportion of small forest fires, which helps the Parks Department make cost-effective staffing and resource decisions.

📊 Objective
To estimate, with 95% confidence, the true proportion of forest fires considered small using the is_small column (binary: 1 for small, 0 for not small). The analysis guides how the Parks Department can plan for resource allocation more efficiently.

🔍 Methodology
1. Understand the Data
is_small column contains:

1 for small fires

0 for non-small fires

2. Visualize the Distribution
Use a quick bar chart to explore the balance between small and not-small fires.

Observation: Distribution is roughly balanced around 0.5, indicating higher variability.

3. Calculate Key Statistics
Sample Proportion (
𝑝
^
p
^
​
 ):

𝑝
^
=
mean of the is_small column
≈
0.48
p
^
​
 =mean of the is_small column≈0.48
Complement (1 - 
𝑝
^
p
^
​
 ):

1
−
𝑝
^
=
0.52
1− 
p
^
​
 =0.52
Sample Size (n):

𝑛
=
count of entries
n=count of entries
4. Set Confidence Level
Z-score for 95% confidence:

𝑧
=
1.96
z=1.96
5. Calculate Margin of Error
Formula:

ME
=
𝑧
×
𝑝
^
(
1
−
𝑝
^
)
𝑛
ME=z× 
n
p
^
​
 (1− 
p
^
​
 )
​
 
​
 
6. Compute Confidence Interval
Lower Bound: 
𝑝
^
−
ME
≈
0.4347
p
^
​
 −ME≈0.4347

Upper Bound: 
𝑝
^
+
ME
≈
0.5208
p
^
​
 +ME≈0.5208

✅ 95% Confidence Interval: (0.4347, 0.5208)

