# 📊 YouTube Trending Video Analysis

What makes a video go viral on YouTube? This project dives into the US trending videos dataset from Kaggle to uncover patterns, behaviors, and oddities in what people watch and when.

---

## 📁 Dataset
- **Source**: [Kaggle - Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- **File Used**: `Cavideos.csv`
- Contains ~40,881 trending YouTube video records across time.

---

## 🎯 Project Goals
- Clean and preprocess a real-world dataset
- Engineer new features like `days_to_trend`, `publish_hour`, etc.
- Visualize data to find trends in views, categories, tags, and posting time
- Present findings in a visually engaging and interpretable format

---

## 🔧 Tools Used
- Python 🐍
- pandas
- matplotlib / seaborn / plotly
- wordcloud
- Jupyter Notebook

---

## 📊 Key Visuals

### 📌 Trending Categories
![Categories](assets/category_boxplot.png)

### ☁️ Most Common Tags
![WordCloud](assets/wordcloud_tags.png)

### ⏱️ When Should You Publish?
![Views by Hour](assets/views_by_hour.png)

### 🔥 Likes vs Views Scatter
![Scatter](assets/likes_vs_views.png)

---

## 🔍 Key Insights

- **Music, Comedy, and Entertainment** dominate trending categories.
- Videos with missing or default tags like `'None'` still manage to trend.
- Most trending videos are published between **noon and 6 PM**.
- The **"days to trend"** varies wildly—some videos trend within hours, others take days.
- Channels like *Logan Paul* and *Gordon Ramsay* have high trending frequency.

---

## 🚀 How to Run
1. Clone the repo
2. Run `youtube_analysis.ipynb` in a Jupyter environment
3. Visuals are saved inside `assets/`

---

## 💡 Possible Improvements
- Sentiment analysis of titles/descriptions
- Predictive model: Will this video trend?
- Compare trends across multiple countries

---

## 📬 Contact
Made with 💻 by [YourName]  
[LinkedIn] | [GitHub]

---

