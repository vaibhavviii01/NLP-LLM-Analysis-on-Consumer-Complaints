# NLP-LLM-Analysis-on-Consumer-Complaints

🔍 Project Overview
This assignment applies NLP techniques to extract insights from consumer financial complaints. The goal is to analyze textual data, classify consumer issues, and predict sentiment while ensuring data quality and visualization.

📝 Tasks and Implementations

1️⃣ Data Cleaning & Tokenization
- Loaded the CFPB complaints dataset and handled encoding issues.
- Performed text cleaning: removed punctuation, stopwords, and frequent words.
- Applied stemming and lemmatization to normalize text.
- Identified most common words and roots in the complaints.

2️⃣ Topic Modeling & Visualizations
- Extracted top 10 consumer complaint topics based on product, sub-product, and issue fields.
- Created visualizations (bar charts, word clouds) to represent common complaint trends.

3️⃣ Sentiment Analysis
- 3.1 Vader Sentiment Scoring
Used VADER (Valence Aware Dictionary and sEntiment Reasoner) to assign sentiment scores on a 1-5 scale:
1: Highly negative
2: Negative
3: Neutral
4: Positive
5: Highly positive
- 3.2 Sentiment Prediction Model
Built classification models (Logistic Regression, Random Forest, etc.) to predict sentiment.
Identified key words influencing each sentiment rating.
Validated model performance and compared actual vs. predicted sentiments.

4️⃣ Google Gemini Summarization & Feedback 
- Generated 1-2 sentence summaries of complaint narratives using OpenAI's GPT-3.5 API.
- Analyzed low sentiment complaints and asked GPT-3.5 for possible improvements.
- Identified predictive words/themes for each sentiment score.
  
🏆 Key Takeaways
NLP techniques help uncover patterns in unstructured financial complaints.
Sentiment analysis & ML models provide insights into customer dissatisfaction.
Google Gemini is a powerful tool for summarizing and analyzing large-scale complaints.
