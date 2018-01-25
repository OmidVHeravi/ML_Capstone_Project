
# Machine Learning Nanodegree Capstone

## Allstate Insurence Severity Detection 

### Project Overview

Allstate insurence, the second largest personal lines insurer in the United States and the largest that is publicly held, approximatly 16 million households. For this challenge, Allstate has provided vast dataset on its insurence claims, several dozen key attributes, thorugh which data analysis could help uncover the underlying pattern in detecting the severeness of an insurance claim. Data is provided in the form of categorical, continues format. This challenge, is a very great problem to tackle with machine learning. The automation of reviweing insurance claims will improves productivity and efficiency which will inevitably lead to happier customers and overall satisfaction. 

### Problem Statement

The challenge requires the data scientists to best predict the label column, or 'loss' as indicated in the data provided. Since the dataset contains both categorical and continious data along with several dozen attributes, and several hundread rows of insurence claim instances, the final algorithm will have to take these constraints into consideraiton. And as such, I belive that a mix of decision tree, supervised regression algorithm will best be able to solve this challenge. For example as refrence to some of the publicly avialable best performing kernels in the challenge page on kaggle can show that XGBoost, MLP, and such perform the best. 

### Challenge Roadmap

** Understanding the Dataset **
 * Data Shape 
 * Skew 
 * Mean, STD deviation, Max, etc. 
 
** Data Visualization **
 * Scatter Plots
 * Correlation
 * Density Plots
 
** Data Processing ** 
 * Transformation
 * One-Hot encoding
 * Train/Test Data preparation
 
** Model Evalaution **
 * Algorithm implementations
 * Model Evaluations
 * Model Predicitons
 * Model Analysis
 
** Appendix **
 * Conclusion
 * Personal Thoughts
 * Thanks and Appreciations

### Project Highlights

Check the report.md for in depth analysis of the challenge and it's highlights.

### Libraries and Dependencies used


 * Sklearn
    * metrics
    * Linear Regression
    * GradientBoosting
    * DecisionTree
    * SGD
    * RandomForest
    * MLP 
 * Numpy
 * Pandas
 * Matplotlib
 * Seaborn

### Core Files

train.csv = train Data provided by Allstate Challenge. The original Shape of the data is in (188318, 131). This dataset also includes the 'loss' column by which we'll be completing the challenge.

test.csv = test data provided by the challenge. The original shape of the data is in (125546, 130). This datset however does not include the 'loss' column. also train set does not include as munch insurance isntance claims as much as the train dataset. 

CapstoneProject.ipynb = This is the main notebook, it includes all the analysis, model building, and predicting. 

### Supplementary Refrences and  Link

Kaggle Challnege: https://www.kaggle.com/c/allstate-claims-severity
Refrences: 
* metric: https://medium.com/human-in-a-machine-world/mae-and-rmse-which-metric-is-better-e60ac3bde13d, https://www.kaggle.com/c/allstate-claims-severity/discussion/24520#140255
* Major thanks and appreiciation for the influence to: https://www.kaggle.com/sharmasanthosh/exploratory-study-on-ml-algorithms, https://www.kaggle.com/snmateen/simple-eda-feature-transformations, https://www.kaggle.com/laurae2/sneak-peak-at-the-data-1, https://www.kaggle.com/achalshah/allstate-feature-analysis-python


```python

```
