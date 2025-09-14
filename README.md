# 📱 SMS Spam Classifier

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using **TF-IDF vectorization** and **Naive Bayes**.  
The project includes an interactive **Streamlit web app** for real-time predictions.  

🔗 **Live Demo:** [SMS Spam Classifier](https://sms-spam-classifier-uc9e.onrender.com/)  

---

## 📊 Dataset
We used the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from Kaggle.  

---

## 🚀 Features
- Text preprocessing (lowercasing, stopword removal, stemming)  
- TF-IDF vectorization  
- Multinomial Naive Bayes classifier  
- Real-time SMS prediction via Streamlit  
- User-friendly UI with deployment on Render  

---

## 🧠 Model Training

Text preprocessing: stopword removal, punctuation cleaning, stemming.

Vectorization: TF-IDF with max features = 3000.

Classifier: Multinomial Naive Bayes.

Evaluation: Achieved ~97% accuracy on test data.

---


## 📌 Project Structure
```bash
├── app.py                  # Streamlit app
├── model.pkl               # Trained ML model
├── vectorizer.pkl          # TF-IDF vectorizer
├── spam.csv                # Dataset file
├── sms_spam_detector.ipynb # Notebook with training code
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```
---

## 🛠️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/SMS-Spam-Classifier.git
cd SMS-Spam-Classifier
```
Create a virtual environment and activate it:
```bash
python -m venv .venv
.venv\Scripts\activate   # On Windows
source .venv/bin/activate   # On Linux/Mac
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

---

## 📦 Requirements

Main dependencies (see requirements.txt for full list):

streamlit

scikit-learn

nltk

pandas

numpy

---

## 📷 Screenshots
<img width="1727" height="691" alt="image" src="https://github.com/user-attachments/assets/a7816d75-54b6-4890-a1f1-49004ec10438" />


---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

---

## 📜 License

This project is licensed under the MIT License.

