# 🎶 Hollywood Music Recommendation System

A **content-based music recommender** system that suggests songs based on lyrical similarity. Powered by **TF-IDF vectorization** and **cosine similarity**, this app analyzes song lyrics to find and recommend tracks with similar themes and content.

Built with **Python** and **Streamlit** for a simple and responsive user interface.

---

## 💡 What It Does

Instead of relying on user behavior or genre tags, this app focuses purely on **lyrics** to suggest songs that share similar textual content. Whether you're looking for poetic vibes, emotional depth, or lyrical storytelling, this app helps you discover music that matches your preferences.

---

## 🧰 Technologies Used

- **Python** – Core programming language
- **Streamlit** – Front-end interface
- **Scikit-learn** – TF-IDF vectorization & cosine similarity
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations

---

## ⚙️ How It Works

1. **Preprocess Lyrics:** Clean and prepare text data from your dataset.
2. **Vectorize:** Convert lyrics into numerical vectors using TF-IDF.
3. **Compute Similarity:** Use cosine similarity to compare songs.
4. **Recommend:** Display the top N songs most similar to the input song.

---

## 🚀 Screenshots
### Screenshot 1:
![Screenshot_181](https://github.com/user-attachments/assets/f0235ea3-7dbe-41ef-9482-fe1b083299a0)
### Screenshot 2:
![Screenshot_180](https://github.com/user-attachments/assets/52aa42fb-1851-475d-82fa-fe9ed37e2ff8)

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/mdshahriarafridi/Hollywood-Music-Recommendation-System.git
cd Hollywood-Music-Recommendation-System
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
streamlit run app.py
```

---

## 🗂️ Project Structure

```
Hollywood-Music-Recommendation-System/
│
├── app.py                # Streamlit front-end
├── recommender.py        # Core recommendation logic
├── data/
│   └── songs.csv         # Lyrics dataset
├── requirements.txt      # Required libraries
└── README.md             # Project documentation
```

## 📌 Features

* Recommend songs based on lyric similarity
* Fast and interactive UI using Streamlit
* No need for user history or genres
* Easy to extend or integrate with external APIs

---

## 🎯 Future Improvements

* Lyrics preprocessing enhancements (e.g., lemmatization, stop word removal)
* Integration with music APIs (e.g., Spotify, Genius)
* Option to upload your own dataset
* Save and share recommendations

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Built with ❤️ by **Md Shahriar Afridi**
🔗 [GitHub Repository](https://github.com/mdshahriarafridi/Hollywood-Music-Recommendation-System)

---

Feel free to fork, contribute, or use this as a base for your own music recommendation experiments! 🎧
