# Phishing Email and Safe Email Classification 📧🔒

## Team FCMB Group 6 🛡️
### Team Members and Individual Contributions:
- Chordia Laksh (U2323234G): Data Preprocessing, EDA, WordCloud, Tokenisation, Support Vector Machine
- Dhaded Aditya Mahalingeshwar (U2323413C): Sentiment Analysis, GRU Neural Network, Statistical Inference
- Savanur Akash (U2323703G): EDA, Visualisation, Logistic Regression, Random Forest, Practical Implications

## Objective 🎯
This project aims to accurately classify and detect phishing emails, providing practical insights to prevent individuals from falling victim to phishing attacks in real-world scenarios.

## Dataset Description 📊
The dataset used in this project is the "Phishing Email Detection" dataset by subhajournal, available on Kaggle: [Phishing Email Detection Dataset](https://www.kaggle.com/datasets/subhajournal/phishingemails). It consists of email text and email types (Safe and Phishing). Out of 18,634 emails, 60.76% are safe, and the rest are phishing attempts. There are also 16 unclassified values.

## Problem Formulation 🤔
Phishing is a cybercrime tactic where attackers impersonate legitimate entities to deceive individuals into disclosing sensitive information such as login credentials, financial details, or personal data. The primary goal of this project is to accurately classify phishing and safe emails to combat the increasing rates of phishing attacks.

## Key Statistics on Phishing 📈
- 3.4 billion emails are sent daily by cybercriminals.
- Over 48% of emails sent in 2022 were spam.
- Around 36% of all data breaches involve phishing.
- In 2022, APWG logged approximately 4.7 million phishing attacks, increasing by more than 150% yearly since 2019.
- Educational institution employees are most likely to open a phishing email.
- Cybercriminals stole $44.2 million through phishing attacks in 2021.
- 323,972 internet users fell victim to phishing attacks in 2021.

## Project Flow 🔄
1. **Data Cleaning and Preparation** 🧹
   - Removal of null values
   - Removal of irrelevant characters and symbols
   - Conversion to lowercase for standardisation
   - Structured labelling for ease of analysis (Phishing = 1, Safe = 0)

2. **Exploratory Data Analysis (EDA)** 🔍
   - Distribution analysis: 11,322 safe emails and 7,312 phishing emails.
   - Length distributions: Phishing emails are generally shorter, possibly to create urgency.
   - Sentiment Analysis: Phishing emails tend to use more emotional language.

3. **Analytical Visualization** 📊
   - Length distribution visualization
   - WordCloud for word frequency insights
   - Identifying common words
   - Sentiment Analysis visualization

4. **Training ML Models and Algorithmic Optimization** 🤖
   - Tokenization: Breaking text into tokens for analysis.
   - Vectorization: Using TF-IDF to assign numerical values to words.
   - Models: Naïve Bayes, Logistic Regression, Random Forest, GRU Neural Network, Support Vector Machine.
   - Evaluation metrics: precision, accuracy, F1 score, ROC curve, Learning Curve, Confusion matrix.

5. **Testing Best Performing Model** 🧪
   - Testing sample emails for prediction accuracy.

## Results 📊
The best-performing model was the Support Vector Machine, with 98% accuracy and a 97% f-score. Insights from EDA and analytical visualization provided a deeper understanding of phishing email characteristics.

## Practical Implications 💼
The developed model can help individuals identify and avoid phishing emails, reducing the risk of falling victim to cyber attacks.

## References 📚
- Smith, G. (2024, April 10). [Top Phishing Statistics for 2024: Latest Figures and Trends](Link). StationX.
- Rushton, J. (2023, June 12). [50+ Phishing Statistics You Need to Know – Where, Who & What is Targeted](https://www.techopedia.com/phishing-statistics). Techopedia.
- Imperva. (2023). [What is phishing | Attack techniques & scam examples | Imperva](https://www.imperva.com/learn/application-security/phishing-attack-scam/). Imperva.
- Proofpoint. [What Is Phishing? - Definition, Types of Attacks & More](https://www.proofpoint.com/us/threat-reference/phishing#:~:text=requires%20human%20defenses).
- Abnormal. [5 Reasons Phishing is Your Biggest Cybersecurity Problem](https://abnormalsecurity.com/blog/phishing-biggest-cybersecurity-problem).
- Cofense. [How to Spot Phishing Emails | 7 Helpful Tips for Employees](https://cofense.com/knowledge-center/how-to-spot-phishing/).
- ScienceDirect Topics. [Phishing Detection - an overview](https://www.sciencedirect.com/topics/computer-science/phishing-detection).
