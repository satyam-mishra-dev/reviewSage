# 🎯 **YouTube Comment Sentiment Analyzer**

This project analyzes the **sentiment** of YouTube comments using Python and provides a visual breakdown of **positive**, **neutral**, and **negative** sentiments. It's a beginner-friendly NLP project designed to run smoothly in a **Jupyter Notebook** environment.

---

## 🧩 **Features**

- 🔍 Sentiment analysis using **TextBlob**
- 📊 Visualize sentiment distribution with **matplotlib**
- 📂 Jupyter-friendly and lightweight
- 🧪 Accepts both manual input and CSV comment datasets
- 💡 Clean foundation for future web integration

---

## 📁 **Folder Structure**

youtube-sentiment-analyzer/
├── sentiment_analysis.ipynb # Main Jupyter notebook
├── sample_comments.csv # (Optional) Your YouTube comment dataset
└── README.md # You're here!

yaml
Copy

## 🛠️ **Installation**

Install the required dependencies:

```bash
pip install pandas textblob matplotlib
Also download the required nltk corpus for TextBlob:
```
python
import nltk
nltk.download('punkt')

🚀 How to Use
Clone this repo or download the notebook.

Open sentiment_analysis.ipynb in Jupyter.

Load your comment dataset (CSV with comment column) or use the defaults.

Run the cells and analyze the output.

📊 Example Output
Comment	Sentiment
I absolutely loved this video!	Positive
It was okay, not the best.	Neutral
Worst content ever.	Negative


🚧 Future Improvements
🔌 Add Streamlit/Gradio UI

📥 Integrate YouTube Data API for live comments

📈 Use VADER, transformers, or custom models for improved accuracy

🙌 Credits
TextBlob

Matplotlib

Basic sentiment logic inspired by community NLP projects

📝 License
This project is licensed under the MIT License.
