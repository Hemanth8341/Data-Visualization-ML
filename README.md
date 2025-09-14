📊 Student Performance Data Visualization

## 📂 Dataset

This dataset contains information about students' academic performance in three subjects: **Math, Reading, and Writing**.
It also includes demographic and background details such as:

* Gender
* Parental level of education
* Lunch type
* Test preparation course

This data helps us analyze factors affecting student performance.

---

## 🔎 Objective

The goal of this notebook is to **visualize and analyze student performance** using **Matplotlib** and **Seaborn**.
We use 13 different plots (6 Matplotlib + 7 Seaborn) to better understand score distributions, comparisons, and relationships.

---

## 📊 Visualizations & Insights
Perfect ✅ — let’s expand each visualization with **more detailed explanations** (what the chart shows, why it’s useful, and how to interpret it). This will make your README and project more professional and insightful.

## 🔹 Matplotlib Visualizations

### 1. **Histogram → Distribution of Math Scores**

* A histogram groups math scores into bins (e.g., 0–10, 10–20, …).
* It helps us see the **frequency of students scoring within certain ranges**.
* Insight: Most students score between **60–80 marks**, meaning performance clusters around this range.
* Few students are at the extremes (very low or very high).

---

### 2. **Line Plot → Math Scores Trend (First 50 Students)**

* A line plot connects data points of the first 50 students.
* Useful to check **trends and fluctuations** across sequential data (student index).
* Insight: While the scores fluctuate, the majority stay within the middle-performance band, with occasional peaks and drops.

---

### 3. **Bar Chart → Average Math Score by Gender**

* Bar charts show **average values** per category.
* Here, we grouped by gender and calculated average math scores.
* Insight: **Males slightly outperform females in Math**, but the gap is small.

---

### 4. **Scatter Plot → Math Score vs. Reading Score**

* A scatter plot places points for each student: (Math score, Reading score).
* Useful to check **relationships or correlations**.
* Insight: A **positive trend** is visible — students who score high in Math tend to also perform well in Reading.

---

### 5. **Pie Chart → Gender Distribution**

* Pie charts show proportions of categories.
* Here, it shows the male vs female split in the dataset.
* Insight: The dataset is **fairly balanced** but has slightly more females. This is important to check bias in the dataset.

---

### 6. **Stacked Bar Chart → Average Scores by Gender**

* A stacked bar chart shows **multiple values for each category stacked together**.
* Here, for each gender, Math, Reading, and Writing averages are stacked.
* Insight:

  * **Females score higher in Reading and Writing.**
  * **Males are slightly better in Math.**
  * Shows subject-specific strengths by gender.

---

## 🔹 Seaborn Visualizations

### 1. **KDE Plot → Reading Score Distribution**

* A KDE (Kernel Density Estimation) plot smooths out the histogram curve.
* It shows the **probability distribution** of reading scores.
* Insight: Most students score between **60–80**, confirming a central clustering similar to Math scores.

---

### 2. **Box Plot → Math Score by Gender**

* Box plots show **median, quartiles, and outliers**.
* Insight:

  * **Median math scores** of males are slightly higher.
  * Males also have **more high outliers** (very high performers).
  * The spread (range of scores) is larger for males.

---

### 3. **Violin Plot → Writing Score by Test Preparation**

* Combines a box plot with a density plot, showing both distribution and spread.
* Insight:

  * Students who **completed test preparation** score higher in Writing.
  * Their distribution is also **tighter**, meaning more consistent performance.
  * Without prep, students show wider variation and lower medians.

---

### 4. **Swarm Plot → Math Score by Lunch Type**

* Swarm plots show **individual data points** categorized by lunch type.
* Insight:

  * Students with **standard lunch** mostly score higher in Math.
  * Those with **free/reduced lunch** have lower scores, possibly indicating socio-economic influence.

---

### 5. **Pairplot → Relation between Math, Reading, and Writing Scores**

* Pairplots create scatterplots for each pair of variables + histograms on the diagonal.
* Insight:

  * All three scores are strongly correlated.
  * High-performing students usually excel in all subjects, not just one.
  * Reading and Writing are most closely linked.

---

### 6. **Countplot → Students by Parental Education Level**

* Countplots show frequency counts for categories.
* Insight:

  * Most parents have **some college** or **high school** education.
  * Fewer students have parents with **master’s degree**.
  * Parental education could influence student performance indirectly.

---

### 7. **Heatmap → Correlation between Scores**

* Heatmaps show correlation coefficients between variables.
* Correlation ranges from **-1 (negative)** to **+1 (positive)**.
* Insight:

  * **Reading & Writing: 0.8+ correlation** (very strong).
  * Math also correlates positively but slightly less with Reading/Writing.
  * Suggests skills in Reading & Writing are more closely linked than Math.

---

## ✅ Conclusion

* Students who **completed test preparation** and had **standard lunch** performed better.
* **Reading and Writing scores** are strongly related, while Math also correlates but slightly less.
* Gender differences exist: **males scored better in Math**, while **females did better in Reading & Writing**.
* Parental education level also plays a role in student performance trends.

---

## ⚙️ Tech Stack

* **Python**
* **Pandas** → Data handling
* **Matplotlib** → Basic plotting
* **Seaborn** → Advanced visualizations

-----------------------------------
