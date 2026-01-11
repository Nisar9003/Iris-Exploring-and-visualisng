# Iris-Exploring-and-visualisng
AI/ML internship tasks including data analysis, visualization, and basic machine learning projects.
# Exploring and Visualizing the Iris Dataset

## Objective
The goal of this task is to explore and visualize the Iris dataset in order to
understand data structure, feature distributions, relationships between variables,
and the presence of outliers using basic data analysis techniques.

---

## Dataset
- **Name:** Iris Dataset  
- **Source:** Seaborn 
- **Description:**  
  The dataset contains 150 samples of iris flowers from three species:
  *Setosa*, *Versicolor*, and *Virginica*.  
  Each sample includes four numerical features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## Tools & Libraries Used
- **Python**
- **Pandas** – data loading and inspection
- **Seaborn** – data visualization
- **Matplotlib** – plotting graphs

---

## Steps Performed
1. Loaded the dataset using **pandas**
2. Inspected the dataset using:
   - Shape
   - Column names
   - First few rows (`head`)
3. Generated summary statistics using:
   - `info()`
   - `describe()`
4. Visualized the data:
   - Scatter plot to analyze feature relationships
   - Histograms to observe value distributions
   - Box plots to identify potential outliers

---

## Key Insights
- The dataset contains **150 rows and 5 columns**.
- No missing values were found.
- Petal length and petal width are the most important features for distinguishing species.
- The *Setosa* species is clearly separable from the other two.
- Minor outliers exist but do not significantly affect the dataset.

---

## Conclusion
This task helped in understanding the structure and characteristics of the Iris dataset
through exploratory data analysis and visualization techniques, forming a strong
foundation for further machine learning tasks.

---

## File Included
- `Task_1_Iris_Data_Exploration.ipynb`
