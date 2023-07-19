# Heart Disease Prediction using Machine Learning

This repository contains a Python script for predicting heart disease using machine learning. The dataset used for this project is "heart.csv" which contains various features related to heart health.

## Dependencies
Before running the code, make sure you have the following dependencies installed:
- numpy
- pandas
- matplotlib
- scikit-learn

You can install these packages using pip:
pip install numpy pandas matplotlib scikit-learn


## Dataset
The dataset used in this project is "heart.csv" which contains the following columns:
- `age`: Age of the patient
- `sex`: Gender of the patient (0: female, 1: male)
- `cp`: Chest pain type (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol (in mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1: true, 0: false)
- `restecg`: Resting electrocardiographic results (0: normal, 1: having ST-T wave abnormality, 2: showing probable or definite left ventricular hypertrophy)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina (1: yes, 0: no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment (1: upsloping, 2: flat, 3: downsloping)
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thallium stress test result (3: normal, 6: fixed defect, 7: reversible defect)
- `target`: Target variable (0: no heart disease, 1: heart disease)

## Data Exploration
The script includes data exploration and visualization using matplotlib. It displays a correlation matrix plot and histogram of the dataset to understand the data distribution.

## Preprocessing
The dataset is preprocessed by one-hot encoding categorical variables and standardizing numerical features using StandardScaler.

## Machine Learning Models
The script uses four different classifiers to predict heart disease:
1. K-Nearest Neighbors (KNN) Classifier
2. Support Vector Classifier (SVC) with various kernel functions (linear, poly, rbf, sigmoid)
3. Decision Tree Classifier
4. Random Forest Classifier

The accuracy scores for each model are calculated and displayed on bar graphs for comparison.

## Logistic Regression Model
The script also includes a Logistic Regression model for heart disease prediction. The model is trained on the training data and evaluated on the testing data. The accuracy score and confusion matrix are displayed.

## Results
The results of all the models are shown using various plots for easy visualization and comparison.

## How to Run
1. Clone the repository to your local machine.
2. Download the "heart.csv" dataset and place it in the same directory as the Python script.
3. Install the required dependencies using the provided pip command.
4. Run the Python script using any Python IDE or from the command line.

Feel free to experiment with the code, try different machine learning models, or modify the visualization plots to gain deeper insights into heart disease prediction.

If you find this project helpful, please give it a star on GitHub. Happy coding! 😊
