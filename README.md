# Spam Classifier using Naive Bayes

![Spam Classification App](spam.jpg)

A Streamlit-based web application that classifies SMS messages as "spam" or "human" using a Naive Bayes machine learning model.

## Features
- Real-time spam detection for SMS messages.
- Simple and intuitive user interface.
- Displays classification results with visual feedback (green for human, red for spam).

## Dataset
The model is trained on the `sms_spam.csv` dataset, which contains labeled SMS messages categorized as "spam" or "ham" (non-spam).

## Requirements
- Python 3.x
- Libraries: `streamlit`, `pandas`, `scikit-learn`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Spam-Classifier-NaiveBayes.git
Navigate to the project directory:

bash
Copy
cd Spam-Classifier-NaiveBayes
Install the required dependencies:

bash
Copy
pip install -r requirements.txt
Usage
Run the Streamlit app:

bash
Copy
streamlit run strem.py
Open the app in your browser (usually http://localhost:8501).

Enter a message in the text box and click "Predict" to see the classification result.

Deployment
The app can be deployed on Streamlit Sharing by linking the GitHub repository. Follow these steps:

Push the project to your GitHub repository.

Log in to Streamlit Sharing and create a new app.

Connect the app to your GitHub repository and deploy.

Project Structure
strem.py: Main Streamlit application script.

sms_spam.csv: Dataset used for training the model.

requirements.txt: List of required Python packages.

spam.jpg: Image used in the app interface.

Contributors
Your Name

License
This project is open-source and available under the MIT License.

Copy

---

This README provides a clear overview of the project, instructions for installation and usage, and details about deployment. The repository name reflects the core functionality of the application. Let me know if you'd like any modifications!
