# Movie Recommendation System


## Project Overview

Welcome to **Movie Match**, your personalized movie recommendation system! Powered by the Close Match algorithm, Movie Match offers highly accurate movie suggestions based on your preferences.

## Dataset

For this project, I utilized the dataset from the YBI Foundation Kaggle repository. You can access the dataset [here](https://github.com/YBIFoundation/Dataset/raw/main/Customer%20Purchase.csv). This dataset contains comprehensive information about movies, user ratings, and other relevant features necessary for building our recommendation system.

How It Works

- Close Match Algorithm: Movie Match uses the Close Match algorithm to identify approximate string matches, accommodating minor input variations such as typos or incomplete titles.
- Personalized Recommendations: Input your favorite movie, and Movie Match will provide you with a curated list of movie recommendations tailored just for you.

## Usage

To get your personalized movie recommendations:
1. Click on the dataset link above to access our movie database.
2. Input your favorite movie into Movie Match.
3. Enjoy a handpicked selection of movies matched to your unique taste!

To explore the Colab notebook for detailed code implementation and analysis, click [here](https://colab.research.google.com/github/virajbhutada/ybi_foundation-task/blob/main/Movie%20Recommendation%20System/Movie_Recommendation_System_Colab%20(1).ipynb)

## Feedback

I value your feedback! If you have any questions, suggestions, or issues, please feel free to contact me.

Enjoy your cinematic journey with Movie Match!

----

# Customer Purchase Prediction & Micro-Numerosity Analysis


## Project Overview

Welcome to the Customer Purchase Prediction & Micro-Numerosity Analysis project! In this project, we explore the fascinating realm of predicting customer purchase behavior and delve into the insights offered by Micro-Numerosity Analysis.

## Dataset
For this project, the dataset is sourced from the YBI Foundation Kaggle repository. You can access the dataset [here](https://github.com/YBIFoundation/Dataset/raw/main/Customer%20Purchase.csv). This dataset comprises detailed information about customers, including demographic details and reviews, essential for constructing our predictive model.

## How It Works
### Micro-Numerosity Analysis
- The project utilizes Micro-Numerosity Analysis to understand the impact of small-scale numerical features on customer purchase predictions.
  
### Predictive Modeling
- A Random Forest Classifier is employed to predict customer purchase behavior based on demographic and review-related features.

## Steps

### Data Import and Exploration
- Imported necessary libraries and loaded customer data.
- Explored the dataset to understand its structure and features.

### Data Preprocessing
- Defined target variable (y) and feature variables (X).
- Encoded categorical variables for modeling.

### Train-Test Split
- Split the dataset into training (80%) and testing (20%) sets.

### Model Selection and Training
- Chose a Random Forest Classifier for purchase prediction.
- Trained the model using the training set.

### Model Evaluation
- Used the trained model to make predictions on the test set.
- Evaluated the model accuracy using confusion matrix, accuracy score, and classification report.

### Feature Importance Visualization
- Visualized the importance of each feature using a bar chart.
- Identified key factors influencing purchase predictions.

### Confusion Matrix Heatmap
- Plotted a heatmap to illustrate model performance via a confusion matrix.
- Analyzed true positives, true negatives, false positives, and false negatives.

### ROC Curve and AUC
- Calculated and visualized the ROC curve and AUC to assess model discrimination.
- Evaluated the trade-off between true positive rate and false positive rate.

### Distribution of Predicted Probabilities
- Examined the distribution of predicted probabilities for positive class predictions ('Yes').
- Explored the model's confidence levels in predicting customer purchases.

## Key Takeaways
- Achieved an accuracy of 60% on the test set.
- Feature importance analysis provided insights into influential factors.
- Confusion matrix heatmap detailed model performance across different prediction categories.
- ROC curve and AUC quantified the model's discriminative power.
- Distribution of predicted probabilities shed light on model confidence.

## Next Steps
- Consider model refinement through hyperparameter tuning.
- Explore additional features or engineering for enhanced predictive power.
- Iterate on the analysis to improve overall model performance.

## Usage
To explore the Colab notebook for detailed code implementation and analysis, click [here](https://colab.research.google.com/github/virajbhutada/ybi_foundation-task/blob/main/Micro_Numerosity_Analysis_Customer_Purchase_Prediction.ipynb#scrollTo=xZkOqL3Bu1SL).




