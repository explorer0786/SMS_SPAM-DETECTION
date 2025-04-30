# 📩 SMS/Email Spam Detection Classifier

A full-fledged machine learning project to detect whether an incoming **SMS or email message is Spam or Not Spam**. The app uses NLP for text preprocessing, **TF-IDF** for vectorization, and **Multinomial Naive Bayes** for classification. Built with **Python**, **scikit-learn**, **NLTK**, and deployed using **Streamlit**.

---
![image](https://github.com/user-attachments/assets/825efc44-d67e-4a51-9952-0a69694ccfb3)


## 🧠 Use Case

In today’s digital world, people are constantly flooded with promotional and phishing messages. **Spam detection** is critical for:

- 📬 Email services to protect users from scams
- 📱 Messaging platforms to auto-filter junk
- 🛡️ Enhancing user trust by reducing clutter
- 🤖 Automating text classification tasks in customer service/chatbots

---

## 🧰 Features

✅ Clean, minimal, interactive UI with **Streamlit**  
✅ Real-time message classification (Spam / Not Spam)  
✅ Fast and efficient using **TF-IDF + Naive Bayes**  
✅ Fully modular and reusable code  
✅ Lightweight and deployable anywhere

---

## 📊 Model Overview

- **Algorithm**: Multinomial Naive Bayes
- **Vectorizer**: TF-IDF
- **Accuracy**: ~95% (on test data)
- **Text Preprocessing**:
  - Lowercasing
  - Tokenization
  - Removing stopwords & punctuation
  - Stemming using Porter Stemmer

---

## 🧱 Project Structure
📁 sms-spam-classifier/

├─ 📄 spam.csv  
╰─ 📥 Raw SMS data from the UCI dataset  

├─ 🛠️ training.py  
├─ 🧹 Cleans and preprocesses the text  
├─ 🧾 Applies TF-IDF vectorization  
├─ 🤖 Trains Multinomial Naive Bayes model  
╰─ 💾 Saves model and vectorizer as pickle files  

├─ 🧠 model.pkl  
╰─ 🧬 Serialized trained model  

├─ 🧾 vectorizer.pkl  
╰─ 📊 Fitted TF-IDF vectorizer  

├─ 🚀 app.py  
├─ 🌐 Streamlit web interface  
├─ 📤 Accepts user SMS input  
├─ 🔁 Preprocesses and vectorizes input  
├─ 🎯 Predicts spam or not  
╰─ 📺 Displays result  

├─ 📦 requirements.txt  
╰─ 🧰 Python dependencies  

├─ 📘 README.md  
╰─ 📝 Full project documentation  

╰─ 🖼️ assets/  
   ╰─ 🖼️ screenshot.png  
      ╰─ 🖥️ Preview of the web interface  

