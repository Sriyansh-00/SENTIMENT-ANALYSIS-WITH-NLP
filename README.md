# SENTIMENT-ANALYSIS-WITH-NLP

"COMPANY": CODTECH IT SOLLUTIONS

"NAME": T.SRIYANSH

"INTERN ID":CT04DM652

"DOMAIN": MACHINE LEARNING

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTHOSH



 DESCRIPTION

  **Sentiment Analysis on Restaurant Reviews Using TF-IDF and Logistic Regression**  

 **Introduction**  
Sentiment analysis is a natural language processing (NLP) technique used to determine the emotional tone behind textual data. In this task, we analyze restaurant reviews to classify them as either **positive (1)** or **negative (0)**. This classification helps businesses understand customer satisfaction, identify areas for improvement, and automate feedback processing.  

We use **TF-IDF (Term Frequency-Inverse Document Frequency)** for feature extraction and **Logistic Regression** for classification. TF-IDF converts text into numerical vectors by weighing words based on their importance, while Logistic Regression efficiently predicts binary outcomes (positive/negative sentiment).  

 **Dataset Overview**  
The dataset consists of **1,000 restaurant reviews**, each labeled as:  
- **1 (Liked)**: Positive sentiment (e.g., *"The food was amazing!"*)  
- **0 (Not Liked)**: Negative sentiment (e.g., *"Terrible service and cold food."*)  

 **Key Challenges in Sentiment Analysis**  
1. **Text Preprocessing**: Removing noise (punctuation, stopwords) while retaining meaningful words.  
2. **Feature Extraction**: Converting unstructured text into numerical features that machine learning models can process.  
3. **Model Selection**: Choosing an algorithm that balances accuracy and interpretability.  

**Methodology**  

 **1. Text Preprocessing**  
Before applying machine learning, we clean the text by:  
- Converting to lowercase  
- Removing punctuation and special characters  
- Eliminating stopwords (e.g., "the", "and", "is")  
- (Optional) Applying stemming/lemmatization to reduce words to their base forms  

**2. Feature Extraction with TF-IDF**  
TF-IDF transforms text into a numerical format by calculating:  
- **Term Frequency (TF)**: How often a word appears in a review.  
- **Inverse Document Frequency (IDF)**: Downweights common words (e.g., "the") while emphasizing rare, meaningful terms.  

This ensures words like **"delicious"** (strong positive indicator) carry more weight than generic words like **"food"**.  

**3. Model Training with Logistic Regression**  
Logistic Regression is ideal for binary classification because:  
- It predicts probabilities (0 to 1) for sentiment classes.  
- It is interpretable—we can analyze which words most influence predictions.  
- It performs well on medium-sized datasets like this one.  

 **4. Model Evaluation**  
We split the data into **80% training** and **20% testing** sets. Performance is measured using:  
- **Accuracy**: Percentage of correctly classified reviews.  
- **Precision & Recall**:  
  - **Precision**: Measures how many predicted positives are truly positive.  
  - **Recall**: Measures how many actual positives were correctly identified.  
- **F1-Score**: Harmonic mean of precision and recall.  

 **Expected Results**  
- **Accuracy**: ~75-85%  
- **Precision & Recall**: ~80% for both classes  
- **Key Influential Words**:  
  - Positive: *"amazing," "great," "delicious," "friendly"*  
  - Negative: *"terrible," "awful," "slow," "overpriced"*  

 **Business Applications**  
1. **Automated Review Filtering**: Quickly categorize feedback for response prioritization.  
2. **Trend Analysis**: Track sentiment changes over time to assess improvements.  
3. **Competitor Benchmarking**: Compare sentiment scores against rival restaurants.  
4. **Menu Optimization**: Identify frequently praised or criticized dishes.  

 **Limitations & Future Improvements**  
1. **Sarcasm & Context**: NLP struggles with sarcasm (e.g., *"Great, my food arrived cold."*).  
2. **Negation Handling**: Phrases like *"not good"* require advanced NLP techniques.  
3. **Model Enhancements**:  
   - Try **Deep Learning (LSTM, BERT)** for better context understanding.  
   - Use **n-grams** to capture phrases (e.g., *"very slow"* vs. *"slow"*).  
   - Apply **hyperparameter tuning** to optimize model performance.  

 **Conclusion**  
This sentiment analysis task demonstrates how **TF-IDF + Logistic Regression** can effectively classify restaurant reviews. The model helps businesses automate feedback analysis, improve customer experience, and make data-driven decisions. Future enhancements could involve more advanced NLP techniques for higher accuracy and better handling of complex language nuances.  
