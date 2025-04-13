# 📱 SMS Spam Classifier with Naive Bayes  
*A real-time spam detection system deployed with Streamlit*  

![Demo](spam.jpg)  
*Classify messages instantly with visual feedback*  

## 🚀 Overview  
This project implements a **Naive Bayes classifier** to detect spam SMS messages. Built with Python and Streamlit, it demonstrates how machine learning can automate text filtering for communication platforms.  

**Key Features:**  
✔️ Real-time spam/ham classification  
✔️ Interactive Streamlit web interface  
✔️ Visual feedback (red for spam, green for legitimate)  
✔️ Model accuracy metrics included  

## 📊 Dataset  
Trained on the `sms_spam.csv` dataset containing labeled SMS messages:  
- **spam**: Unwanted promotional/malicious messages  
- **ham**: Legitimate personal messages  

## ⚙️ Tech Stack  
- **Python 3**  
- **Streamlit** (Web Interface)  
- **Scikit-learn** (Naive Bayes Model)  
- **Pandas** (Data Processing)  

## 🛠️ Installation  
1. Clone the repository:  
```bash
git clone https://github.com/your-username/Spam-SMS-Classifier.git
```
2.Install dependencies:
bash
Copy
pip install -r requirements.txt


## 🎮 Usage
Run the app locally:

bash
Copy
streamlit run strem.py
Then:

Type/paste a message in the text box

Click Predict

See instant classification (✅ human / ❌ spam)

## 🌐 Deployment
Deploy to Streamlit Sharing in 3 steps:

Push to GitHub

Create new app in Streamlit Share

Connect your repository

## 📌 Project Structure
Copy
.
├── strem.py             # Main application
├── sms_spam.csv         # Dataset
├── requirements.txt     # Dependencies
└── spam.jpg             # App thumbnail
## 📈 Performance
Model accuracy: ~98% (varies by test split)

