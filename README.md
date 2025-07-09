# 📊 WhatsApp Chat Analyzer

**WhatsApp_analysis** is a Python-based tool that provides detailed statistical and visual analysis of WhatsApp group or personal chat exports. With just a `.txt` chat file, you can uncover message counts, active hours, emoji usage, media sharing, and much more — beautifully visualized and interactive.

---

## 🚀 Features

- 📅 Daily and monthly message timelines
- 👤 Most active users in group chats
- 📈 Word count and frequency stats
- 😂 Emoji usage breakdown and charts
- 📷 Media, links, and deleted message stats
- 🌐 Streamlit-powered interactive dashboard

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (pandas, matplotlib, seaborn, emoji, urlextract)
- **Visualization**: Matplotlib, Seaborn, WordCloud

---

2. Install Dependencies
Make sure you have Python 3 installed. Then run:

bash
Copy
Edit
pip install -r requirements.txt
3. Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
4. Upload Your Chat File
Open WhatsApp

Go to the group or personal chat

Click Export Chat (without media)

Select the .txt file and upload it to the app interface

📊 Output Examples
Top senders and message counts

Time-based activity heatmaps

Most used words (with word cloud)

Most used emojis

Shared media and links count

✨ Future Improvements
🌍 Multi-language support

📱 Mobile-optimized dashboard

📌 Save & export reports

📤 Cloud-hosted version (e.g., Streamlit Cloud or Hugging Face)
