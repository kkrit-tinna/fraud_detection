# Fraud Detection

## About Dataset
This dataset is a Kaggle Dataset named **'Credit Card Fraud Detection'** 
<br><br>
It is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants. It contains two separate files, one is a training dataset and another is a test dataset for model validation.
<br><br>
This was generated using Sparkov Data Generation | Github tool created by Brandon Harris. This simulation was run for the duration - 1 Jan 2019 to 31 Dec 2020. The files were combined and converted into a standard format. 

## Project Description
* This project follows typical machine learning workflow including data cleaning, EDA, data preprocessing, feature engineering, model building, regression modeling, and model validation.
* This project uses predctive modeling -- logistics regression model and decision tree model, and compare their model accuracy and success metrics such as confusion matrix and classification report. It also includes model optimization techniques such as emsemble(random forest) and L2 regularization.
* This project leverages some popular data-analyic tools, including numpy, pandas, seaborn, and train models using sklearn package(including model selection, metrics, logistics regression, grid search and decision tree).
* This project can serve as a beginner-friendly tutorial on supervised learning, particularly using logistics regression and decision tree, process is well-documented and annotated in the jupyter notebook.

## Getting Started

### Dependencies
* The process of Analysis is stored in the Jupyter Notebook **'fraud_detection_analysis.ipynb'**.
* Pre-req Python Libraries include: numpy, pandas, maplotlib, seaborn, and sklearn.

### Installing
* You can download this project [here](https://github.com/kkrit-tinna/fraud_detection.git).

### Executing Program
* To begin, locate **'fraud_detection_analysis.ipynb'** and view codes & outputs for reference.
* **DATASETS ARE TOO LARGE FOR GITHUB STORAGE, CANNOT EXECUTE CODE**. <br>You can download this notebook and find the original datasets on [kaggles](https://www.kaggle.com/datasets/kartik2112/fraud-detection).
* Major plots are saved to the current repository for reference.

### Potential Issues
* Dataset is generated using stimulator, which can be problematic in the accuracy and reliability.
* Only one powerful features is determined, so the application of this project is limited.
  
## Resources
Learning description of this dataset <br>
@https://www.kaggle.com/datasets/kartik2112/fraud-detection<br><br>
How to Optimize Logistic Regression Performance<br>
@https://www.geeksforgeeks.org/how-to-optimize-logistic-regression-performance/#hyperparameters-in-gridsearchcv<br><br>
Logistic Regression and regularization: Avoiding overfitting and improving generalization<br>
@https://medium.com/@rithpansanga/logistic-regression-and-regularization-avoiding-overfitting-and-improving-generalization-e9afdcddd09d<br><br>
Overfitting and Regularization in Logistic Regression: <br>
@https://tung-dn.github.io/prog_class3.html#Overfitting-and-Regularization-in-Logistic-Regression


## Author
Yifei Shi


## Version History
* 0.2
    * Modified model optimization part, dominant feature is idenitfied
* 0.1
    * Initial Release
