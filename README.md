# Project-Predictive-Modeling-for-Agriculture
## Project Description

Farmers face the challenging task of choosing the right crops to plant each season, with soil condition being a crucial factor. Each crop has an ideal soil condition for optimal growth and yield. To address this challenge, we've employed machine learning to build a multi-class classification model that predicts the best crop based on soil measurements.

## Data

The dataset used in this project is named `soil_measures.csv` and contains the following columns:

- `"N"`: Nitrogen content ratio in the soil
- `"P"`: Phosphorous content ratio in the soil
- `"K"`: Potassium content ratio in the soil
- `"pH"`: pH value of the soil
- `"crop"`: Categorical values representing various crops (target variable).

The data has been preprocessed and prepared for machine learning.

## Data Exploration

The Jupyter Notebook includes code for data exploration, which covers the following:

- Data distribution analysis
- Handling missing values
- Crop distribution visualization
- Feature correlations

## Model Development

The core of this project is the development of a multi-class classification model for crop prediction. We use logistic regression with the 'multinomial' option to address the multicollinearity issue between highly correlated features.

## Model Evaluation

The model's performance is evaluated using F1-scores, and you can see the results in the Jupyter Notebook. We aim to achieve a reliable and effective model for crop selection.

## Results

The project aims to assist farmers in making informed decisions based on data, leading to improved crop yields and sustainable agriculture practices. The results demonstrate the viability of machine learning in crop selection and provide insights into improving agricultural practices.

## Conclusion

This project demonstrates the potential of machine learning in agriculture. By leveraging data and technology, we can help farmers maximize their yields, reduce costs, and make more sustainable choices. If you have any questions or would like to learn more, please don't hesitate to reach out.
