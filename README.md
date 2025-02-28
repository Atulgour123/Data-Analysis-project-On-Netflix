# Data-Analysis-project-On-Netflix
This project performs an exploratory data analysis (EDA) and builds a linear regression model to predict IMDb ratings.

**Data Loading and Cleaning:**
- Loads a dataset (presumably movie data) from a CSV file.
- Handles missing values by removing rows with any missing data.
- Renames columns 'imdbAverageRating' to 'Rating' and 'imdbNumVotes' to 'Popularity' for clarity.

**Exploratory Data Analysis (EDA):**
- Visualizes missing values using a heatmap.
- Analyzes the distribution of IMDb ratings using histograms and box plots.
- Calculates and visualizes the correlation between numerical features using a heatmap.
- Explores categorical features like 'type' and 'genres' using count plots and bar plots to show their frequencies.

**Model Training:**
- Selects 'releaseYear' and 'Popularity' as features for predicting 'Rating'.
- Splits the dataset into training and testing sets (80/20 split).
- Trains a linear regression model on the training data.
- Makes predictions on the test data.

**Model Evaluation:**
- Evaluates the model's performance using Mean Absolute Error (MAE), R-squared (R2), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).  The printed values provide quantitative measures of the model's accuracy.
