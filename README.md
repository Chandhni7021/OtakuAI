🎌 OtakuAI: Anime Recommendation System
"Your personalized anime concierge powered by LLaMA3 + LangChain"

📌 Overview
OtakuAI is an interactive AI-powered anime recommendation system that suggests anime titles tailored to your interests. Just type in your mood, favorite genres, or keywords like "romantic comedy" or "dark fantasy", and OtakuAI delivers three spot-on recommendations — complete with summaries and reasons you'll love them!


Built using:

🧠 Groq's LLaMA3 model for natural language generation

🔎 LangChain with ChromaDB for semantic search over anime synopses

🎨 Gradio UI for an easy-to-use web interface

📊 A clean dataset from anime_with_synopsis.csv


✨ Features
🔍 Semantic understanding of your query using LLMs

🎥 Anime recommendations with title, summary, and reasoning

⚙️ On-the-fly vector search using sentence-transformer embeddings

🖥️ Web-based UI — no CLI required

🧠 LLaMA-3 (via Groq) for quality generation

💬 Real-time querying with LangChain RetrievalQA


🧰 Tech Stack
Python 3.x

Gradio for UI

LangChain

HuggingFace Sentence Transformers

ChromaDB as Vector Store

Groq API with llama3-8b-8192 model

![Screenshot 2025-06-22 093246](https://github.com/user-attachments/assets/a0297366-8447-4399-9864-7d27735dd664)
![Screenshot 2025-06-22 093213](https://github.com/user-attachments/assets/392bdfde-0525-46b9-9627-6ce15e9c200f)


🚀 Getting Started

1. Clone the repo
bash
Copy
Edit
git clone https://github.com/yourusername/otakuai-anime-recommender.git  
cd otakuai-anime-recommender

2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt

3. Prepare the dataset
Place your cleaned CSV named anime_with_synopsis.csv in the root folder. The file must contain:

Name (Anime title)

sypnopsis (Plot summary)

Genres

✅ Note: The app automatically cleans and converts this to anime_updated.csv.

4. Add your Groq API key
Replace the placeholder api_key="gsk_..." in the script with your actual Groq API key.

5. Run the app
bash
Copy
Edit
python app.py
The app will open in your browser with a simple interface to get recommendations!


💡 Use Cases
Discover new anime based on genres, themes, or vibes

Use as a fun chatbot for anime enthusiasts

Integrate into larger entertainment recommendation platforms


📂 Dataset Info
Dataset source: anime_with_synopsis.csv

Total rows: ~14,000+ anime titles

Format: Name, sypnopsis, Genres


🔮 Future Ideas
Collaborative filtering + LLM hybrid

User profile-based recommendations

Streamlit dashboard with filters

Image-based anime search


📄 License
MIT License © 2025 Chandini Tharayil Sunil
