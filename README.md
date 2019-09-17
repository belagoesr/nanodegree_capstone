# Capstone Project for Udacity Data Science Nanodegree

## Project Motivation:
The first part of this project analyses demographics data for customers of a mail-order sales company in Germany and compare it against demographics data for the general population. The main goal is to identify segments of the population that composes the core of the customers of the company. In the second part, given a dataset of individuals that were targeted for a mailout campaign, a machine learning model will be built to predict whether or not it will be worth it to include that person in the campaign (if they are likely to become customers for the company).


## Files
- **Arvato Project Workbook.ipynb**: Jupyter notebook with project code
- **Arvato Project Workbook.html**: html file with same content as notebook.

## Libraries
- scikit-learn:  https://scikit-learn.org/stable/index.html
- seaborn: https://seaborn.pydata.org/
- pandas: https://pandas.pydata.org/
- numpy: https://numpy.org/

## Project Structure
### Part 1: Customer Segmentation
#### Data Cleaning:
- *Assessing missing data*
- *Feature Encoding*
- *Feature Scaling*
- *Imputing missing values*

#### Dimensionality Reduction
- *Dimensionality Reduction (PCA)*

#### Clustering:
- *Clustering (KMeans)*

### Part 2: Supervised Learning Model
- *Class Imbalance of the dataset / Downsampling approach*
- *Training models*
- *Parameters tuning*
- *Model validation (KFold)*
- *Conclusion*

## Results
The metric used is the area under the curve. Final model is validated using KFold cross-validation and has an mean AUC of 0.77.


