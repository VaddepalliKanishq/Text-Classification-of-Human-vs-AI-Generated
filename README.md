# Text-Classification-of-Human-vs-AI-Generated
Here's a clean and pointwise summary of the project:

Project Overview AI vs Human Text Classification: A Machine Learning project that detects whether a given piece of text is AI-generated or Human-written.

Key Features
Data preprocessing
Feature engineering using TF-IDF vectorization
Model training and evaluation using Logistic Regression
Model persistence
Streamlit web deployment
Problem Statement
Distinguishing between AI-generated text and human-written content is becoming increasingly challenging.

Dataset
Total Samples: 105,000
Human Text: 52,500
AI Text: 52,500
Balanced dataset with essay-style texts
Project Pipeline
Data Preprocessing: Text cleaning, lowercase conversion, special character removal, and stopword removal
Train-Test Split: 80% training, 20% testing with stratified split
Feature Engineering: TF-IDF vectorization with max_features = 20000
Model Selection: Logistic Regression with max_iter = 1000
Model Performance: ~86.7% accuracy
Deployment
Streamlit web application with text input box, AI/Human prediction, and confidence score display
Local deployment on localhost:8501
Limitations
Short text inputs may produce less reliable predictions
Model trained on essay-style text (not chat-style)
TF-IDF may miss deeper contextual patterns
Future Improvements
Add n-gram feature tuning
Use Character-level TF-IDF
Upgrade to Transformer models (DistilBERT / BERT)
Deploy on Streamlit Cloud
Add probability visualization
Technologies Used
Python
Pandas
NumPy
NLTK
Scikit-learn
Streamlit
Joblib
Author
Roshan, Undergraduate Student – AIML, passionate about Machine Learning and AI System
