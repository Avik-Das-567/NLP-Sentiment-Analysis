# Sentiment Analysis in NLP
### App Link
- https://nlp-sentiment-analysis-1.streamlit.app/
---
### What is Sentiment Analysis?
- Sentiment Analysis is a technique in **Natural Language Processing (NLP)** used to identify the **emotion** or **opinion** in a piece of text.
- It helps in understanding whether the text is **Positive**, **Negative**, or **Neutral**.
---
### Why is Sentiment Analysis Useful?
- Used in **product reviews**, **social media**, **feedback analysis**.
- Companies use it to know how customers **feel** about their brand.
- Helps in making **business decisions** based on public opinion.
---
### Sentiment Types

| **Sentiment** | **Meaning**                             | **Example Text**                     |
| ------------- | --------------------------------------- | ------------------------------------ |
| Positive      | Happy or satisfied opinion              | "I love this product!"               |
| Negative      | Angry, unhappy, or dissatisfied opinion | "This is the worst experience ever!" |
| Neutral       | Neither good nor bad                    | "It was okay, nothing special."      |

---
### Code Example
```
from textblob import TextBlob

text = "I really enjoy using this app. It's fantastic!"
blob = TextBlob(text)
print(blob.sentiment)
```
- **Output :**
```
Sentiment(polarity=0.75, subjectivity=0.9)
```
-  - **Polarity** ranges from -1 (negative) to +1 (positive).
   - **Subjectivity** ranges from 0 (objective) to 1 (subjective).
---
### Required Python Packages
- **`textblob`**
- **`streamlit`**
---
### Additional Insights :
- Sentiment analysis is used in **Twitter monitoring** and **political debates**.
- It's part of **opinion mining** in text analytics.
- Tools like **TextBlob**, **VADER**, and **BERT** are used for sentiment classification.
---
