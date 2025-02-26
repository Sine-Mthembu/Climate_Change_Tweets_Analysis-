# Climate Change Tweets Analysis


## 📌 Project Overview
This project analyzes tweets related to climate change using Natural Language Processing (NLP) techniques and Large Language Models (LLMs). The aim is to uncover patterns, sentiments, key topics, and named entities within the discussions around climate change on Twitter.

## Data Source
The data was sourced from Twitter, consisting of tweets related to climate change. The dataset includes a mixture of public opinions, news updates, and scientific discussions.
By Sibu at [Twitter Sentiment Data](https://raw.githubusercontent.com/sibukele/sa_tweets/main/twitter_sentiment_data.csv)

## 🔍 Key Features
- **Word Cloud:** Visualizes the most common words in tweets.
- **Sentiment Analysis:** Classifies tweets as Positive, Negative, or Neutral using VADER.
- **Topic Modeling:** Groups tweets into key themes using LDA.
- **Named Entity Recognition (NER):** Extracts names, locations, and organizations.
- **Summarization:** Uses T5 Transformer to generate summaries of long tweets.
- **Data Visualization:** Displays insights using matplotlib and seaborn.

## 🛠️ Technologies Used
- Python
- NLP Libraries: `nltk`, `spaCy`, `gensim`, `transformers`
- Data Processing: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`, `wordcloud`

## 📊 Results Summary
### 1️⃣ Word Cloud
- The most frequently mentioned words include **climate change**, **global warming**, **believe**, **trump** and **science**.
- Indicates discussions around belief in climate change and scientific perspectives.

### 2️⃣ Sentiment Analysis
- **Negative tweets** dominate the dataset, as expected for climate change discussions.
- **Positive sentiment** is still present, reflecting hopeful narratives about solutions and activism.

### 3️⃣ Topic Modeling
- **Topic 0:** Politics & climate agreements (*Trump, Paris Agreement, EPA*)
- **Topic 1:** Climate action and world response (*world, action, take, fight*)
- **Topic 2:** Global warming and skepticism (*global warming, real, weather*)
- **Topic 3:** Public opinions and energy (*believe, people, oil, energy*)

### 4️⃣ Named Entity Recognition (NER)
- Extracted notable names like **Leonardo DiCaprio**, locations such as **Odisha**, and cardinal values (*e.g., 15 years*).
- Suggests influence of public figures in climate discourse.

### 5️⃣ Summarization
- Compressed long tweets while preserving key climate-related insights.
- Useful for digesting large volumes of climate-related discussions.


## 📌 Future Improvements
- Expand dataset for more diverse insights.
- Fine-tune topic modeling to improve thematic distinctions.
- Use a transformer-based sentiment model for more nuanced sentiment analysis.

![Sentiments](https://github.com/user-attachments/assets/95c92119-d4ec-4a72-a531-c06455732ed6)

![my_twitter_wordcloud_1](https://github.com/user-attachments/assets/0484a19d-f657-46d1-ad71-179ac69adcdc) 

![top_1](https://github.com/user-attachments/assets/c10784a0-522f-4839-a6bf-68d455026d26)

![Untitled](https://github.com/user-attachments/assets/0657fb36-c30d-4195-9ef3-72752108a989)


![top_entities](https://github.com/user-attachments/assets/5d4207db-33cc-40ff-9707-6163cd376baa)


