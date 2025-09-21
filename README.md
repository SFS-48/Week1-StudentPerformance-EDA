# Week1-StudentPerformance-EDA

## Project Overview
This project analyzes student exam scores to uncover patterns based on **gender**, **parental education level**, **lunch type**, and **test preparation course**. The analysis is performed on the **Students Performance in Exams** dataset from Kaggle.

The goal is to practice **data handling**, **exploratory data analysis (EDA)**, and **data visualization** using Python.

---

##  Objective
- Explore the dataset structure and understand data types.
- Analyze how categorical features affect numerical scores (Math, Reading, Writing).
- Visualize trends and distributions with bar plots, box plots, and histograms.
- Derive meaningful insights to summarize student performance.

---

## 🛠 Tools & Technologies
- **Python** (Programming language)
- **Google Colab** (Notebook environment)
- **Libraries:**
  - pandas – data handling
  - matplotlib & seaborn – visualization

---

##  Dataset
**Source:** [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

**Key Features:**
- gender – Male or Female
- race/ethnicity
- parental level of education – e.g., Bachelor's degree, High school
- lunch – Standard or Free/Reduced
- test preparation course – None or Completed
- math score , reading score , writing score – Student exam scores

---

## Stepwise Approach

### Step 1: Upload and Load Dataset
- Used files.upload() in Colab to upload the CSV file.
- Loaded the dataset into a pandas DataFrame.

### Step 2: Explore the Data
- Checked dataset info (df.info()) and summary statistics (df.describe()).
- Identified unique values in categorical columns.

### Step 3: Check for Missing Values
- Verified dataset has no missing/null values.

### Step 4: Analyze Score Patterns
- Calculated average scores grouped by:
  - Gender
  - Lunch type
  - Test preparation course
  - Parental education level

### Step 5: Visualize the Data
- **Boxplots** for gender vs math scores.
- **Bar plots** for lunch type, test preparation, and parental education vs average scores.
- **Histograms** for distribution of all scores.

### Step 6: Summarize Insights
Key Findings:
- **Gender Difference:** Females perform better in reading and writing; males slightly better in math.
- **Lunch Effect:** Students with standard lunch score higher than those with free/reduced lunch.
- **Test Preparation:** Completing the test preparation course boosts reading and writing scores.
- **Parental Education:** Higher parental education correlates with better student performance.
- **Score Distribution:** Most students score between 60–80, with a few outliers.

---

## Visualization
All visualizations are created using matplotlib and seaborn:
- Boxplots, bar plots, and histograms.
- Clear titles, axis labels, and color schemes for readability.

---

## How to Use
1. Clone or download the repository.
2. Open the notebook Week1-StudentPerformance-EDA.ipynb in Google Colab.
3. Upload StudentsPerformance.csv when prompted.
4. Run all cells to view analysis and visualizations.

---
