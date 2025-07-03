# 📊 YouTube Analytics Project – SuuZ Channel

This project explores data from **SuuZ**, a YouTube channel that focused on study and productivity content during the 2020 COVID-19 lockdown. The goal is to analyze historical performance using YouTube Analytics data and extract meaningful insights around viewer engagement, content strategy, and channel growth.

---

## 📌 About the Channel

- 🎥 Channel Name: **SuuZ**
- 📅 Active Year: 2020 (COVID lockdown)
- 📊 Total Performance:
  - **Subscribers**: 281  
  - **Views**: 61,600  
  - **Likes**: 1,400  
  - **Comments**: 72  
  - **Shares**: 122

---

## 📁 Dataset Description

The dataset was exported from YouTube Studio and includes the following columns:

| Column                      | Description                                      |
|----------------------------|--------------------------------------------------|
| `Video title`              | Title of the uploaded video                      |
| `Video publish time`       | Date the video was uploaded                      |
| `Duration`                 | Video length (in seconds)                        |
| `Views`                    | Total views received                             |
| `Watch time`               | Total hours watched                              |
| `Subscribers`              | Net subscribers gained from the video            |
| `Average view duration`    | Avg. minutes watched per view                    |
| `Impressions`              | How many times thumbnails were shown             |
| `CTR (%)`                  | Click-through rate of impressions                |

---

## 📌 Analysis Performed

### ✅ Correlation Analysis
- **Views vs Watch Time** – Do longer watch times lead to more views?
- **Views vs Subscribers** – Do higher views result in more subscribers?
- **Impressions vs CTR** – Do more impressions bring higher engagement?
- **Watch Time vs Avg View Duration** – Are longer videos watched more?

### ✅ Audience Retention
- **Avg View Duration vs Video Length**
- **Retention Rate (%)** = Watch Time / Duration
- **Best Duration Range** for audience retention

### ✅ Title Optimization
- Removed redundant phrases and characters (like `||`)
- Shortened long titles using NLP techniques
- Analyzed title length impact on CTR

### ✅ Temporal Trends
- Analyzed performance by **day of the week**
- Extracted day & weekday from `publish time`
- Bar plots for views by day

---

## 🧪 Tools & Libraries Used

- `Pandas` – data manipulation
- `Matplotlib` & `Seaborn` – data visualization
- `NLTK` – text cleaning for title optimization
- `Jupyter Notebook` – analysis environment

---

## 📷 Sample Visualizations

- 📊 Bar plot: Total Views by Day of Month  
- 📉 Scatterplot: Avg View Duration vs Video Length  
- 📈 Correlation Heatmap  
- 📦 Title Optimization Table  

*(See `/notebooks` folder for full visual outputs)*

---

## 🧠 Key Insights

- Shorter videos (3–6 min) showed higher retention
- Titles under 60 characters performed better
- Watch time and avg duration are better indicators of success than just views
- Timing of publishing had a mild effect; content and engagement matter more

---

## 🚀 Future Scope

- Apply A/B testing on thumbnails and titles  
- Relaunch channel with improved strategies  
- Build predictive models for video performance  
- Integrate YouTube Data API for real-time tracking

---

## 📂 Project Structure

