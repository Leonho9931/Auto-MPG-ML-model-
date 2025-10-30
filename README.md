## 🚗 Auto-MPG City-Cycle Fuel Consumption Prediction using Support Vector Regression (SVR)
### Problem Statement

Fuel efficiency, measured in miles per gallon (MPG), is a critical indicator of vehicle performance and environmental impact. Predicting MPG based on vehicle characteristics helps manufacturers and consumers understand how design factors (such as engine size, horsepower, and weight) influence fuel consumption. The objective of this project is to develop a machine learning model that accurately predicts a car’s city-cycle MPG using several numerical and categorical input features from the Auto-MPG dataset.

### Feature Selection Using Pearson’s Correlation

1. To improve model performance and reduce overfitting, Pearson’s correlation coefficient was applied to select the most relevant features.
This method measures the linear relationship between each input feature and the target variable (MPG).
2. Features with high positive or negative correlation to MPG were retained, as they contribute most strongly to prediction accuracy.
3. Features with low or near-zero correlation were dropped to minimize noise and redundancy.

### Model Evaluation

The line graph above compares the actual MPG values (orange line) and the predicted MPG values (blue line) for a test dataset using SVR.
<img width="885" height="376" alt="image" src="https://github.com/user-attachments/assets/823a6045-83f0-4dbd-93f4-55b9ccbdcd0b" />

Interpretation:
1. The two curves closely overlap, showing that the SVR model predicts city-cycle MPG values accurately for most samples.
2. Small deviations indicate areas where the model might slightly under- or over-estimate fuel consumption, possibly due to non-linear or unobserved factors (like aerodynamic design or tire resistance).
