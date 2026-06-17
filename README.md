Fake News Detection Using Machine Learning

Project Overview
Fake News Detection is a Machine Learning and Natural Language Processing (NLP) project designed to classify news articles as Real News or Fake News. The rapid spread of misinformation through digital platforms has made automated fake news detection an important research area.

This project develops and evaluates multiple machine learning models capable of identifying misleading news articles based on textual content. The system processes news data, extracts meaningful features using TF-IDF Vectorization, and applies various classification algorithms to determine authenticity.

Objectives
Detect fake news articles automatically.
Reduce the spread of misinformation.
Compare the performance of different machine learning algorithms.
Build a reliable and scalable fake news classification system.
Machine Learning Models Used
The following classifiers were implemented and evaluated:

Logistic Regression
Decision Tree Classifier
Gradient Boosting Classifier
Random Forest Classifier
Dataset
The dataset contains labeled news articles categorized into:

True News
Authentic and verified news articles.

Fake News
Fabricated, misleading, or manipulated news articles.

Dataset Files:

Fake.csv
True.csv
Workflow
Workflow

Project Pipeline
Data Collection
Data Cleaning
Text Preprocessing
Feature Extraction using TF-IDF
Train-Test Split
Model Training
Model Evaluation
News Prediction
System Requirements
Hardware Requirements
Minimum 4 GB RAM
Intel i3 Processor or above
500 MB Free Disk Space
Software Requirements
Python 3.x
Jupyter Notebook / VS Code / PyCharm
Anaconda (Optional)
Technologies Used
Python
Pandas
NumPy
Scikit-Learn
NLTK
Matplotlib
Seaborn
Regular Expressions (re)
Installation
Clone the repository:

git clone https://github.com/your-username/Fake-News-Detection-Using-Machine-Learning.git
Navigate to the project folder:

cd Fake-News-Detection-Using-Machine-Learning
Install dependencies:

pip install -r requirements.txt
Run the project:

python src/fake_news_detection.py
Model Performance
Accuracy Comparison

The implemented machine learning models achieved high classification accuracy on the testing dataset.

Models Evaluated:

Logistic Regression
Decision Tree
Gradient Boosting
Random Forest
Confusion Matrix
Confusion Matrix

The confusion matrix illustrates the model's classification performance by comparing actual and predicted labels.

Features
Automatic Fake News Detection
Text Preprocessing
TF-IDF Vectorization
Multiple Machine Learning Models
Model Comparison
Manual News Prediction
High Accuracy Classification
Future Enhancements
Web Application Deployment
Real-Time News Verification
Deep Learning Models
Transformer-Based NLP Models
Browser Extension Integration
REST API Deployment
Project Screenshots
Real News Prediction
Output:

Not a Fake News
Fake News Prediction
Output:

Fake News
License
This project is licensed under the MIT License.
