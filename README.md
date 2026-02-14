# NLP-LLM-Analysis-on-Consumer-Complaints

**🔍 Project Overview**

This assignment applies NLP techniques to extract insights from consumer financial complaints. The goal is to analyze textual data, classify consumer issues, and predict sentiment while ensuring data quality and visualization.

**📝 Tasks and Implementations**

**1️⃣ Data Cleaning & Tokenization**
- Loaded the CFPB complaints dataset and handled encoding issues.
- Performed text cleaning: removed punctuation, stopwords, and frequent words.
- Applied stemming and lemmatization to normalize text.
- Identified most common words and roots in the complaints.

**2️⃣ Topic Modeling & Visualizations**
- Extracted top 10 consumer complaint topics based on product, sub-product, and issue fields.
- Created visualizations (bar charts, word clouds) to represent common complaint trends.

**3️⃣ Sentiment Analysis**
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

**4️⃣ Google Gemini Summarization & Feedback** 
- Generated 1-2 sentence summaries of complaint narratives using Google Gemini's API.
- Analyzed low sentiment complaints.
- Identified predictive words/themes for each sentiment score.

# 🛠️ Tech Stack

**Language:** Python

**Libraries:** Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn, ydata-profiling

**Models/APIs:** OpenAI GPT-3.5

# 🏆 Key Takeaways

**Customer Experience:** Prioritize clear timelines for dispute resolutions and enhance representative training.

**Branding:** Focus on transparency in addressing fraud concerns to build long-term credibility.

**Features:** Expand fraud detection systems and provide accessible documentation for disputed accounts.
