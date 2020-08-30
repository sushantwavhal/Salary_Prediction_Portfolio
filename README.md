# Salary Prediction Portfolio

## DEFINE THE PROBLEM
For this Salary prediction portfolio I chose to examine 1 million job records along with their features such as **Job Type, Major, Degree, Industry, Years of Experience, Distance from the metropolis area** and the given **SALARY**. Based on this data, I'm going to build some predictive models and choose the best model (having lowest MSE) and use it to predict salaries of another 1 million jobs based on their features.

### PROJECT OUTLINE:

- Load the data, Understand the data, Find relationships between attributes
- Establish a baseline model, Engineer features, Optimize the data features
- Select the best model with the lowest Evaluation metric and
- **Predict salaries of another 1 million job features using the selected model**

## DISCOVER DATA
The Salary distribution histogram plot!

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/Salary_dist.png)

### DISTRIBUTION OF CATEGORICAL VARIABLES IN THE DATASET
Following are the Job types in this dataset and the box plots represent their distribution across the whole data.

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/jt_box.png)

Following are the Degree types in this dataset and the box plots represent their distribution across the whole data.

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/deg_box.png)

Following are the Major types in this dataset and the box plots represent their distribution across the whole data.

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/maj_box.png)

Following are the Industry types in this dataset and the box plots represent their distribution across the whole data.

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/ind_box.png)

### DISTRIBUTION OF THE NUMERICAL VARIABLES IN THE DATASET

Following is a line plot of Years of Experience(yearsExperience) against the Salary

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/exp_line.png)

Following is a line plot of Distance from Metropolis(milesFromMetropolis) against the Salary

![image](https://github.com/sushantwavhal/Salary_Prediction_Portfolio/blob/master/Plots/dist_lin.png)
