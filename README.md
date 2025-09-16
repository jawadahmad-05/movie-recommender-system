# Movie Recommender System (Popularity-Based)

This project implements a simple movie recommender system using the TMDB 5000 dataset.  
The system identifies trending movies by ranking them based on their popularity scores.

---

## 📂 Project Structure
- `movie_recommender.ipynb` – Implementation code
- `Report.docx` –  report analysis
- `requirements.txt` – Python dependencies

---

## 🗂️ Dataset
This project uses the **[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)** from Kaggle.  

Please download the following files manually and place them inside the `data/` folder:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## ⚙️ Methodology
1. Load dataset using Pandas
2. Sort movies by the **popularity/score** column
3. Select **Top 10 movies** as "Trending Now"

---

## 📊 Results
- Displays the **Top 10 movies** with highest popularity
- Suitable for a "Trending Now" section

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/jawadahmad-05/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it inside the `data/` folder.

4. Open the notebook:
   ```bash
   jupyter notebook notebooks/movie_recommender.ipynb
   ```
