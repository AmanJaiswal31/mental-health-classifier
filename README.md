<div align="center">

# 🧠 Mental Health Classifier

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-00F7FF?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-8A2BE2?style=for-the-badge)

*Using AI to understand and support mental health 💚*

**🌐 Live Demo:** [Try it on Hugging Face Spaces](https://huggingface.co/spaces/suyashjaiswal/mental-health-classifier1)

</div>

---

## 🧠 About This Project

A Machine Learning powered mental health text classifier that analyzes input text and classifies it into different mental health categories. Deployed as an interactive web app using Streamlit on Hugging Face Spaces.

---

## ✨ Features

- 💬 Classifies text into mental health categories
- 🤖 ML/NLP based text classification
- 📊 Confidence score for each prediction
- ⚡ Real-time predictions
- 🌐 Interactive Streamlit web interface
- ☁️ Deployed on Hugging Face Spaces

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Core language |
| PyTorch | Deep Learning framework |
| Scikit-Learn | ML pipeline |
| NLTK / spaCy | Text preprocessing |
| Streamlit | Web interface |
| Hugging Face Spaces | Deployment |

---

## 🏗️ Architecture

```
User Input (text)
    │
    ▼
Text Preprocessing
    │  Tokenization, Cleaning, Vectorization
    ▼
ML Classification Model
    │
    ▼
{ category: "Anxiety", confidence: 92.4% }
```

---

## 📁 Project Structure

```
mental-health-classifier/
├── app.py               # Streamlit web app
├── model.py             # Model definition and inference
├── train.py             # Model training script
├── preprocess.py        # Text preprocessing pipeline
├── requirements.txt     # Dependencies
└── README.md
```

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/AmanJaiswal31/mental-health-classifier.git
cd mental-health-classifier

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
# App running at http://localhost:8501
```

---

## ☁️ Deployment

The model is deployed on **Hugging Face Spaces** using **Streamlit**.

👉 Try it live: [https://huggingface.co/spaces/suyashjaiswal/mental-health-classifier1](https://huggingface.co/spaces/suyashjaiswal/mental-health-classifier1)

---

## ⚠️ Disclaimer

This tool is built for **educational and research purposes only**. It is not a substitute for professional mental health advice, diagnosis, or treatment. If you or someone you know is struggling, please seek help from a qualified mental health professional.

---

## 🔮 Future Work

- Add more mental health categories for broader classification
- Improve model accuracy with larger datasets
- Add multilingual support
- Integrate with therapy recommendation system

---

## 👨‍💻 Author

**Aman Jaiswal**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amanjaiswal31/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amanjaiswal.cse@gmail.com)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:8A2BE2,100:FF6B6B&height=100&section=footer"/>
</div>
