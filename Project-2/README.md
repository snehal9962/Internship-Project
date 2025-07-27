# 🎬 Movie Recommender System

This project is a **Content-Based Movie Recommendation System** developed using **Python**, **Streamlit**, and the **TMDb API**. It was built as the **second project** during my **Data Science internship** at **Infotact Solutions**.

The application suggests similar movies based on a user's selection and displays dynamic movie posters fetched in real-time.

---

## 🔍 Features

- ✅ Movie recommendations using **content-based filtering**
- 🎞️ Poster images fetched via **TMDb API**
- ⚡ Fast recommendations using **pre-computed similarity matrix**
- 🖥️ **Interactive Streamlit** frontend with clean UI

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **Streamlit**
- **Pickle** (for model serialization)
- **Requests** (API integration)
- **TMDb API** (for movie posters)

---

## 📁 Project Structure

├── app.py # Main Streamlit application
├── movie_dict.pkl # Dictionary of movie data
├── similarity.pkl # Similarity matrix for recommendations
├── README.md # Project documentation


---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/snehal9962/movie-recommender-system.git
   cd movie-recommender-

## Install dependencies
  pip install -r requirements.txt

## Run the app
  streamlit run app.py

## 🔑 TMDb API Key

This project uses The Movie Database (TMDb) API to fetch movie posters.
To run this project, you’ll need a TMDb API key:
1. Sign up at https://www.themoviedb.org/
2. Go to your account settings → API → Request an API Key
3. Replace the placeholder key in app.py:

    https://api.themoviedb.org/3/movie/{}?api_key=YOUR_API_KEY
