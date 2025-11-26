# Student Performance Investigation: Data Visualization Module

## 📖 Overview
This repository contains the complete lesson plan and resources for an interactive training module designed to teach **Google Looker Studio**.  
In this scenario-based lesson, learners act as **Junior Data Analysts** for a school district, tasked with visualizing student test scores to uncover insights about educational performance.

---

## 🎯 Learning Objectives
- **Connect Data**: Link Google Sheets data sources to Looker Studio.  
- **Calculate Metrics**: Configure aggregation methods (Average, Min, Max, Median) correctly.  
- **Visualize Trends**: Create and customize Scorecards, Bar Charts, Donut Charts, and Scatter Plots.  
- **Analyze Distributions**: Build advanced Box Plots using calculated fields to visualize statistical spread.  
- **Implement Interactivity**: Use filters to slice data dynamically.  
- **Design Dashboards**: Organize multiple visualizations into a cohesive, single-page report.  

---

## 📂 Repository Contents
| File Name | Description |
|-----------|-------------|
| `intro.html` | **Start Here**: The landing page that sets the scenario and guides learners through the critical data setup process. |
| `lesson_plan.html` | **Main Lesson**: The step-by-step interactive guide with task instructions and visual references. |
| `StudentPerformance ver2.csv` | **Archived Data**: The raw dataset used for this lesson (contains the unique student ID). |

---

## 🚀 Getting Started

### 👩‍🏫 For Instructors
1. Host the `.html` files or upload them directly to your LMS.  
2. Direct students to open `intro.html` first.  
⚠️ **Critical Note**: Ensure students use the Google Sheet link provided in the lesson for the smoothest experience, rather than uploading the raw CSV, to avoid connection issues.  

### 👨‍🎓 For Learners
1. Open `intro.html` in your browser.  
2. Follow the instructions to copy the Corrected Dataset link.  
3. Proceed to `lesson_plan.html` to begin your investigation.  

---

## 🛠️ Data Preparation Notes
- This lesson requires a specific version of the dataset (`StudentPerformance ver2.csv`) which includes a **unique identifier column (`student`)**.  
- **Recommended Data Source**: Google Sheets  

### 🔑 Key Fields
- `student` → Unique ID (Do not aggregate)  
- `math score`, `reading score`, `writing score` → Numeric  
- `test preparation course`, `parental level of education` → Categorical  

---

## 📊 Visualizations Covered
- **KPI Scorecards**: High-level averages for Math, Reading, and Writing.  
- **Bar Chart**: Analyzing the impact of parental education.  
- **Donut Chart**: Visualizing demographic composition.  
- **Scatter Plot**: Correlating Reading vs. Writing scores.  
- **Box Plot**: Comparing score distributions by gender (requires calculated fields).  

---

## 📜 License
This project is open for **educational use**.

---

## 🙌 Acknowledgements
This project was made with the assistance of **Google Gemini**.
