# Exploratory-data-analysis
1.Load Data
-Reads the Titanic dataset (Titanic-Dataset.csv) into a Pandas DataFrame.
2.Summary Statistics
-Uses describe() to show stats like mean, median, std, min, max, and count for all numeric and categorical columns.
3.Visualizations of Numeric Features
-Histograms → Show the distribution (spread, skewness, peaks) of numeric columns.
-Boxplots → Help spot outliers, median, and spread of each numeric feature.
4.Feature Relationships
-Correlation Matrix (Heatmap) → Shows how strongly numeric features are related (positive/negative correlations).
-Pairplot → Plots pairwise relationships of selected features, colored by survival status.
5.Pattern & Trend Detection
-Checks for missing values (e.g., Age, Cabin, Embarked have NaNs).
-Calculates survival rates by Pclass (travel class) and Sex.
6.Basic Inferences (printed as text)
-Women had higher survival rates than men.
-First-class passengers survived more often than third-class passengers.
-Higher fare passengers had better chances of survival.
-Children/younger passengers were more likely to survive.
