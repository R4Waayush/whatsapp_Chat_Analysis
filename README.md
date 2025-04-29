# 📊 WhatsApp Chat Analyzer

A Streamlit web app that analyzes WhatsApp group chats and provides visual insights including word clouds, user activity, timelines, and emoji usage.

## 🚀 Features
- Overall and user-specific statistics (messages, words, media, and links)
- Monthly and daily timeline charts
- Weekly activity heatmaps
- Most active users analysis
- WordCloud of frequent words
- Emoji usage summary

## Run the app
streamlit run app.py

📁 How to Use

1. Export your WhatsApp chat (without media) as a .txt file.

2. Launch the app and upload the exported file using the sidebar.

3. Choose a specific user or select "Overall" for group-level analysis.

4. Click "Show Analysis" to generate insights.

⚙️ Dependencies
1. streamlit – For the interactive web interface

2. pandas – Data manipulation and cleaning

3. matplotlib & seaborn – Visualization

4. wordcloud – To generate word clouds

5. urlextract – To extract URLs from messages

6. emoji – Emoji parsing and analysis

