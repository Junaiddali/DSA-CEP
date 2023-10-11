## Group members
Anousha-20SW030 |
Junaid Ali-20sw066 |
Sarosh-20SW128 

## Title: Urban Mobility

## Description

Welcome to the Urban Mobility Insights repository, where data takes the driver's seat in solving key challenges of urban mobility. This collection of data-driven solutions offers a comprehensive approach to enhance city living. From identifying high-congestion areas based on real-time traffic data and weather patterns to promoting sustainable transportation modes, optimizing emergency responses during extreme weather conditions, and understanding the role of different vehicle types in congestion, our repository is a hub of insights rooted in analytics. Graphs and visualizations accompany each solution, providing a clear picture of spatial congestion patterns, mode distribution across weather conditions, optimized emergency response routes, and the contribution of vehicle types to congestion. Join us on the journey to make cities more efficient, sustainable, and responsive through the lens of data. Explore, contribute, and drive change in urban mobility!

## Overview

This GitHub repository contains code for predicting traffic congestion using a Random Forest Regressor. The project is implemented using Google Colab, a powerful and collaborative Python environment for data science and machine learning.

## Environment

- **IDE:** Google Colab
  - Google Colab provides a cloud-based environment that allows for easy collaboration and access to powerful computing resources, making it an ideal choice for data science and machine learning projects.

## Dataset

The project utilizes the [Urban Mobility and Traffic Patterns in Smart Cities dataset](https://www.kaggle.com/datasets/slmsshk/urban-mobility-n-traffic-patterns-in-smart-cities) from Kaggle. This dataset contains valuable features related to traffic patterns and congestion in urban areas.

## Libraries Used

The following Python libraries are utilized in this project:

- **Pandas (pd):** Used for data manipulation and analysis.
- **Matplotlib.pyplot (plt):** Employed for creating visualizations, particularly plots and charts.
- **Seaborn (sns):** A data visualization library based on Matplotlib that enhances the aesthetics of plots.
- **Scikit-learn:**
  - **Train-Test Split:** From `sklearn.model_selection`, used to split the dataset into training and testing sets.
  - **StandardScaler:** From `sklearn.preprocessing`, applied for standardizing feature variables.
  - **OneHotEncoder:** Also from `sklearn.preprocessing`, utilized for one-hot encoding categorical variables.
  - **RandomForestRegressor:** From `sklearn.ensemble`, the model employed for predicting traffic congestion.
  - **Mean Absolute Error (MAE):** From `sklearn.metrics`, used as the evaluation metric for the model.

## Usage

1. Open the provided Jupyter notebook in Google Colab.
2. Run the notebook cells sequentially to load data, preprocess, train the Random Forest Regressor, and make predictions.
3. Analyze the results and evaluate the model's performance using mean absolute error.

## Note

Ensure that you have downloaded the [Urban Mobility and Traffic Patterns in Smart Cities dataset](https://www.kaggle.com/datasets/slmsshk/urban-mobility-n-traffic-patterns-in-smart-cities) and update file paths accordingly. Additionally, check for any dependencies that may not be explicitly mentioned in the code.

Feel free to explore and modify the code to suit your specific requirements.

Happy coding!
