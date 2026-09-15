# 📰 Fake News Detection Using Machine Learning

## 🧠 Overview  
This project detects whether a news article is **real** or **fake** using machine learning techniques.  
It leverages text classification with **TF‑IDF Vectorization** and a **Passive Aggressive Classifier** to analyze news headlines and content.

---

## 📁Here’s a clean, professional **README.md** for your **Fake News Detection Project** — in plain text so you can copy‑paste directly into GitHub:

---

# 📰 Fake News Detection Using Machine Learning

## 🧠 Overview  
This project detects whether a given news headline is **real** or **fake** using machine learning techniques.  
It leverages the **Passive Aggressive Classifier** along with **TF‑IDF vectorization** to classify news articles based on their textual content.

---

## 📁 Dataset  
**File:** `news.csv`  
**Description:**  
Contains news articles with the following columns:  
- `title` → Headline of the news  
- `author` → Author name  
- `text` → Full news content  
- `subject` → Label (Fake or Real)

---

## ⚙️ Project Workflow  

### 1️⃣ Import Libraries  
- pandas, numpy  
- scikit‑learn (train_test_split, TfidfVectorizer, PassiveAggressiveClassifier, metrics)

### 2️⃣ Load Dataset  
Read the dataset and display the first few rows, shape, and column names.

### 3️⃣ Data Preprocessing  
- Remove null values  
- Combine `title` and `text` into a single `content` column  
- Define input features (`X`) and output labels (`y`)

### 4️⃣ Train‑Test Split  
Split the dataset into training and testing sets (80‑20 ratio).

### 5️⃣ Text Vectorization  
Use **TF‑IDF Vectorizer** to convert text into numerical features.

### 6️⃣ Model Training  
Train a **Passive Aggressive Classifier** with `max_iter=50`.

### 7️⃣ Evaluation  
Evaluate model performance using:  
- Accuracy Score  
- Confusion Matrix  
- Classification Report

---

## 📈 Results  
- **Accuracy:** ~92–95% (depending on dataset size and preprocessing)  
- **Model:** Passive Aggressive Classifier  
- **Insights:** TF‑IDF effectively captures word importance, and the classifier distinguishes fake vs real news with high accuracy.

---

## 🔮 Custom Prediction  
The program allows interactive prediction:  
- Enter a news headline in the console.  
- The model predicts whether it is **REAL NEWS** or **FAKE NEWS**.  
- Type `EXIT` to end the program.

---

## 🧩 Future Improvements  
- Try other models: Naive Bayes, Random Forest, or Deep Learning (LSTM, BERT)  
- Perform hyperparameter tuning  
- Deploy using Flask or Streamlit for a web interface  

---

## 🚀 How to Run  

1. **Clone the repository**  
   `git clone https://github.com/<your-username>/fake-news-detection.git`

2. **Navigate to the project folder**  
   `cd fake-news-detection`

3. **Install dependencies**  
   `pip install -r requirements.txt`

4. **Run the script**  
   `python fake_news_detection.py`

---

## 🧾 License  
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author  
**Devanshi**  
BCA (AI/ML) Student | Aspiring Data Analyst  
