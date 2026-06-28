## Linear Regression to predict home values

## Internship in the technology department at SkillCraft

### Track: Machine Learning
### Task 1 of 11

## Overview of the project

The purpose of this project is create a linear regression model that predicts home values based on 3 features:


- GrLivArea - living area (above ground)
- BedroomAbvGr - number of bedrooms
- FullBath - number of full bathrooms


The end goal of this project is to develop a machine learning (ML) model that predicts home values based on the features mentioned above, and measure the performance of the model using standard regression metrics.


## Dataset

The dataset used in this case is called "House Prices - Advanced Regression Techniques."

The following files were used to create the model:


- train.csv
- test.csv
- sample_submission.csv
- data_description.txt


## Technologies Used

- Python
- Google Colab (JC)
- Pandas (3.5.1)
- NumPy (1.21.6)
- Matplotlib (3.4.3)
- Seaborn (0.11.2)
- Scikit-learn (0.24.2)


## Workflow Steps

1. Import Libraries
2. Load dataset
3. Explore dataset
4. Handle missing data
5. Select features
6. Split dataset into training and validation sets
7. Train the linear regression model
8. Use the model to predict the value of homes
9. Evaluate the model's accuracy
10. Visualize results


## Features Selected for Use in the Model

| Feature(s)  | Description |
| ------------ |-------------|
| GrLivArea   | Above ground living area (square feet)  |
| BedroomAbvGr| Number of bedrooms |
| FullBath    | Number of full bathrooms   |

Target variable:


- SalePrice


## Model Performance

- MAE = 35,788.06
- MSE = 2,806,426,667.25
- RMSE = 52,975.72
- R2 = 0.6341


## Data Visualizations
The data visualizations created as part of this project include:


1. Correlation heatmap (Map)
2. Actual vs. predicted home sales prices (Graph)
3. Residual Plot (Graph)

### Conclusion

The model currently achieves predictions of house pricing with the line of best fit established by the linear regression model, using features selected from the MLS records to produce an overall R² score of **0.63**, providing a fair level of accuracy. Future potential for improvements exist once we add features such as neighborhood, garage, overall quality, and year built to the data set.

---

### Author

This project was created as part of the SkillCraft Technology Machine Learning Intern Program.   
