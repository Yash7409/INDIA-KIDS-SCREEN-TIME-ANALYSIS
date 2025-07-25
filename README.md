# 📱 Indian Kids Screen Time Analysis (2023–2024)

> Analyze the screen usage patterns of 9712 Indian children aged 8–18 across urban and rural regions, focusing on devices used, purpose of usage, and associated health impacts.

---

## 📌 Objective

This project explores:
- Daily screen time patterns across age and gender
- Urban vs rural disparities in screen use
- Device preference and type of screen activity (educational vs recreational)
- Compliance with Indian Academy of Pediatrics (IAP) guidelines
- Correlation with health impacts such as:
  - 😴 Poor Sleep
  - 👁️ Eye Strain
  - 😟 Anxiety

---

## ✅ Key Steps in the Project

### 1. 📦 Libraries Imported
- `pandas` — data handling  
- `matplotlib`, `seaborn` — data visualization  
- `numpy` — numerical operations

---

### 2. 📂 Data Loading
- **Dataset**: `Indian_Kids_Screen_Time.csv`  
- Loaded using:  
  ```python
  pd.read_csv("Indian_Kids_Screen_Time.csv")

  
---

## 🧹 3. Data Cleaning

- ✅ Replaced `"?"` with `NaN`  
- ✅ Converted columns like `Avg_Daily_Screen_Time_hr` and `Educational_to_Recreational_Ratio` to numeric  
- ✅ Dropped rows with missing values for reliable analysis  
- ✅ Extracted binary labels from multi-label health impact column:
  - `Poor_Sleep`
  - `Eye_Strain`
  - `Anxiety`

---

## 📊 Exploratory Data Analysis (EDA)

### 📈 Age Distribution
- Histogram visualized how screen time varies by age (8–18)

### ⏰ Average Screen Time by Age
- Bar plot showed increasing screen time with age, especially post-13 years

### 👧👦 Screen Time by Gender & Area
- Boxplot showed urban boys generally spend more time on screens

### 📺 Primary Device Usage
- Smartphones dominate screen usage, followed by TVs and tablets

### 🚫 IAP Guideline Compliance
- Countplot revealed the **majority exceed** Indian Academy of Pediatrics (IAP) recommended screen time
- Rural children showed a higher violation rate

### ⚠️ Health Impact Correlation
- Heatmap revealed:
  - High screen time ⟶ **Poor Sleep**
  - High screen time ⟶ **Eye Strain**
  - High screen time ⟶ **Anxiety**

---

## 🧠 Insights

- Screen time **steadily increases with age**
- **Overuse is common** across both rural and urban populations
- **Smartphone** is the most used device
- High screen time **strongly correlates with negative health outcomes**

---

## 💡 Recommendations

### 👪 For Parents
- Limit screen use, especially during evenings
- Promote outdoor play and offline hobbies

### 🏫 For Schools
- Educate students on screen hygiene and digital well-being
- Balance screen-based learning with real-world interaction

### 🏛️ For Policymakers
- Launch public awareness initiatives around healthy screen habits
- Encourage development of screen monitoring tools for families

---

## 📎 License
This project is for educational, analytical, and awareness-building purposes, using simulated data modeled on recent trends in India (2023–2024).
