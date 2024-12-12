# NFL Big Data Bowl 2025 Project

## Description
This project focuses on analyzing player tracking data to understand NFL team tendencies during critical third-down plays. Using PySpark and machine learning, we explored the factors influencing the decision to run or pass on third down, aiming to provide actionable insights for coaches and analysts.

### Key Features:
- **Objective:**
  - Analyze third-down play tendencies in the NFL during the first nine weeks of the 2024 season.
  - Predict whether a play will be a run or pass based on pre-snap information.
  - Generate actionable insights to improve decision-making during games.

- **Highlights:**
  - PySpark for large dataset processing and feature engineering.
  - Machine learning models (Random Forests, Gradient Boosted Trees, Logistic Regression, etc.).
  - Traditional statistical analysis for better insight into team strategies.

---

## Contents
1. **Presentation:** [`2025 NFL Big Data Bowl.pptx`](2025%20NFL%20Big%20Data%20Bowl.pptx)
2. **Project Notebook:** [`2025 NFL Big Data Bowl.ipynb`](2025%20NFL%20Big%20Data%20Bowl.ipynb)
3. **Project Report:** [`BDA Project Report Final Draft.docx`](BDA%20Project%20Report%20Final%20Draft.docx)

---

## Data and Methodology
- **Dataset:**
  - Contains data from 136 games during weeks 1–9 of the 2024 NFL season.
  - 16,124 plays (3,279 on third downs): 80% pass plays, 20% run plays.
  - Features include field position, offensive formation, receiver alignment, and yards-to-go.

- **Analysis Tools:**
  - **PySpark:** Efficient handling of large datasets.
  - **Machine Learning Models:**
    - Decision Trees
    - Random Forests
    - Logistic Regression
    - Gradient Boosted Trees
  - **Traditional Statistics:** Insights into play-calling tendencies using formations and field position.

- **Key Findings:**
  - Teams pass 80% of the time on third downs.
  - The Philadelphia Eagles have the highest run rate on third downs (~40%).
  - Pass likelihood increases with more than four yards needed for a first down.

---

## Usage Instructions
1. **Run the Project Notebook:**
   - Requires a PySpark environment.
   - Install dependencies via `pip install pyspark`.

2. **View Presentation and Report:**
   - Presentation provides a summary of findings and visuals.
   - Report includes detailed methodology and results.

3. **Data Preprocessing:**
   - Binary target column `isRun` (1 for run, 0 for pass).
   - Filter third-down plays with 10 or fewer yards-to-go for cleaner analysis.

---

## Results and Insights
- **Model Performance:**
  - Best F1 score for run predictions: 0.83.
  - Ensemble models outperformed individual models in predicting play outcomes.

- **Key Insights:**
  - Shotgun formation: Philadelphia Eagles run 75% of the time on third downs with ≤3 yards to go.
  - Traditional statistical methods provided better insights for strategic recommendations compared to machine learning in some cases.

---

## Conclusion
This project demonstrates the power of combining advanced machine learning techniques with traditional data analytics for actionable football insights. While machine learning models were effective, traditional analysis often offered clearer strategic insights, emphasizing the importance of balancing both approaches.

### Future Work:
- Explore additional features from player tracking data.
- Develop more advanced models to predict the location of runs and passes.
- Test real-time analytics for in-game decision-making.

---
