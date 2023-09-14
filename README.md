# Kaiburr
## Consumer Complaint Text Classification

This repository contains a Python script for performing text classification on a consumer complaint dataset using machine learning. The script includes the following steps:

1. Data Loading and Preprocessing: The consumer complaint dataset is loaded, and irrelevant columns are removed. Missing data is also handled. For demonstration purposes, a smaller portion of the data is selected.

2. Data Splitting: The dataset is split into training and testing sets for model evaluation.

3. Text Vectorization: The text data is transformed into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.

4. Model Building and Evaluation: Three machine learning models are built and evaluated: Random Forest, Support Vector Machines (SVM), and Gradient Boosting. Each model's accuracy, classification report, and confusion matrix are displayed. Additionally, a bar chart compares the accuracy of the three models.

5. Comparison DataFrames: For each model, a DataFrame is created that includes 'ID,' 'Complaint,' 'Actual Product,' and 'Prediction' columns for easy comparison of model performance.

### Usage

To run the script:

1. Replace `'complaints.csv'` with your own dataset file.
2. Install the required libraries using `pip install pandas scikit-learn matplotlib seaborn`.

Run the script using `python text_classification.py`.

### Results

The script displays the accuracy, classification report, confusion matrix, and comparison DataFrame for each model. A bar chart visually compares the accuracy of the three models.

### Customization

You can further fine-tune the models and explore additional options for optimization by modifying the script as needed.

Feel free to adapt and use this script for your own text classification tasks.

