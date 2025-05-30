# NBA Draft Prediction with college stats - A ML approach

**Presentation**: [Click here](https://docs.google.com/presentation/d/e/2PACX-1vT5Zg7E6ThHR5z7zWHHVrwIStPbvbqeWgyDE9_u4ck0e3SkTuj46dTI8r4IIXyQnEV66o60rEgSAZ4T/pub?slide=id.g34fd5b658fc_0_111)

## Data Description

- **Source**: [Kaggle – College Basketball Players (2009–2021)](https://www.kaggle.com/datasets/adityak2003/college-basketball-players-20092021/data)
- Scope: Data from the 2018–19 to 2021–22 seasons
- Target Variable: pick (drafted or not)

## Processing:
- Filtered to one entry per player (most recent season or the season they were picked)
- Cleaned missing values and selected relevant performance metrics
- Handled class imbalance (picked ~3%) via oversampling

## Tools & Libraries Used
- Python, Jupyter Notebook
- pandas, NumPy, scikit-learn, seaborn, matplotlib
- Logistic Regression, KNN, Decision Tree, Random Forest

## Key Insights & Results
- Random Forest provided the best performance with:
- Accuracy: 99.95%
- Recall: 100% — ensuring few truly draftable players are missed
- F1 Score: 99.95%
- Oversampling significantly improved model fairness toward the minority class (picked players)

## Conclusion

Machine learning can support NBA draft scouting by identifying potential draftees using only college stats. This approach can be a helpful analytical tool when combined with traditional scouting methods.

## Future Work
- Predict draft pick position or rookie season performance (PER)
- Integrate advanced stats or team context for deeper insights
