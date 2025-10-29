Software Requirements

Python (latest version)
Libraries:
pandas → data manipulation
numpy → numerical operations
re → regular expressions
matplotlib & seaborn → data visualization
scikit-learn → ML models and evaluation
wordcloud, nltk → text preprocessing

IDE: Jupyter Notebook / PyCharm / VS Code

Dataset: Flipkart reviews dataset (text + sentiment labels)

🧠 Methodology
Data Collection – Import and store Flipkart review data
Data Preprocessing – Clean text, remove noise, and tokenize
Feature Extraction – Convert text to vectors using TF-IDF
Model Training – Train ML models (SVM, Random Forest, Gradient Boosting)
Evaluation – Compare models using accuracy, precision, recall, F1-score
Visualization – Plot confusion matrices and sentiment distributions

🧩 System Design
The system is modular with these components:
Input Data Module – Loads raw reviews
Preprocessing Module – Cleans and tokenizes text
Feature Extraction Module – Converts text to numerical form (TF-IDF)
Model Training Module – Trains and tunes ML models
Prediction & Voting Module – Combines model outputs via majority voting
Evaluation Module – Assesses model performance visually and statistically

📊 Results
Model	Accuracy	Highlights
SVM	High	Great for high-dimensional data but slight confusion between neutral & negative
Random Forest	High	Balanced precision and recall, reduced overfitting
Gradient Boosting	Highest	Excellent precision and recall across all sentiments

✅ Final Ensemble (SVM + RF + GB) outperformed individual models with improved accuracy and robustness.
Most reviews were positive, indicating overall customer satisfaction.
