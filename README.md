# 🎬 Movie Recommendation System

A **content-based Movie Recommendation System** built using **Python**, **Scikit-learn**, and **Streamlit**. The application recommends movies similar to a selected movie by computing cosine similarity on movie metadata and displays movie posters using **The Movie Database (TMDB) API**.

---

## 🚀 Project Overview

This project demonstrates the implementation of a basic recommendation engine using machine learning concepts such as text preprocessing, feature engineering, vectorization, and similarity computation. It also showcases how to deploy a machine learning model through an interactive web application using Streamlit.

---

## ✨ Features

* Recommend movies similar to the selected movie.
* Display movie posters using the TMDB API.
* Interactive web interface built with Streamlit.
* Fast recommendations using a precomputed similarity matrix.
* Handles missing posters with a placeholder image.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Requests
* Pickle

---

## 📂 Dataset

The project uses the TMDB Movie Metadata dataset, which contains information such as:

* Movie Title
* Genres
* Keywords
* Cast
* Crew
* Movie Overview

These features are combined to generate recommendations based on movie content.

---

## ⚙️ How It Works

1. Load and preprocess the movie dataset.
2. Combine important textual features into a single feature.
3. Convert text into numerical vectors using **CountVectorizer**.
4. Compute cosine similarity between movies.
5. Store the processed movie data and similarity matrix using Pickle.
6. Build a Streamlit interface for user interaction.
7. Fetch movie posters dynamically using the TMDB API.

---

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── app.py
├── README.md
├── notebooks/
└── .gitignore
```

---

## ▶️ Run the Project Locally

Clone the repository:

```bash
git clone https://github.com/Prakhar528/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

Create and activate a virtual environment:

```bash
python -m venv movie_env

# Windows
movie_env\Scripts\activate
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn streamlit requests
```

### Generate the Required Files

Before running the application, execute the notebook in the `notebooks/` directory to preprocess the dataset and generate the required serialized (`.pkl`) files.

> **Note:** The generated `.pkl` files are not included in this repository.

### Launch the Application

```bash
streamlit run app.py
```

---

## 📚 Concepts Demonstrated

* Content-Based Recommendation Systems
* Feature Engineering
* Natural Language Processing (Basic)
* CountVectorizer
* Cosine Similarity
* API Integration
* Model Serialization using Pickle
* Streamlit Deployment

---

## 🔮 Future Improvements

* Display IMDb ratings.
* Show movie overview and release year.
* Display genres and cast information.
* Add trailer links.
* Improve the UI design.
* Explore collaborative and hybrid recommendation techniques.

---

## 👨‍💻 Author

**Prakhar Naudiyal**

Aspiring Data Analyst | Data Science & Machine Learning Enthusiast

If you have any suggestions or feedback, feel free to connect or raise an issue in this repository.
