📊 Student Performance Data Visualization
📂 Dataset

This dataset contains information about students' academic performance in three subjects: Math, Reading, and Writing.
It also includes demographic and background details such as:

Gender

Parental level of education

Lunch type

Test preparation course

This data helps us analyze factors affecting student performance.

🔎 Objective

The goal of this notebook is to visualize and analyze student performance using Matplotlib and Seaborn.
We use 13 different plots (6 Matplotlib + 7 Seaborn) to better understand score distributions, comparisons, and relationships.

📊 Visualizations & Insights
🔹 Matplotlib Visualizations

Histogram → Distribution of Math Scores

Shows how math scores are spread across students.

Most students scored between 60 and 80.

Line Plot → Math Scores Trend (First 50 Students)

Plots math scores of the first 50 students.

We can see fluctuations but most scores remain in the middle range.

Bar Chart → Average Math Score by Gender

Compares average math performance between male and female students.

Males scored slightly higher on average in Math.

Scatter Plot → Math Score vs Reading Score

Shows the relationship between math and reading.

Positive correlation: Students good at math tend to do well in reading too.

Pie Chart → Gender Distribution

Displays the proportion of male vs female students.

Dataset is fairly balanced, with slightly more females.

Stacked Bar Chart → Average Scores by Gender

Compares Math, Reading, and Writing averages for each gender.

Females scored better in Reading & Writing, while males were slightly ahead in Math.

🔹 Seaborn Visualizations

KDE Plot → Reading Score Distribution

Smooth curve showing reading score density.

Most scores lie between 60 and 80, similar to math.

Box Plot → Math Score by Gender

Compares math scores spread for each gender.

Male students show a wider spread of scores with higher outliers.

Violin Plot → Writing Score by Test Preparation

Compares writing scores for students with and without test prep.

Students who completed test preparation generally scored higher.

Swarm Plot → Math Score by Lunch Type

Displays math scores based on lunch type (standard vs free/reduced).

Students with standard lunch usually scored higher.

Pairplot → Relation between Math, Reading, and Writing Scores

Shows scatter plots for all subject combinations.

Strong positive relationship among all three subjects.

Countplot → Students by Parental Education Level

Shows how many students belong to each parental education category.

Most parents completed some college or high school.

Heatmap → Correlation between Scores

Displays correlation values among Math, Reading, and Writing.

Strong correlation (0.8+) between Reading and Writing.

✅ Conclusion

Students who completed test preparation and had standard lunch performed better.

Reading and Writing scores are strongly related, while Math also correlates but slightly less.

Gender differences exist: males scored better in Math, while females did better in Reading & Writing.

Parental education level also plays a role in student performance trends.

⚙️ Tech Stack

Python

Pandas → Data handling

Matplotlib → Basic plotting

Seaborn → Advanced visualizations
