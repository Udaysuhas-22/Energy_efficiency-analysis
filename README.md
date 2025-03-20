# Energy Efficiency Analysis Project

## Project Overview
This project involves analyzing the energy efficiency of buildings using machine learning and statistical methods. The study examines 12 different building shapes simulated in Ecotect, considering various features to predict cooling loads.

## Team Members
- Meghanath Somarowthu  
- Sai Sinduri Vangala  
- Uday Suhas Nakkapalli  
- Chenna Keshav Chinthakindi  

**Professor:** Donald Harter

## Dataset
The dataset consists of eight features used to predict cooling load:
- **Relative Compactness** (Continuous)
- **Surface Area** (Continuous)
- **Wall Area** (Continuous)
- **Roof Area** (Continuous)
- **Overall Height** (Continuous)
- **Orientation** (Categorical and Discrete)
- **Glazing Area** (Continuous)
- **Glazing Area Distribution** (Categorical and Discrete)

### Data Insights:
- Buildings vary in terms of glazing area, glazing area distribution, and orientation.
- The target variable is **Cooling Load**.

## Visualizations and Statistical Analysis
### Exploratory Data Analysis:
- **Scatterplot Matrix:** Used to identify relationships between features.
- **Histograms:** Displayed distributions of variables.

### Descriptive Statistics:
- **Relative Compactness:** Range: 0.62 - 0.98, Mean: 0.76
- **Surface Area:** Range: 514.5 - 808.5, Mean: 671.7
- **Cooling Load:** Range: 10.90 - 48.03, Mean: 24.59

### Correlation Analysis:
- **Relative Compactness** and **Surface Area**: Strong negative correlation (-0.99)
- **Overall Height** and **Roof Area**: Strong negative correlation (-0.97)
- **Cooling Load**: Correlated positively with Relative Compactness (0.63) and Wall Area (0.43), and negatively with Surface Area (-0.67)

## Machine Learning Models
We implemented multiple models for predicting cooling loads:

### 1. **Linear Regression**
- Accuracy: **88.7%**
- High multicollinearity detected in "Roof Area" and "Overall Height" (VIFs: 24.23 and 18.86 respectively).

### 2. **Perceptron Model**
- Initial prediction: 715
- Final prediction after learning: 690
- Accuracy: **58%**

### 3. **Support Vector Machines (SVM)**
- Used to find the best decision boundary for classification.

### 4. **Neural Networks**
- Implemented for pattern recognition and predictive analysis.

### 5. **K-Nearest Neighbors (KNN)**
- Conducted two analyses for classification-based predictions.

### 6. **Naïve Bayes**
- Applied for probabilistic classification.

### 7. **Decision Tree**
- Used for hierarchical rule-based classification.

### 8. **Random Forest**
- Applied for improving prediction accuracy by aggregating multiple decision trees.

### 9. **Boosting Algorithms**
- Used for enhancing prediction power.

## Conclusion
The project successfully analyzed the energy efficiency of buildings using statistical methods and machine learning models. The Linear Regression model provided the best predictive power, explaining 88.7% of the variance in cooling loads. Future work could involve hyperparameter tuning and deep learning techniques to improve accuracy.

## Technologies Used
- **Ecotect** (Building simulations)
- **R Studio** (Data visualization & statistical analysis)
- **Python** (Machine Learning & Model Development)
- **Jupyter Notebook** (Data exploration & model evaluation)

## Contact Information
For any inquiries, please reach out to the project team members.

**Thank you!**
