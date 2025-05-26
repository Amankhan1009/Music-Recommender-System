# 🎵 Music Recommendation System using Lyrics (Content-Based)

This project is a simple **content-based music recommendation system** that uses the **lyrics** of songs to recommend similar tracks. Built in Python using NLP techniques, it leverages **TF-IDF vectorization** and **cosine similarity** to find songs that are lyrically similar.

---

## 🚀 Features

- Content-based recommendations using lyrics.
- Text preprocessing with `nltk`.
- TF-IDF vectorization for feature extraction.
- Cosine similarity for finding similar songs.
- Modular codebase with separation of concerns.
- Works with a dataset of 57,000+ songs.

---

## 📂 Project Structure

music-recommendation-app-python
│
├── src/
│ ├── main.py # Entry point to run the app
│ ├── preprocess.py # Preprocessing logic and TF-IDF vectorization
│ ├── recommend.py # Recommendation engine
│ └── spotify_millsongdata.csv # Dataset (lyrics + song titles)
│
├── Music_Recommendation_System_using_Python_code_prep_2.ipynb # Jupyter notebook version
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── start_app.txt # Instructions to run the project


---

## 📊 Dataset

- **Source**: [Kaggle: Spotify Million Song Dataset](https://www.kaggle.com/datasets/gyani95/380000-lyrics-from-metrolyrics)
- **Format**: CSV with song titles and lyrics

> Note: The `spotify_millsongdata.csv` file contains cleaned song lyrics and titles.

---

## ⚙️ How It Works

1. **Preprocessing**:
   - Clean text (lowercase, remove stopwords and punctuation)
   - Tokenize and vectorize using TF-IDF

2. **Similarity Calculation**:
   - Compute cosine similarity between lyrics vectors

3. **Recommendation**:
   - For a given song, return the top 10 most similar songs

---

## 🧪 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Amankhan1009/Music-Recommender-System.git
cd Music-Recommender-System

2. Install Dependencies
pip install -r requirements.txt

3. Run the App
python src/main.py
