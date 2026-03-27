# NLP_Homework

## Arabic Punctuation Processing using NLP

This project contains a Python script that performs basic preprocessing on Arabic text as part of a Natural Language Processing (NLP) task. The script focuses on cleaning text and removing punctuation and non-Arabic content to prepare data for further analysis.

---

## Overview

Arabic text often includes noise such as English words, numbers, URLs, and punctuation. This script demonstrates how to clean and normalize such text so it can be used in NLP applications like text classification or machine learning models.

---

## How the Code Works

### 1. Reading the File
The script opens and reads a text file containing Arabic content:
- Loads the file in read mode  
- Stores all text into a variable  

---

### 2. Cleaning the Text
Using regular expressions, the script removes:
- English letters  
- Numbers  
- URLs and hashtags  
- Special characters  

This ensures that only meaningful Arabic text remains.

---

### 3. Filtering Arabic Characters
The script relies on the Unicode range for Arabic characters to keep only valid Arabic letters and discard everything else.

---

### 4. Removing Punctuation
All punctuation marks are removed to simplify the dataset and make it suitable for NLP tasks.

---

### 5. Output
The cleaned Arabic text is printed, resulting in:
- Plain Arabic words  
- No punctuation  
- No non-Arabic characters  

---



**CLICK [Notebook](https://colab.research.google.com/drive/1CW8XhlUjwDD4uXP-Q0I_FcU40CDbWXDU?usp=sharing) to check it out**
