# Glass_Identification
Data Science Project


## Data Sources:-
			 https://archive.ics.uci.edu/ml/datasets/glass+identification

## Dataset description

This is a Glass Identification Data Set from UCI. It contains 10 attributes including id. The response is glass type(discrete 7 values)
The study of the classification of types of glass was motivated by the criminological investigation. At the scene of the crime, the glass left can be used as evidence...if it is correctly identified!

Number of Instances: 214

Number of Attributes: 10 (including an Id#) plus the class attribute -- all attributes are continuously valued

### Goal:-
The goal of the project is to find the type of glass based on the characteristics of the new glass. To perform preprocessing of the dataset provided for the glass type and get inferences from it Through Data analysis and Visualization Then Train Machine Learning Models/Algorithms. 

## Attribute Information(Features):

Id number: 1 to 214 (removed from CSV file)

*   RI: refractive index
*   Na: Sodium (unit measurement: weight percent in corresponding oxide, 
    as attributes 4-10)
*   Mg: Magnesium
*   Al: Aluminum
*   K: Potassium
*   Ca: Calcium
*   Ba: Barium
*   Fe: Iron
*   Type of glass: (class attribute)  [1-7]
    1.   Building_windows_float_processed
    2.   Building_windows_non_float_processed
    3.   Vehicle_windows_float_processed
    4.   Vehicle_windows_non_float_processed
    5.   Containers
    6.   Tableware
    7.   Headlamps
    
## Project Outline
1. Exploring Dataset
  * Preprocessing Dataset
  * Adding meaningful column/attribute names
  * Removing unnecessary columns
2. Statistics of Dataset
  * Descriptive Statistics
3. Data Visualization
  * Using Univariate Plots
  * Using Multivariate Plots
  * Using Correlation Matrix
4. Outlier Detection
5. Data Treatment
  * Removing Outliers
  * Normalizing the Data
  * Scaling the features
6. Visualization of Data after Being Preprocessed
7. Training set - Test set Split
8. Training Different Machine learning Models
  * K-Nearest Neighbors
  * Decision Tree
  * Logistic Regression
  * SVM Classifier (Non-Linear)
9. Summary

    
    
    
# Summary
Out of all above models:
### Decision Tree
Decision tree is overfitting with :->
Training accuracy: 1.0
Testing accuracy: 0.7037037037037037

### SVM (Non Linear Kernel)
SVM (Non Linear Kernel) is giving best result with:
Training accuracy: 0.76875
Testing accuracy: 0.7407407407407407


