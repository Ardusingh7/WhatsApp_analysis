# WhatsApp Chat Analysis

A Streamlit-based application to analyze WhatsApp chat exports using statistics, visualizations, and NLP techniques. It helps you gain insights from your chat history with ease and interactivity.

---

## 🚀 Features

* **Chat Import** – Upload your exported WhatsApp `.txt` file for analysis
* **Statistical Overview** – Get insights like total messages, most active users, and chat activity trends
* **Visualizations** – Generate plots for message frequency, word clouds, and user activity
* **NLP Insights** – Perform basic natural language processing for sentiment, frequent words, and more
* **Interactive Interface** – Explore results dynamically in Streamlit

---

## 🛠️ Tech Stack

* **Framework**: Streamlit for building the app interface
* **Language**: Python
* **Libraries**: Pandas, NumPy (data processing), Matplotlib/Seaborn (visuals), NLTK or SpaCy (NLP)

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/Ardusingh7/WhatsApp_analysis.git
   cd WhatsApp_analysis
   ```

2. **Set up a virtual environment** (recommended)

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   > If `requirements.txt` is missing, make sure to install:
   > `streamlit`, `pandas`, `numpy`, `matplotlib`, `seaborn`, and your NLP tools (e.g., `nltk` or `spacy`).

4. **Run the app**

   ```bash
   streamlit run app.py
   ```

   (Replace `app.py` with the appropriate script name if different.)

---

## 🔮 Future Enhancements

* Add **sentiment analysis** using pretrained models (e.g., VADER, TextBlob)
* Enable **media file handling and analysis** (images, voice messages)
* Offer **downloadable reports** (PDF, CSV) for analysis outputs
* Add exploration of **emoji usage** and trending themes/topics
* Deploy via **Heroku**, **Streamlit Cloud**, or a Docker container for easy sharing

---

## 🤝 Contribution Guidelines

We welcome contributions! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add insightful feature"`)
4. Push to your fork (`git push origin feature/your-feature`)
5. Open a Pull Request for review

Please keep code style and documentation consistent; new features should include usage details or examples.

---
