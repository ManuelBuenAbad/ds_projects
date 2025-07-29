# ds_projects/03_homes

An end-to-end regression project with the Ames IA homes dataset.
Written by Manuel A. Buen-Abad.

Description
-----------------------------------------

The dataset consists of 1,460 training and 1,460 test records of 80 features of various homes sold in the city of Ames, IA; the training dataset also includes the prices at which each home was sold.

In this end-to-end project, I

1. Collect, transform, and deploy the data in various ways (ETL), including a thorough, automated cleaning of the same.
2. Engage in painstaking exploratory analysis (EDA) through statistics and data visualization reports.
3. Use domain knowledge and unsupervised learning for feature engineering.
4. Employ rigorous feature selection methods.
5. Construct automated pipelines that, in addition to performing the steps listed above:

	a. employ various state-of-the-art AI/ML/DL algorithms (including stacked and boosted ensamble models),
	
	b. cross validate them,
	
	c. tunes their hyperparameters, and
	
	d. produces statistical and explanatory ML reports (including metrics such as the RMSE score, plotting SHAP values, etc.)
	
6. Evaluate the models, select the best, and save it locally.

Because this project is so long and complex, I have broken down the notebook into two parts: `03_homes_01.ipynb`, and `03_homes_02.ipynb`.

Requirements
-----------------------------------------

1. python
2. matplotlib
3. seaborn
4. numpy
5. pandas
6. scikit-learn
7. xgboost
8. catboost
9. shap
10. graphviz
11. dill
