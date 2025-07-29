# 📩 SMS Spam Classifier

A simple machine learning project that classifies SMS text messages as **spam** or **ham (not spam)** using Natural Language Processing (NLP) and a Naive Bayes classifier.

This project is built using Python and Streamlit for the web interface. It demonstrates how classical ML models can be used effectively for text classification tasks.

---

## 🚀 Features

- ✅ Classifies SMS messages as spam or not
- 🧠 Trained on real-world SMS data
- 🗃️ Uses TF-IDF vectorization for feature extraction
- 💡 Built with a Naive Bayes classifier
- 🖥️ Simple web UI with Streamlit

---

## 🧠 Tech Stack

- Python
- Scikit-learn
- NLTK
- Streamlit
- Pandas
- Pickle

---

## 📁 Project Structure
sms-spam-classifier/
├── app.py # Streamlit app for spam prediction
├── model.pkl # Trained Naive Bayes model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # List of dependencies
└── spam.csv # (Optional) Dataset used for training


---

## 🛠️ How It Works

1. Input SMS message is preprocessed and tokenized.
2. Message is vectorized using the pre-fitted TF-IDF vectorizer.
3. Vector is passed to a trained Naive Bayes model.
4. The model outputs whether the message is **Spam** or **Not Spam**.

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/hiteshchotwani/Sms-Spam-Detector.git
cd Sms-Spam-Detector

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

