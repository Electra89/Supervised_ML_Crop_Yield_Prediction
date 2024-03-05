

#  Crop Yield Prediction

<p  align="center">
<img  src="https://scorpionsearth.in/wp-content/uploads/2020/01/01-1.gif"  alt="Animated gif netflix Image"  height="382px">
</p>

In this project aims to predict crop yields using a dataset containing information about different factors influencing agricultural production. The goal is to develop a predictive model that can aims to empower agricultural decision-making, enhance risk management, and contribute to the sustainable future of global agriculture.

## Problem Statement

The science of training machines to learn and produce models for future predictions is widely used, and not for nothing. Agriculture plays a critical role in the global economy. With the continuing expansion of the human population understanding worldwide crop yield is central to addressing food security challenges and reducing the impacts of climate change.

Crop yield prediction is an important agricultural problem. The Agricultural yield primarily depends on weather conditions (rain, temperature, etc), pesticides and accurate information about history of crop yield is an important thing for making decisions related to agricultural risk management and future predictions.


##  Project Summary

### Key Steps

### 1. Data Preprocessing

-   **Handling Missing Values:** Mitigated the impact of missing data by employing relevant imputation techniques, ensuring the integrity of the dataset.

### 2. Exploratory Data Analysis (EDA)

-   **Statistical Analysis:** Conducted a comprehensive exploratory data analysis, utilizing statistical methods to unveil the distribution of key variables and uncover potential correlations.

### 3. Feature Selection and Engineering

-   **Outlier Detection:** Identified and addressed outliers to enhance the robustness of subsequent modeling steps.
    
-   **Selecting Relevant Features:** Identified crucial features affecting crop yield and retained them for modeling.
    
-   **Data Splitting:** Employed techniques like train-test splitting to divide the dataset, ensuring independent sets for model training and evaluation.
    
-   **Feature Scaling and Transformation:** Applied appropriate scaling methods, such as Min-Max scaling, to normalize numeric features, ensuring a consistent impact on model training.
    

### 4. Machine Learning Models & Evaluation

-   **Regression Models:** Implemented advanced regression models, including Random Forest, XGBoost, and Bagging Regressor, to predict crop yield.
    
-   **Performance Metrics:** Evaluated model effectiveness using key metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared, providing a comprehensive assessment of predictive accuracy.
    
-   **Cross-Validation:** Employed k-fold cross-validation to ensure the models' robustness across various subsets of the dataset.
    
-   **Hyperparameter Tuning:** Utilized optimization techniques, such as  randomized search, to fine-tune model hyperparameters, enhancing overall performance.


## Tech-stack Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
-  Scikit-learn
  
## Key Findings
- The Sweet Potatoes yield exhibited a consistent upward trend from 1990 to 2010
- India emerged as a key contributor to total crop yield, outshining other areas in agricultural productivity.
- Over the years 1990 to 2010, the yield of Sweet Potatoes shows a consistent increasing trend.
-   Higher temperatures, such as those seen in Indonesia and India, may be associated with higher crop yields
- Bagging Regressor and Random Forest outperform other models, achieving the highest accuracy of 98.89% and the lowest mean squared error (MSE).
  

## Conclusion
This project underscores the application of data analysis, machine learning, and visualization techniques to understand and Pattern crop yield patterns. 
 The robust performance of advanced regression models, especially Bagging Regressor, highlights their effectiveness, with a remarkable 98.89% accuracy and minimal mean squared error, underscoring their potential for accurate crop yield prediction.
 

## Code and Notebooks
Access the [Colab notebook](https://github.com/Electra89/Supervised_ML_Crop_Yield_Prediction/blob/main/Supervised_ML_Crop_Yield_Prediction.ipynb) to view the detailed project implementation.

## Data Source

The analysis is based on the # Crop Yield Dataset . You can find more about the dataset [here](https://github.com/Electra89/Supervised_ML_Crop_Yield_Prediction/blob/main/Crop_Yield_Dataset.csv).


## License

This project is licensed under the [MIT License](LICENSE).

