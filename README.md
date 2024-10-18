# EasyML
EasyML
EasyML is a powerful no-code platform designed to help users train machine learning models without writing a single line of code. It simplifies the complexities of ML and enables individuals from all backgrounds to leverage the power of machine learning for their projects.

Table of Contents
Introduction
Features
Getting Started
Prerequisites
Installation
How to Use
Supported Algorithms
Contributing
License
Introduction
NoCodeML is developed to bridge the gap between non-technical users and machine learning. With an intuitive drag-and-drop interface, users can select datasets, configure ML algorithms, and train models easily. The platform handles the backend processes such as data preprocessing, model training, and evaluation.

Features
Drag-and-drop interface for building ML models.
AutoML support to automatically select and tune models.
Pre-built data preprocessing tools.
Visualization tools for better understanding of data and model performance.
Supports multiple ML algorithms (classification, regression, clustering).
Easy export of trained models in popular formats.
Cross-platform support (web-based).
Getting Started
Prerequisites
To run NoCodeML, ensure you have the following installed:

Python 3.x
pip (Python package manager)
Libraries: numpy, pandas, scikit-learn, matplotlib
You can install the dependencies using the following command:

bash
Copy code
pip install -r requirements.txt
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/nocodeml.git
Navigate into the project directory:
bash
Copy code
cd nocodeml
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Start the local server:
bash
Copy code
python app.py
Open the platform in your browser at http://localhost:5000.
How to Use
Upload your dataset: You can upload CSV or Excel files for model training.
Select preprocessing options: Choose from normalization, feature encoding, handling missing values, etc.
Choose ML algorithm: Select from the list of supported machine learning algorithms.
Train the model: Click on the Train Model button, and the platform will automatically train the model based on your selections.
Evaluate results: View the evaluation metrics, such as accuracy, precision, recall, or RMSE, based on the model type.
Export model: Save the trained model for deployment in other environments.
Supported Algorithms
Classification: Logistic Regression, Decision Trees, Random Forest, SVM, KNN
Regression: Linear Regression, Decision Trees, Random Forest, Lasso Regression
Clustering: K-Means, DBSCAN, Agglomerative Clustering
AutoML: Automatic selection of models with hyperparameter tuning
