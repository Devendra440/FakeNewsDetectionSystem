# 📰 Fake News Detection System

A machine learning-based web application that predicts whether a news article is **real or fake** using natural language processing (NLP). This system helps combat misinformation by providing users with a simple interface to check the authenticity of news content.

---

## 🚀 Live Demo

👉 [Click here to open the app](https://fakenewsdetectionsystem-bvgp9ms2nlbshdqnlsjzky.streamlit.app/)  

---

## 📌 Features

- 🔍 Detects fake or real news based on the article title or text
- ⚙️ Preprocesses data using NLP techniques (TF-IDF)
- 🤖 Trained machine learning model (Logistic Regression)
- 📊 Clean and interactive UI with **Streamlit**
- 💾 Loads a serialized model (`model.pkl`) for fast predictions

---

## 🧠 Machine Learning Overview

- **Algorithm Used**: Logistic Regression
- **Text Vectorization**: TF-IDF Vectorizer
- **Input Features**: `title`, `text`, `subject`
- **Target**: Label (fake = 1, real = 0)
- **Dataset Source**: [Kaggle Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 📁 Project Structure

Fake-News-Detection/
│
├── app.py # Main Streamlit app
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

## 💻 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Joblib (for model saving/loading)

---

## 🧪 How It Works

1. User enters a news article **title or full text**
2. Text is **vectorized** using TF-IDF
3. Trained model predicts **Fake (1)** or **Real (0)**
4. Output is shown in a clean UI

---

## 🛠️ Installation & Running the App Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

requirements.txt

streamlit
pandas
numpy
scikit-learn
joblib

🙋‍♂️ Author
👨‍💻 Pinnam Devendra Gupta
📧 Email: pinnamuptha1234@gmail.com
🌐 Portfolio Website (bento.me/pinnamdevendragupta)

📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgments
Kaggle Dataset

Streamlit for frontend UI

scikit-learn for model training
