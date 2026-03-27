# NLP_Homework

## 📌 Arabic Punctuation Restoration using NLP

This project implements a simple Natural Language Processing (NLP) approach to **restore punctuation marks in Arabic text**. The script takes unpunctuated Arabic sentences and predicts appropriate punctuation such as commas and periods.

---

## 🧠 Overview

In many real-world applications (e.g., speech-to-text or informal writing), Arabic text is often written without punctuation. This script aims to improve readability by automatically inserting punctuation marks into such text.

---

## ⚙️ How the Code Works

### 1. Input Text
The script starts with Arabic text that does not contain punctuation.

---

### 2. Text Processing
The text is processed and prepared for prediction:
- Splitting text into words  
- Organizing the sequence for analysis  

---

### 3. Punctuation Prediction
The core logic predicts punctuation marks based on the text sequence:
- Each word is analyzed in context  
- A punctuation label is assigned (e.g., comma, period, or none)  

---

### 4. Output Reconstruction
After prediction:
- Punctuation marks are inserted into the correct positions  
- The final sentence becomes more readable and grammatically structured  

---

## 🔄 Example

**Input:**
كيف حالك اليوم اتمنى ان تكون بخير

**Output:**
كيف حالك اليوم؟ أتمنى أن تكون بخير.


**CLICK [Notebook](https://colab.research.google.com/drive/1CW8XhlUjwDD4uXP-Q0I_FcU40CDbWXDU?usp=sharing) to check it out**
