# Mental Health Patient Outcome Dashboard

This Power BI dashboard provides an interactive analysis of mental health treatment outcomes using anonymized patient data. It allows users to explore clinical trends, treatment responses, therapy types, medication usage, and soft metrics such as mood, sleep quality, and emotional states. The dashboard is structured to support both high-level summaries and individual-level insights for better healthcare decision-making.

---

## 🔎 Overview

- **Tool Used:** Power BI Desktop
- **Dataset Size:** 500 patients
- **Data Type:** Structured tabular data with numeric scores, categorical diagnosis, and text fields
- **Goal:** Understand treatment outcomes and patterns across clinical and behavioral dimensions

---

## 📁 Dataset Fields

### Patient Demographics
- `Total Patients`
- `Age`
- `Gender`

### Clinical Diagnosis & Treatment Strategy
- `Diagnosis`: Panic Disorder, Generalized Anxiety, Bipolar Disorder, Major Depressive Disorder
- `Therapy Type`: CBT, DBT, Mindfulness-Based, Interpersonal Therapy
- `Medication`: SSRIs, Antipsychotics, Benzodiazepines, etc.
- `Treatment Progress (1–10)`
- `Adherence to Treatment (%)`
- `Physical Activity (hrs/week)`

### AI-Inferred Sentiment
- `AI-Detected Emotional State`: Happy, Stressed, Depressed, Excited, Anxious, Neutral

### Patient-Reported Experience
- `Symptom Severity (1–10)`
- `Mood Score (1–10)`
- `Sleep Quality (1–10)`
- `Stress Level (1–10)`

### Outcome Category
- `Outcome`: Improved, No Change, Deteriorated

---

## 🧠 Dashboard Sections

### 1. **Filters Panel**
- Age (slider)
- Gender
- Diagnosis
- Therapy Type
- Medication
- AI-Detected Emotional State
- Outcome
- Month (if added)

### 2. **Demographics**
- Total patient count
- Age group breakdown (Teenagers to Older Adults)
- Gender distribution

### 3. **Clinical Information**
- Diagnosis frequency %
- Therapy type frequency %
- Medication distribution
- AI Emotional State frequency
- Treatment adherence & physical activity
- Treatment Progress (avg. score out of 10)

### 4. **Patient Scores (1–10)**
Displayed as KPI cards:
- Mood Score
- Sleep Quality
- Stress Level
- Symptom Severity

### 5. **Outcome Analysis**
- Final treatment status: Improved, No Change, Deteriorated (visualized as stacked bar %)

---

## 📌 Key Metrics

| Metric                          | Value      |
|---------------------------------|------------|
| Total Patients                  | 500        |
| Avg. Treatment Progress         | 7.00       |
| Avg. Adherence to Treatment     | 75%        |
| Avg. Physical Activity          | 5 hrs/week |
| Most Common Diagnosis           | Generalized Anxiety (27%) |
| Most Used Therapy Type          | Mindfulness-Based Therapy (26%) |
| Most Reported Emotion           | Anxious (20.4%) |
| Outcome with Highest Count      | Deteriorated (34.2%) |

---

## 💡 Highlights

- **Visual Consistency:** Unified soft violet color scheme, professional layout
- **Drillable Filters:** Quickly isolate cohorts based on emotional state, therapy, medication
- **Balanced Insight:** Mix of soft metrics and hard KPIs for a complete view
- **Realistic Use Case:** Applicable to patient outcome evaluation in real-world clinical research

---

## Features

- **Demographic Breakdown**: Visualize patient distribution by gender and age group for population-level trends  
- **Therapy & Medication Distribution**: Analyze the frequency and combination of treatment types used  
- **Patient-Reported Experience**: Track patient feedback on mood, sleep quality, stress, and symptom severity  
- **AI-Detected Emotional Trends**: Gain insight into patients' emotional states such as anxious, neutral, happy, or depressed  
- **Treatment Adherence & Progress**: Measure adherence to prescribed plans and average progress scores  
- **Outcome Tracking**: Identify how many patients improved, saw no change, or deteriorated across treatment cycles  

---

## Insights Enabled

- **Diagnosis by Age Group**: Identify which conditions are most prevalent among teenagers versus older adults  
- **Adherence vs. Emotional Outcomes**: Explore how closely following treatment affects mood, stress, and overall emotional health  
- **Therapy Effectiveness**: Compare outcome trends across therapy types to determine what works best for specific diagnoses  
- **Stress & Sleep by Demographic**: Understand how sleep quality and stress levels vary across gender and age categories  


## 🛠 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. If needed, re-link the dataset (`mental_health_diagnosis_treatment_.csv`)
3. Interact with filters to explore subsets of the data
4. Hover over charts and cards to see tooltips

---
