# Gujarati Sentiment Analysis (GSA)
**Gujarati Sentiment Analysis**

This project aims to perform Gujarati Sentiment Analysis, classifying text as **Positive (સકારાત્મક) [1]**, **Negative (નકારાત્મક) [0]**, **or Neutral (તટસ્થ) [2]** using different machine learning models. It includes a **Flask-based web application** that ensures **only Gujarati text input is allowed**. If non-Gujarati text is entered, an error message is displayed.

The web interface contains:

✅ A **text area** for Gujarati text input (restricts non-Gujarati text)

✅ **Two buttons:**

  •	**Analyze Sentiment:** Performs sentiment classification

  •	**Re-enter Sentence:** Clears the input for new text

🔍 **Machine Learning Models Implemented**

1️⃣ **Logistic Regression Model** (Accuracy: **83.52%**) [Model 1 (LR)]

  •	Uses **TF-IDF vectorization + Logistic Regression**

  •	Web-based UI for real-time sentiment prediction

2️⃣ **SVM Model (Linear Kernel - SVC)** (Accuracy: **84.88%**) [Model 2 (SVM)]

  •	Uses **TF-IDF vectorization + Support Vector Machine (SVC - Linear Kernel)**

  •	Provides improved accuracy over Logistic Regression

3️⃣ **Ensemble Learning Model** (Accuracy: **81.40%**) [Model 3 (SVM+RF+LR)]

  •	Combines **SVM + Random Forest + Logistic Regression** for robust sentiment classification

  •	Balances multiple classifiers for better performance

Each model has a **separate UI but identical functionality**.

🚀 **Features**

✅ **Strict Gujarati text validation** (Restricts non-Gujarati input)

✅ **User-friendly Web Interface** with Flask

✅ **ML models trained with TF-IDF vectorization**

✅ **Interactive buttons for easy interaction**

✅ **Pickle-based model serialization** for efficient deployment

🔧 **Tech Stack**

•	**Programming Language:** Python

•	**Machine Learning:** Scikit-learn (Logistic Regression, SVM, Random Forest)

•	**NLP Preprocessing:** TF-IDF, NLTK, Indic NLP Library

•	**Web Framework:** Flask

•	**Frontend:** HTML, CSS, JavaScript

🚀 **Future Enhancements**

• **Expand Model Selection:** Add advanced models (LSTM, BERT, GPT) and fine-tune for better accuracy.

• **Multilingual Support:** Support multiple languages and allow user selection.

• **Sentiment Breakdown:** Provide emotion detection (happy, sad, etc.).

• **Real-Time Feedback & Visualization:** Show sentiment graphs and word clouds.

• **API for Sentiment Analysis:** Develop a RESTful API for integration.

• **Automated Data Labeling:** Implement semi-automated labeling with active learning.

• **Mobile App Integration:** Build a mobile app with OCR for Gujarati text.

• **Sentiment Over Time:** Track sentiment trends and keywords/hashtags.

• **Personalized Sentiment Feedback:** Offer insights into users' sentiment history.

• **Advanced Preprocessing:** Use techniques like NER and dependency parsing.

• **Model Performance Monitoring:** Implement a performance dashboard.

• **Feedback Mechanism:** Collect user feedback to improve model accuracy.
