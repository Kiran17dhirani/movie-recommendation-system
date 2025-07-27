# Movie Recommendation System
 A machine-learning based movie recommendation system that suggests  relevant movies to the users based on their previous interactions. This project processes interactions to recommend similar content based on keyword or user input.

🚀 Features 

🔍 Keyword-based movie recommendations
📈 Analyzes  metadata (title, tags, description)
🧠 Uses TF-IDF + Cosine Similarity for content-based filtering
📊 Cleaned and preprocessed real-world data
💡 Simple and interactive UI 

📁 Project Structure
📦 movie-recommendation-system/
 ┣ 📜 app.py                # Streamlit app main file
 ┣ 📜 recommender.py        # Logic for recommendations
 ┣ 📜 utils.py              # Helper functions
 ┣ 📜 movies.csv            # Cleaned dataset
 ┣ 📜 requirements.txt      # Python dependencies
 ┗ 📜 README.md             # Project documentation

 💡 How It Works

1. Data Collection: Uses the movies dataset (title, tags, etc.)
2. Text Vectorization: Apply TF-IDF to convert text to vectors.
3. Similarity Score: Use Cosine Similarity to find similar movies.
4. User Input: User types a movie keyword or title.
5. Output: Top 5 similar movies are displayed.
