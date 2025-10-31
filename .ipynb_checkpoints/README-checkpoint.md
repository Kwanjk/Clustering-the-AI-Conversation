# 🧠 Clustering the AI Conversation  
**How People Feel About Artificial Intelligence in the 21st Century**

This project analyzes nearly 300 recent news headlines about Artificial Intelligence to understand how the public perceives AI — what we celebrate, what we fear, and how those narratives reflect human adaptation to technology.

---

## 📂 Project Overview
Using Python, this project clusters AI-related news articles into themes and measures emotional tone across topics like creativity, ethics, education, and mental health.  
It reveals how public discourse around AI reflects broader human behavior — balancing curiosity, anxiety, and moral concern.

---

<details>
<summary>⚙️ <b>Methods and Tools</b></summary>

**Libraries Used**
- `pandas`, `numpy`
- `scikit-learn` (KMeans, PCA)
- `TextBlob` (sentiment analysis)
- `GoogleNews` (data collection)
- `matplotlib`, `wordcloud`

**Pipeline**
1. Collected AI-related headlines using the Google News API  
2. Cleaned and preprocessed the dataset  
3. Transformed text into TF-IDF vectors  
4. Clustered headlines using **K-Means (k=9)**  
5. Visualized clusters and top keywords with **word clouds and PCA**  
6. Performed sentiment analysis to interpret public tone (*positive → negative*)  

</details>

---

<details>
<summary>🧩 <b>Key Findings</b></summary>

| Cluster | Theme | Average Tone (–1 → +1) |
|----------|--------|------------------------|
| Creative Tools & Platforms | +0.31 |
| AI & Cognition | +0.26 |
| AI Ethics in Education | +0.10 |
| AI Governance & Policy | +0.06 |
| AI in Education | –0.02 |
| ChatGPT & Societal Impact | –0.07 |
| AI & Mental Health | –0.07 |
| AI & Global Economy | –0.38 |

- **Positive clusters** reflect fascination, creativity, and empowerment  
- **Negative clusters** show anxiety about economy, mental health, and loss of control  
- This duality mirrors a human *“wonder vs. worry”* mindset — curiosity toward progress, caution toward consequence  

</details>

---

<details>
<summary>🧭 <b>Behavioral Insight</b></summary>

From an **Information Science** perspective, this dataset captures *sensemaking in motion*.  
Humans use information — like news stories — to negotiate identity and emotion during periods of rapid change.  

> “We embrace technology that empowers us, and resist technology that defines us.”  

- Positive clusters represent **assimilation** (fitting AI into existing frameworks)  
- Negative clusters represent **accommodation** (rewriting frameworks to restore balance)  
- Together, they map how humans emotionally adapt to technological acceleration  

</details>

---

<details>
<summary>📊 <b>Visual Highlights</b></summary>

*(See `/visuals` or open the Jupyter Notebook)*

**Included Visuals**
- Elbow Plot → optimal number of clusters (k=9)  
- PCA Scatter Plot → visualizing 9-cluster distribution  
- Word Clouds → dominant terms for each cluster  
- Sentiment Distribution Chart → wonder vs. worry  
- Overall Word Cloud → global theme frequency  

</details>

---

<details>
<summary>🔍 <b>Next Steps</b></summary>

- Expand dataset with **Reddit** and **X (Twitter)** discussions for grassroots sentiment tracking  
- Compare **2025 vs. 2023** data to detect tone shifts over time  
- Explore **BERT-based embeddings** for deeper semantic clustering  
- Build a small **dashboard in Streamlit or Tableau** for interactive exploration  

</details>

---

## 🧑‍💻 Author
**Joshua Kwan**  
Information Science Major  
Washington and Lee University  

> “Information doesn’t just describe adaptation — it *is* adaptation.”

---

## 📎 Repository Structure

├── ai_news_dataset_full_20251029.csv # Raw scraped data
├── ai_news_clustered.csv # Clustered dataset
├── ai_perception_clustering.ipynb # Analysis notebook
├── visuals/ # Word clouds & plots
├── LICENSE
└── README.md


---

## 🔗 Related Links
- 📰 [**Medium Post: Human Adaptation in the Age of AI**](https://medium.com)  
- 💻 [**GitHub Repository**](https://github.com/Kwanjk/ai_perception_clustering)

---

## 🧠 Key Takeaways for Information Science

1. **Sensemaking is Emotional, Not Just Logical.**  
   Headlines reflect both fascination and fear — showing that people use emotion to interpret rapid innovation.  

2. **Information Shapes Identity.**  
   Discourse around AI reveals how society negotiates self-concept and moral boundaries through information.  

3. **Adaptation Is the New Literacy.**  
   The ability to reinterpret and integrate new information may be the defining human skill of the 21st century.  

---

⭐ *If you found this useful, consider starring the repository or sharing your own analysis of public sentiment toward AI!*