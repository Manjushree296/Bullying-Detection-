# 🚨 Bullying Detection System

This project is a Python-based system that detects bullying or harassment in online text, especially from social media platforms. The system helps store offensive or bullying comments as **proof** so that appropriate action can be taken against the bully.

---

## 📌 Features

- ✅ Detects bullying and harassment in text data.
- ✅ Helps store offensive comments for future reference.
- ✅ Simple and clean Python implementation.
- ✅ Can be extended with ML/NLP techniques for higher accuracy.

---

## 🛠️ Technology Stack

- **Language**: Python 🐍
- **Libraries**: 
  - scikit-learn
  - pandas
  - nltk
  - re (regular expressions)
- **Model**: Naive Bayes / Logistic Regression (can be customized)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Manjushree296/Bullying-Detection-.git
cd Bullying-Detection-
2. Install Required Libraries
Make sure you have Python 3.x installed.
pip install -r requirements.txt
3. Run the Program
python main.py
Note: If the main file has a different name (e.g. bully_detect.py), update the command accordingly.

📂 Project Structure
Bullying-Detection-/
├── data/                  # Dataset files (comments + labels)
├── models/                # Trained ML models (if any)
├── main.py                # Main detection script
├── utils.py               # Utility functions
├── README.md              # Project readme
└── requirements.txt       # Python dependencies
🧠 How It Works
Input: A comment or piece of text.

Processing:
Clean and preprocess the text.
Extract features (TF-IDF, Bag of Words).
Predict using a trained classifier.
Output: Bullying or Not Bullying.
Action: Optionally, store the bullying comment for evidence.
