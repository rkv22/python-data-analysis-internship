# 🚢 Data Science with Python Internship
## Task 2 — Titanic Dataset: Survival Pattern Analysis & Visualization

---

## 📋 Overview

This task involves exploratory data analysis (EDA) and visualization of the Titanic dataset. The goal is to uncover survival patterns based on key passenger attributes such as **gender**, **passenger class**, and **age**.

---

## 🛠️ Requirements

Install the required Python libraries before running the script:

```bash
pip install pandas matplotlib seaborn numpy
```

| Library      | Purpose                          |
|--------------|----------------------------------|
| `pandas`     | Data loading and manipulation    |
| `numpy`      | Numerical computations           |
| `matplotlib` | Base plotting library            |
| `seaborn`    | Statistical data visualization   |

---

## 📂 Dataset Setup

- Download the **Titanic Dataset** (CSV format).
- Place `Titanic-Dataset.csv` in the **same folder** as the script.

**Key columns used:**

| Column      | Description                              |
|-------------|------------------------------------------|
| `Survived`  | Survival status (0 = No, 1 = Yes)        |
| `Pclass`    | Passenger class (1st, 2nd, 3rd)          |
| `Sex`       | Gender of the passenger                  |
| `Age`       | Age of the passenger                     |
| `SibSp`     | Number of siblings/spouses aboard        |
| `Parch`     | Number of parents/children aboard        |
| `Fare`      | Ticket fare                              |

---

## 📊 Charts Generated

### Chart 1 — Survival by Gender
**File:** `chart1_survival_by_gender.png`

- Bar chart comparing survival counts for **male** vs **female** passengers.
- Key insight: Female passengers had a significantly higher survival rate.

---

### Chart 2 — Survival by Passenger Class
**File:** `chart2_survival_by_class.png`

- Bar chart showing survival distribution across **1st**, **2nd**, and **3rd** class.
- Key insight: 1st class passengers were far more likely to survive than 3rd class.

---

### Chart 3 — Age Distribution (Histogram)
**File:** `chart3_age_histogram.png`

- Histogram of passenger ages across the entire dataset.
- Key insight: The majority of passengers were between **20–40 years old**.

---

### Chart 4 — Survival by Age Group *(Bonus)*
**File:** `chart4_survival_by_age_group.png`

- Passengers grouped into age bands (e.g., Child, Teen, Adult, Senior).
- Key insight: Children had a relatively higher survival rate compared to adults.

---

### Chart 5 — Heatmap: Gender × Class Survival *(Bonus)*
**File:** `chart5_heatmap_gender_class.png`

- Heatmap showing survival rates across all combinations of **gender** and **passenger class**.
- Key insight: 1st class females had the highest survival rate; 3rd class males the lowest.

---

## 🔍 Key Findings

1. **Gender was the strongest predictor of survival** — women were prioritized during evacuation ("women and children first").
2. **Passenger class strongly correlated with survival** — higher class meant better access to lifeboats.
3. **Age played a secondary role** — children showed slightly higher survival rates; elderly passengers fared worse.
4. **The intersection of gender and class** reveals the starkest contrasts in survival probability.

---

## ▶️ How to Run

```bash
python titanic_analysis.py
```

On successful execution, the terminal will display:

```
✅ Task 2 Complete!
============================================================
```

All five chart images will be saved in the same directory as the script.

---

## ✅ Deliverables

- [x] `chart1_survival_by_gender.png`
- [x] `chart2_survival_by_class.png`
- [x] `chart3_age_histogram.png`
- [x] `chart4_survival_by_age_group.png` *(bonus)*
- [x] `chart5_heatmap_gender_class.png` *(bonus)*

---

*Data Science with Python Internship — Task 2*
