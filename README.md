# WhatsApp Chat Analyzer with Sentiment Analysis  

🔍 A Python-based tool to analyze WhatsApp chats, providing insights on message statistics, user activity, and sentiment analysis using a pre-trained NLP model.  

## 🚀 Features  

### ✅ Overall Analysis  
- Total Messages, Total Words, Media & Links Shared  
- Monthly & Daily Timeline, Activity Heatmap  
- Most Active Days & Months, Weekly Activity Map  
- Most Busy Users, Word Cloud, Most Common Words  
- Emoji Analysis  

### ✅ Individual User Analysis  
- Analyze a single participant’s chat statistics  

### ✅ Sentiment Analysis  
- Integrated **"ganeshkharad/gk-hinglish-sentiment"** (Hugging Face)  
- Classifies messages as **positive, negative, or neutral**  
- Supports Hinglish (Hindi + English mixed language)  

## 🛠️ Tech Stack  
- **Python**  
- **Streamlit** (for UI)  
- **Pandas** (for data processing)  
- **Matplotlib, Seaborn** (for visualizations)  
- **Hugging Face Transformers** (for sentiment analysis)  

## How It Works
- Upload a WhatsApp chat export file (.txt format).
- View overall analysis (message stats, activity trends, common words, emojis).
- Select a specific user for individual chat insights.
- Sentiment Analysis: Messages are classified as positive, negative, or neutral using a pre-trained model.
