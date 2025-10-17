# Transgender Sentiment Analysis: Reddit & YouTube

## 📌 Project Overview
This is a **personal project demo** showcasing a full Data Analyst pipeline. The original dataset and analysis pipeline were inspired by a course project from **RMIT University**, as part of the course *Social Media & Networking Analysis*. The author participated in the original **3-person group** that designed the dataset and initial analysis.  

The project focuses on collecting public comments from both **Reddit** and **YouTube** using their official APIs, performing data cleaning, preprocessing, exploratory analysis, sentiment analysis, and statistical modeling. Key techniques include **Python**, **NLTK tokenization**, and **VADER Sentiment Analysis**. Finally, **Power BI** is used to create interactive visualizations and dashboards.  

This repo serves as a **full Data Analyst pipeline demo**, demonstrating skills from raw data collection to polished dashboard storytelling.  

---

## 🧩 Project Workflow
1. **Data Collection**
   - Fetch comments from Reddit (via PRAW) and YouTube (via YouTube API).  
   - Filter relevant subreddit threads and YouTube videos around transgender-related topics.  

2. **Data Cleaning & Preprocessing**
   - Handle missing values, duplicates, and inconsistent text formats.  
   - Tokenization and normalization of textual data using NLTK.  

3. **Sentiment Analysis**
   - Apply VADER Sentiment Analyzer to quantify positive, negative, and neutral sentiments.  
   - Perform statistical modeling to uncover trends and patterns.  

4. **Data Visualization & Dashboard**
   - Use **Power BI** to build dashboards showcasing sentiment trends, platform comparisons, and key insights.  
   - Generate static visualizations for reports and presentations.  

---

## ⚙️ Environment & Setup Tips
To run the Python demo scripts successfully:
- Python >= 3.9
- Libraries: `pandas`, `nltk`, `matplotlib`, `seaborn`, `numpy-2.2.6`, `scipy-1.15.3`
- Ensure NLTK datasets (like `vader_lexicon`) are downloaded:
```python
import nltk
nltk.download('vader_lexicon')
```

---

## Sample Dataset for Demonstration

Due to the file size constraints, we have included **sample datasets** which are less than 10 MB instead of full data.

- `reddit_sample.json` – Subset of Reddit data (randomly sampled)
- `youtube_sample.json` – Subset of YouTube data (randomly sampled)

The full datasets (original Reddit: 25.8 MB, YouTube: 17.2 MB) were used during analysis but are excluded to meet size restrictions. All scripts will still work on these smaller files for demonstration purposes.

---

## 🌈 Notes / Disclaimer
- This repo is intended for **personal learning and demo purposes**.  
- Original datasets are based on the RMIT course project; some datasets may be **anonymized or modified** for demonstration.  
- Any use of Reddit or YouTube data should comply with their **API usage terms**.

---

### **Optional: Add in How to Run Demo**
```markdown
## ▶️ How to Run the Demo
1. **Jupyter Notebook Scripts**
   - Open `notebooks/` folder.  
   - **Recommended:** Use Google Colab to run the scripts without worrying about local library versions.  
   - Alternatively, run locally with Python >=3.9 and the required libraries installed.  
```

---