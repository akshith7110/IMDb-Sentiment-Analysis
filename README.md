# IMDb Movie Review Sentiment Analysis

## Project Goal
This project classifies movie reviews from the IMDb dataset as either positive or negative using machine learning.

---

## Dataset
The dataset consists of labeled IMDb movie reviews.  
(Source: [IMDb Dataset on Google Drive](https://drive.google.com/file/d/17AhYlX0Lihe7sMNJ9KcwOdMR9FuotU5-/view?usp=drive_link))

---

## My Approach
### 1. Data Cleaning
- Converted text to lowercase  
- Removed HTML tags and punctuation  
- Removed common English stopwords  

### 2. Feature Engineering
- Transformed the cleaned text into numerical features using TF-IDF (Term Frequency–Inverse Document Frequency)  

### 3. Models Used
- Logistic Regression  
- Support Vector Machine (SVM) with LinearSVC  

---

## Results

| Model                | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   | 88.3%    | 87.8%     | 88.9%  | 88.4%    |
| SVM (LinearSVC)       | 87.6%    | 86.8%     | 88.6%  | 87.7%    |

---

## Conclusion
Both the Logistic Regression and SVM models proved to be highly effective for this sentiment analysis task, achieving strong accuracy and correctly classifying the sentiment of movie reviews.
