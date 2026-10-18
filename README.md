In this respository, codes for analyzing microbiome and gene expression data of pancreatic ductal adenocarcinoma (PDAC) samples are provided. These codes implement nine featrue ranking algorithms: Adaptive Boosting (AdaBoost), Categorical boosting (CatBoost), Light gradient boosting machine (LightGBM), Least absolute shrinkage and selection operator (LASSO), Extreme gradient boosting (XGBoost), Ridge, Monte Carlo feature selection (MCFS), Random Forest (RF), and Extremely Randomized Trees (ExtraTrees), and nine classification algiorithms: Decision Tree (DT), Support Vector Machine (SVM), Ridge, ExtraTrees, LightGBM, K-Nearest Neighbors (KNN), AdaBoost, RF, and XGBoost.
Python environment installation

Step 1 Download the software by git clone https://github.com/*******/*******

Step 2 Installation has been tested in Linux and Windows with Python 3 (Recommend to use Python 3.10 or miniconda 3 platform). Since the package is written in Python 3, Python 3 with the pip tool must be installed first. The tools use the following dependencies: numpy, scipy, pandas, scikit-learn You can install these packages first, by the following commands: pip install pandas pip install numpy pip install scipy pip install scikit-learn

Step 3 cd to the software folder and run the installation command: python *************

Guide for codes 

Step 1: The microbiome and gene expression data  was fed into the codes of one of the feature ranking algorithm, which can produce a feature list. 

Step 2: With the feature list in Step 1, using codes in folder csv_make to generate csv files, which contain samples represented by some top features in the list. 

Step 3: For each generated csv file, using the codes of one classification algorithm to obtain the cross-validation results.

Other notes

In each folder, the file "comd" contains the codes to run the corresponding package.
