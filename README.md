# 💬Chat Analysis Dashboard

## 🔍 Project Overview
An interactive dashboard built with **Python** and **Streamlit** to analyze personal and group WhatsApp chat exports. The tool provides insights into user activity, message patterns, and chat behavior.

## 📁 Features
- Upload `.txt` WhatsApp chat exports directly into the app
- Analyze chat data for:
  - 📊 Top statistics (messages, words, media, links)
  - 📆 Monthly & daily timelines
  - 📅 Most active days and months
  - 🔥 Weekly heatmap of message activity
  - 👤 Busiest users in group chats
  - ☁️ Word cloud of common words
  - 🗣 Most frequent words
  - 😄 Emoji usage stats and pie chart

## 🛠️ Tech Stack
- Python  
- Streamlit (UI)  
- Pandas (data manipulation)  
- Matplotlib & Seaborn (visualization)  
- Regex (for text cleaning)  

## 📂 File Structure
- `app.py` – Main Streamlit app  
- `preprocessor.py` – Cleans and structures raw WhatsApp data  
- `helper.py` – Contains logic for analysis and visual generation  

## 🚀 How to Run
1. Clone the repo  
2. Install dependencies  
3. Run the app with:
   ```bash
   streamlit run app.py
