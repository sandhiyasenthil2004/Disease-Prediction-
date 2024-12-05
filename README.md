Disease Predictor using Machine Learning

Overview
The Disease Predictor using Machine Learning is a medical diagnostic tool that predicts the likely disease based on input symptoms. The system uses machine learning algorithms such as Decision Tree, Random Forest, and Naive Bayes to analyze the provided symptoms and predict the corresponding disease. The tool aims to assist healthcare professionals and patients in early diagnosis and decision-making.

Features
Symptom Input: Allows users to input up to five symptoms.
Disease Prediction: Predicts the most likely disease using machine learning models.
Model Evaluation: Compares the performance and accuracy of different algorithms (Decision Tree, Random Forest, Naive Bayes).
User-friendly Interface: A simple GUI using Tkinter for easy interaction.
Accuracy Calculation: Measures the accuracy of the models based on a test dataset.

Technologies Used
Programming Language: Python
ML Libraries: Scikit-learn (Decision Tree, Random Forest, Naive Bayes)
Data Science Libraries: Pandas, NumPy
GUI: Tkinter
Development Environment: Jupyter Notebooks

Installation
Install Dependencies
Make sure you have Python installed. Then, install the required libraries:
pip install -r requirements.txt

Run the Application
Navigate to the project directory and run the following command to start the GUI:
python disease_predictor.py

How to Use
Open the GUI application.
Enter the symptoms by selecting up to five options from the dropdown menus.
Click the Predict button to get the predicted disease.
The system will display the predicted disease or show "Not Found" if no matching disease is found.
Model Training
The system uses the following machine learning models to predict diseases:

Decision Tree: A tree-based model that splits data based on feature values.
Random Forest: An ensemble of decision trees for improved accuracy.
Naive Bayes: A probabilistic model based on Bayes' Theorem for classification tasks.
Accuracy
The accuracy of each model is calculated using the test dataset, and the predictions are compared with actual outcomes to evaluate the performance.

Contributing
Contributions to the project are welcome. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.
