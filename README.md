# Predicting Concrete Compressive Strength using Machine Learning

This project utilizes the [Concrete Compressive Strength Dataset](https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength) from the UCI Machine Learning Repository. The goal is to predict the compressive strength of concrete using machine learning techniques.

## Dataset Features
- **Input Features**:
  - Cement (kg/m³)
  - Blast Furnace Slag (kg/m³)
  - Fly Ash (kg/m³)
  - Water (kg/m³)
  - Superplasticizer (kg/m³)
  - Coarse Aggregate (kg/m³)
  - Fine Aggregate (kg/m³)
  - Age (days)
- **Target Variable**:
  - Concrete Compressive Strength (MPa)

## Workflow
1. **Data Preprocessing**
   - Import necessary libraries.
   - Load and clean the dataset.
   - Handle duplicate records and missing values.

2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships using box plots and heat maps.
   - Gain insights into the dataset.

3. **Feature Scaling and Train-Test Split**
   - Normalize features for machine learning models.
   - Split the data into training and testing sets.

4. **Model Training**
   - Train and evaluate:
     - Linear Regression
     - Support Vector Machines (SVM)

## Results
- Performance metrics of each model are evaluated on the testing dataset.
- Insights derived from the dataset help optimize predictions.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: Scikit-Learn, Pandas, NumPy, Matplotlib


## Conclusion
This project highlights the potential of machine learning in predicting concrete strength, aiding in the design and evaluation of durable materials.
