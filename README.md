# Phishing Email and Safe Email Classification 📧🔒

## Team FCMB Group 6 🛡️
### Team Members:
- Chordia Laksh (U2323234G) 👨‍💻
- Dhaded Aditya Mahalingeshwar (U2323413C) 👨‍💻
- Savanur Akash (U2323703G) 👨‍💻

## Objective 🎯
This project aims to accurately classify and detect phishing emails, providing practical insights to prevent individuals from falling victim to phishing attacks in real-world scenarios.

## Dataset Description 📊
The dataset used in this project is "Phishing Email Detection" by subhajournal, available on Kaggle: [Phishing Email Detection Dataset](https://www.kaggle.com/datasets/subhajournal/phishingemails).
It contains labelled email data, with features representing various attributes of the emails. Out of 18,634 emails, 60.76% are safe, and the rest are phishing attempts.

## Problem Formulation 🤔
Phishing is a cybercrime tactic where attackers impersonate legitimate entities to deceive individuals into disclosing sensitive information such as login credentials, financial details, or personal data. The primary goal of this project is to accurately classify phishing and safe emails to combat the increasing rates of phishing attacks.

## Key Statistics on Phishing 📈
- 3.4 billion emails are sent in a day by cybercriminals.
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
   - Assessing the distribution of email classes
   - Summarizing length distributions of the different email types

3. **Analytical Visualization** 📊
   - Visualization of the distributions of lengths of the email types
   - WordCloud visualization to gain insight into word frequency
   - Identifying the most common words in both email types
   - Sentiment Analysis and visualization

4. **Training ML Models and Algorithmic Optimization** 🤖
   - Tokenization and two types of Vectorization to process text data
   - Models Used: Naïve Bayes, Logistic Regression, Random Forest, Gated Recurrent Unit (GRU) Neural Network, Support Vector Machine
   - Evaluation metrics: precision, accuracy, F1 score, ROC curve, Learning Curve, Confusion matrix
   - Selecting the best-performing model

5. **Testing Best Performing Model** 🧪
   - Testing sample emails to show the accuracy of prediction

## Results 📊
The project achieved promising results in accurately classifying phishing and safe emails. The best-performing model was Support Vector Machine, achieving an accuracy of 97% on the test dataset. Insights gained from EDA and analytical visualization provided valuable understanding of phishing email characteristics.

## Practical Implications 💼
Findings from this project have practical implications in real-world scenarios. Individuals can use the developed model to identify and avoid phishing emails, reducing the risk of falling victim to cyber attacks.

## References 📚
- Smith, G. (2024, April 10). [Top Phishing Statistics for 2024: Latest Figures and Trends](Link). StationX.
- Rushton, J. (2023, June 12). [50+ Phishing Statistics You Need to Know – Where, Who & What is Targeted](https://www.techopedia.com/phishing-statistics). Techopedia.
- Imperva. (2023). [What is phishing | Attack techniques & scam examples | Imperva](https://www.imperva.com/learn/application-security/phishing-attack-scam/). Imperva.
