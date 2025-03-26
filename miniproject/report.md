# Pixar Movie Box Office Prediction

## Data Source and Description
- **Source:** Kaggle dataset
- **Content:** The dataset includes details on every Pixar movie released in theaters, such as:
  - Box office earnings (worldwide)
  - Rotten Tomatoes rating
  - Movie name
  - Total budget for the movie
  - Release date
- **Objective:** To analyze the relationship between the budget of a movie and its box office earnings, specifically to predict if a higher budget leads to higher earnings.

---

## Research Question
**Hypothesis:** There is a positive correlation between movie budgets and box office earnings.
- "The higher the budget of a Pixar movie, the more successful it is at the box office."

---

## Target Variable
- **Box office earnings (worldwide)** – The dependent variable that you're trying to predict.

---

## Key Predictor Features
1. **Budget** – The cost of producing the movie.
2. **Rating** – This could refer to movie ratings from Rotten Tomatoes or other sources, which might influence a movie’s popularity.
3. **Release date** – The timing of the release might affect its performance in the box office (e.g., release during the holiday season).

---

## Data Cleaning Process
- Removed any missing or null values that could negatively impact the analysis.
- Identified and removed any outliers that could skew results.
- Dropped columns that were irrelevant to the final analysis.

---

## Training Process and Model Evaluation
- **Modeling:** A quick default builder was used to create the prediction model.
- **Evaluation Metric:** The R² score achieved was **91.307%**, which indicates a very strong positive correlation and high predictive accuracy.
- **Potential Improvements:** The model could be further improved by removing more unnecessary columns.




