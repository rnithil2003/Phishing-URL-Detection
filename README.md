# Phishing-URL-Detection 🔒
A Machine Learning–based web application that detects and classifies phishing URLs by analyzing domain-level and structural patterns. Built using Python, Flask, and Scikit-Learn, the model achieves over 97% accuracy in identifying malicious URLs.

🧠 Overview
This project applies supervised machine learning algorithms to distinguish between legitimate and phishing URLs. It uses multiple models like Gradient Boosting, XGBoost, and Random Forest, evaluating them through precision, recall, and F1-score metrics.

⚙️ Tech Stack
Languages: Python 3
Libraries: NumPy, Pandas, Scikit-learn, Matplotlib
Framework: Flask
Tools: Jupyter Notebook, Git, GitHub

🗂️ Project Structure
├── app.py                # Flask app for web interface
├── feature.py            # Feature extraction logic
├── Phishing URL Detection.ipynb  # Model training & analysis
├── requirements.txt      # Dependencies
├── templates/            # HTML templates
├── static/               # CSS & assets

📊 Model Performance
| Model             | Accuracy |
| ----------------- | -------- |
| Gradient Boosting | 97.4%    |
| CatBoost          | 97.2%    |
| Random Forest     | 96.7%    |
| SVM               | 96.4%    |

🚀 Result
Feature analysis shows that factors like HTTPS presence, Anchor URL, and Website Traffic play the most significant roles in phishing detection.






