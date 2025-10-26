# Netflix_AI_Agent
Netflix AI Agent is an intelligent assistant that recommends TV shows and movies based on a user’s mood and previous watch history.
The system uses natural language processing (NLP) and machine learning to understand user preferences and suggest personalized Netflix content.

# ✨ Key Features

🎭 Mood-based recommendations — Suggests shows & movies aligned with user emotions or descriptions.

📚 Watch history learning — Learns user preferences from past viewing patterns.

🤖 AI-powered understanding — Uses NLP to interpret mood keywords and semantic meaning.

⚡ Lightweight and fast — Runs locally with pre-trained models (no API key required).

💬 Interactive interface — Simple command-line or web-based interface for user queries.

# 🧠 System Workflow

          ┌────────────────────┐
          │  User Input (Mood) │
          └──────────┬─────────┘
                     │
           +─────────▼──────────+
           |  NLP Mood Analyzer  |
           +─────────┬──────────+
                     │
          ┌──────────▼──────────┐
          │ Watch History Model │
          └──────────┬──────────┘
                     │
           +─────────▼──────────+
           | Recommendation Core|
           +─────────┬──────────+
                     │
             ┌───────▼────────┐
             │ Recommended List│
             └────────────────┘

# 🧩 Tech Stack

Python 3.10+

pandas, numpy — data processing

scikit-learn — recommendation algorithms

sentence-transformers / spaCy — mood & text embedding

FastAPI / Streamlit (optional) — to create an interactive UI

# 🧩 Core Logic

Mood Understanding

Extracts emotional context using embeddings or sentiment classification.

Maps mood → genre/theme tags (e.g., happy → comedy, sad → drama, thrill → action).

User Profile Modeling

Stores last N watched shows in a local JSON or database.

Creates vector profile based on genres, actors, and descriptions.

Recommendation Engine

Combines mood tags + user vector to compute cosine similarity with Netflix catalog embeddings.

Returns top-k relevant titles.

# 📊 Data Source

Uses Netflix Movies and TV Shows dataset (available on Kaggle):
https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies

# 🧪 Future Improvements

🎯 Improve personalization using reinforcement learning

🗣️ Add voice or chatbot interface

🌐 Integrate live Netflix API (if accessible)

🧬 Context-aware recommendations (time of day, recent moods, device type)

# 👨‍💻 Author

# Dhyey Shah
📧 dhyeys2805@gmail.com
🔗 linkedin.com/in/dhyeys2805

