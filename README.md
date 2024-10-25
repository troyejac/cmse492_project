## Body Fat Estimator
This project is to create a machine learning algorithm that will estimate a persons body fat based on factors such as density, height, weight, and body measurements.
# Objectives
- Create an easy way to measure someones body fat
- Provide accurate measurements
- Allow users to analyze results and understand how each factor influences predictions
# Folder Structure
data/: Contains the initial data file (bodyfat.txt), as well as preprocessed files like normalized and split data for training and testing.
notebooks/: Contains Jupyter notebooks for different stages of the project:
data_processing.ipynb: Preprocesses and cleans the data, normalizes, and splits it.
model.ipynb: Builds and trains the machine learning model.
evaluation.ipynb: Evaluates model performance and visualizes results.
results/: Stores outputs, figures, and evaluation metrics from model runs for further analysis.
# Instructions for Setting Up and Running the Code
1. Clone the repository

git clone https://github.com/troyejac/cmse492_project.git

2. Run the Notebooks: Open Jupyter Notebook and run each notebook in the following order:

data_processing.ipynb: Run to clean, normalize, and split data.
model.ipynb: Run to train the model using the preprocessed data.
evaluation.ipynb: Run to visualize model performance and evaluate accuracy.