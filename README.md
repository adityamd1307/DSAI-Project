# Phishing Email and Safe Email Classification 📧🔒

## Team FCMB Group 6 🛡️

### Team Members 
- Chordia Laksh (U2323234G)
- Dhaded Aditya Mahalingeshwar (U2323413C)
- Savanur Akash (U2323703G)

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
   - Models:
      - **Naïve Bayes**: The Naïve Bayes classifier is a popular supervised machine learning algorithm used for classification tasks such as text classification. It belongs to the family of generative learning algorithms, which means that it models the distribution of inputs for a given class or category.
      - **Logistic Regression**: a statistical method used for binary classification tasks, where the outcome variable is categorical and has only two possible outcomes. It uses the sigmoid function to model the probability of the binary outcome. It is effective in detecting phishing emails due to its computational efficiency and regularisation techniques that improve its performance.
      - **Random Forest**: a popular model used for both classification and regression tasks. It builds multiple decision trees during training and merges their predictions to improve accuracy and reduce overfitting. Since random forest chooses the most important features for classification and yields high accuracy, it helps us to solve our task.
      - **GRU Neural Network**: The Gated Recurrent Unit is an efficient type of recurrent neural network (RNN) with update and reset gates. Their gated mechanisms and fewer parameters enhance accuracy, making them valuable for real - time systems in filtering deceptive content and identifying malicious patterns effectively.
      - **Support Vector Machine**: SVMs are a supervised machine learning algorithm. They distinguish between two classes by finding the optimal hyperplane that maximizes the margin between the closest data points of opposite classes. This enables it to generalize well to new data and make accurate classification predictions. We tune the kernel function, C value and Gamma to find the best model
   
   - Evaluation metrics: Precision, Accuracy, F1 score, ROC curve, Learning Curve, Confusion matrix.
     To compare the performance of our models, we used the above metrics. F1 Score was our primary consideration since it is useful for measuring the performance for classification models when you have imbalanced data because it takes into account the type of errors — false positive and false negative. This was suitable for our dataset which contained a slight imbalance in email classes.

5. **Testing Best Performing Model** 🧪
   - Testing sample emails for prediction accuracy using best-performing SVM Model.

## Results 📊
The project achieved promising results in accurately classifying phishing and safe emails. Although regression, random forest, and GRU neural network were very good models too, the best-performing model was Support Vector Machine, achieving an accuracy of 97% on the test dataset. The insights gained from exploratory data analysis and analytical visualization provided valuable understanding of the characteristics of phishing emails.
![Evaluation Metrics](https://github.com/adityamd1307/DSAI-Project-FCMB-team-6/assets/102379249/dd5608cd-7b06-45c8-b29f-cbfb04c49463)

### Lessons Learned:
- Handling datasets that need thorough analysis and cleaning before usage.
- Utilizing new tools for data visualization and analysis such as WordCloud and Sentiment Analysis.
- Tokenization of text for machine learning model processing.
- Introduction and implementation of various algorithms like Random Forest, GRU Neural Network, Naive Bayes, and Support Vector Machine.
- Working with libraries like Keras and Tensorflow.
- Assessing model correctness based on precision, recall, F1 score, learning curve, ROC curve, confusion matrix, and epochs.

### Conclusion:
- Multiple models can be used to classify emails with varying accuracy.
- Phishing emails often exhibit distinct features that aid in prediction.
- Data preprocessing significantly improves model performance.
- Visualizing data before modelling provides crucial insights.
- Implementing similar models in real-world scenarios for phishing email identification is viable.

## Practical Implications 💼
The findings of this project have practical implications in real-world scenarios, where individuals can use the developed model to identify and avoid phishing emails, thereby reducing the risk of falling victim to cyber attacks.

### Individual Contributions:
- Chordia Laksh (U2323234G): Data Preprocessing, EDA, WordCloud, Tokenisation, Support Vector Machine
- Dhaded Aditya Mahalingeshwar (U2323413C): Sentiment Analysis, GRU Neural Network, Statistical Inference
- Savanur Akash (U2323703G): EDA, Analytical Visualisation, Logistic Regression, Random Forest, Practical Implications
  
## References 📚
- Smith, G. (2024, April 10). [Top Phishing Statistics for 2024: Latest Figures and Trends](Link). StationX.
- Rushton, J. (2023, June 12). [50+ Phishing Statistics You Need to Know – Where, Who & What is Targeted](https://www.techopedia.com/phishing-statistics). Techopedia.
- Imperva. (2023). [What is phishing | Attack techniques & scam examples | Imperva](https://www.imperva.com/learn/application-security/phishing-attack-scam/). Imperva.
- Proofpoint. [What Is Phishing? - Definition, Types of Attacks & More](https://www.proofpoint.com/us/threat-reference/phishing#:~:text=requires%20human%20defenses).
- Abnormal. [5 Reasons Phishing is Your Biggest Cybersecurity Problem](https://abnormalsecurity.com/blog/phishing-biggest-cybersecurity-problem).
- Cofense. [How to Spot Phishing Emails | 7 Helpful Tips for Employees](https://cofense.com/knowledge-center/how-to-spot-phishing/).
- ScienceDirect Topics. [Phishing Detection - an overview](https://www.sciencedirect.com/topics/computer-science/phishing-detection).
