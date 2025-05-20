
# 🎬 NextWatch AI – Personalized Movie Recommendation System

NextWatch AI is a machine learning-powered movie recommendation system that intelligently suggests movies based on user preferences. It combines the power of **content-based filtering** and **cosine similarity** to help users discover films they'll love — quickly and accurately.

---

## 🚀 Features

- Personalized movie recommendations based on content similarity
- Uses NLP to analyze genres, keywords, overviews, and cast
- Built with **Streamlit** for an interactive web interface
- Fast similarity calculations with **cosine similarity**
- Clean, intuitive, and lightweight design

---

## 🧠 Recommendation Approach

This system uses **content-based filtering**. It analyzes movie metadata (like genres, cast, and keywords) to find similarities between movies. Recommendations are made using **cosine similarity** between these metadata vectors.

> Cosine similarity measures the cosine of the angle between two vectors — a value closer to 1 means higher similarity.

---

## 📦 Dataset Used

- [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- Cosine Similarity (Sklearn)
- Jupyter Notebook

---

## 📂 Project Structure

```

NextWatch-AI/
├── app.py                       # Streamlit web app
├── Movie Recommender System Data Analysis.ipynb  # Model development
├── model.pkl                   # Serialized similarity matrix
├── movies.pkl                  # Movie metadata
├── demo/                       # Demo screenshots
├── requirements.txt            # Python dependencies
└── README.md

````

---

## ⚙️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/prekshadhongade/NextWatch-AI.git
cd NextWatch-AI
````

### 2. Create & Activate Environment

```bash
conda create -n nextwatch python=3.7.10 -y
conda activate nextwatch
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Generate the Model

Run the notebook to generate `model.pkl`:

```bash
jupyter notebook "Movie Recommender System Data Analysis.ipynb"
```

### 5. Start the App

```bash
streamlit run app.py
```

---

## 📬 Contact

Feel free to connect or collaborate!
Made with ❤️ by [Preksha Dhongade](https://github.com/prekshadhongade)


