# Titanic Dataset - Exploratory Data Analysis (EDA)

## 🏷️ Title
**Titanic Dataset - Exploratory Data Analysis**

## 📋 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries like Pandas, Matplotlib, and Seaborn. The goal is to analyze and visualize various aspects of the dataset to understand survival trends based on different demographic and ticket-related features.

## 📂 Dataset Overview
- **Source:** Titanic Dataset
- **Number of Records:** 891
- **Features:**
  - PassengerId
  - Survived
  - Pclass
  - Name
  - Sex
  - Age
  - SibSp
  - Parch
  - Ticket
  - Fare
  - Cabin
  - Embarked

## 📊 Summary Statistics

### Numeric Columns
- **Age:** Mean = 29.7, Median = 28, Max = 80
- **Fare:** Mean = 32.2, Max = 512.3
- **SibSp & Parch:** Most passengers traveled alone
- **Pclass:** Majority in 3rd class

### Categorical Columns
- **Sex:** 577 males, 314 females
- **Embarked:** Majority from Southampton
- **Cabin:** Many missing values (687 nulls)

## 📈 Key Visualizations

### 1. Survived
- **Bar Plot:** Shows majority of passengers did not survive.
- **Box Plot:** Binary distribution with median at 0.

### 2. Pclass
- **Bar Plot:** Most passengers were in 3rd class.
- **Box Plot:** Discrete distribution of classes.

### 3. Sex
- **Bar Plot:** More male passengers than female.
- **Insight:** Female passengers had a higher survival rate.

### 4. SibSp
- **Bar Plot:** Most passengers had 0 siblings/spouses aboard.
- **Box Plot:** Slightly better survival for those with small families.

### 5. Parch
- **Bar Plot:** Most passengers had 0 parents/children aboard.
- **Box Plot:** Passengers with family had slightly better chances.

### 6. Cabin
- **Insight:** Over 77% missing values. Low utility for correlation.

### 7. Embarked
- **Bar Plot:** Majority of passengers embarked from Southampton.

### 8. Age
- **Histogram:** Most passengers were young adults (20-40).
- **Box Plot:** Median ~28 years; some outliers over age 60.

### 9. Fare
- **Histogram:** Right-skewed distribution.
- **Box Plot:** Most paid between 7–31 units; few paid >500.

### 10. Correlation Heatmap
- **Insight:** Survival is positively correlated with Fare and Sex (female), negatively with Pclass.

## 💡 Summary of Insights
- Females and higher-class passengers had higher survival rates.
- Traveling with family (SibSp or Parch > 0) slightly improved survival chances.
- Fare and Pclass showed a strong influence on survival.
- Age distribution and class interplay also affected survival probabilities.
