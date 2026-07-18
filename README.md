# 🧠 Sentiment Analysis using BERT

> A full-stack NLP application that performs **sentiment classification** on user text using a fine-tuned **BERT** model. Built with **React**, **FastAPI**, and **Hugging Face Transformers**, the application predicts whether the input sentiment is **Positive**, **Negative**, or **Neutral** in real time.

---

## 🚀 Live Demo

🌐 **Demo:** https://bert-model.vercel.app

---

# ✨ Features

- 🤖 Fine-tuned BERT model for sentiment classification
- 😊 Predicts **Positive**, **Negative**, and **Neutral** sentiments
- 📊 Displays confidence score for each prediction
- ⚡ Real-time inference using FastAPI
- 🎨 Clean and responsive React user interface
- 🔍 Handles custom user input
- 🚀 Deployed frontend and backend

---

# 🛠 Tech Stack

## Frontend

- React.js
- HTML5
- CSS3
- JavaScript

## Backend

- FastAPI
- Python

## Machine Learning

- Hugging Face Transformers
- BERT (bert-base-uncased)
- PyTorch
- Scikit-learn
- Pandas
- NumPy

---

# ⚙️ How It Works

1. User enters text.
2. The React frontend sends the request to the FastAPI backend.
3. The backend preprocesses the text.
4. The fine-tuned BERT model predicts the sentiment.
5. The predicted sentiment and confidence score are returned and displayed instantly.

---

# 📂 Project Structure

```text
Sentiment-Analysis
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── app.py
│   ├── predict.py
│   ├── requirements.txt
│   └── sentiment_model
│
├── assets
├── README.md
└── requirements.txt
```

---

# 🔐 Installation

## Clone the repository

```bash
git clone https://github.com/yourusername/sentiment-analysis.git
```

Move into the project

```bash
cd sentiment-analysis
```

---

## Backend Setup

```bash
cd backend

pip install -r requirements.txt

uvicorn app:app --reload
```

Backend runs at

```
http://127.0.0.1:8000
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm start
```

Frontend runs at

```
http://localhost:3000
```

---

# 🧠 Model Details

- Model: **Fine-tuned BERT**
- Framework: **Hugging Face Transformers**
- Language: **English**
- Classes:
  - Positive
  - Neutral
  - Negative

---

# 📈 Features Implemented

- Fine-tuned BERT classifier
- FastAPI REST API
- React frontend
- Confidence score prediction
- Input preprocessing
- Responsive UI
- REST API integration
- Deployment-ready architecture

---

# 🔮 Future Improvements

- Batch sentiment prediction
- Aspect-based sentiment analysis
- Emotion detection
- Multilingual support
- Explainable AI visualizations
- User authentication
- Prediction history

---

# 📚 Technologies Used

- Python
- FastAPI
- React.js
- Hugging Face Transformers
- BERT
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- HTML
- CSS
- JavaScript

---

# 👨‍💻 Author

**Krish Agrawal**

- GitHub: https://github.com/krishagrawal623
- LinkedIn: https://linkedin.com/in/krishagrawal75

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!
