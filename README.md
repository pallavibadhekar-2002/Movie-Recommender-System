# 🎬 Movie Recommendation System

## Overview

The Movie Recommendation System is a machine learning application that recommends movies similar to the one selected by the user. It uses a content-based filtering approach by analyzing movie metadata such as genres, keywords, cast, crew, and overview. The application is built with Streamlit and integrates with the TMDB API to display movie posters, providing an interactive and user-friendly experience.

---

## Features

* Recommend the top 5 similar movies.
* Interactive web interface built using Streamlit.
* Displays movie posters using the TMDB API.
* Fast recommendation generation using cosine similarity.
* Clean and responsive user interface.
* Easy movie selection through a dropdown menu.

---

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle
* Requests
* TMDB API

---

## Machine Learning Techniques

* Data Preprocessing
* Feature Engineering
* Text Vectorization
* CountVectorizer
* Cosine Similarity
* Content-Based Filtering

---

## Dataset

* TMDB 5000 Movies Dataset
* TMDB 5000 Credits Dataset

The datasets were cleaned, merged, and processed to generate feature vectors used for movie recommendations.

---

## Project Workflow

1. Load movie and credits datasets.
2. Clean and preprocess the data.
3. Merge the datasets.
4. Extract important features such as genres, keywords, cast, crew, and overview.
5. Create a combined tags column.
6. Convert text into numerical vectors using CountVectorizer.
7. Calculate cosine similarity between movies.
8. Save the processed data and similarity matrix using Pickle.
9. Build the Streamlit application.
10. Fetch movie posters dynamically using the TMDB API.

---

## Project Structure

```
Movie-Recommendation-System/
│
├── app.py
├── requirements.txt
├── README.md
├── model/
│   ├── movie_list.pkl
│   └── similarity.pkl
├── data/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
```

Move to the project directory:

```bash
cd Movie-Recommendation-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Screenshots

Add screenshots of the application in the `screenshots` folder and display them here.

---

## Future Enhancements

* Hybrid recommendation system.
* Collaborative filtering.
* User authentication.
* Movie search with autocomplete.
* Ratings and reviews integration.
* Personalized recommendations based on user preferences.
* Cloud deployment using Streamlit Community Cloud or Render.

---

## Learning Outcomes

* Built an end-to-end machine learning application.
* Applied feature engineering and text vectorization techniques.
* Implemented cosine similarity for recommendations.
* Integrated REST APIs for dynamic content.
* Developed and deployed an interactive Streamlit application.
* Gained practical experience with Git and GitHub for version control.

---

## Author

**Pallavi Badhekar**

M.Sc. Industrial Mathematics with Computer Applications | PG-Diploma in Big Data Analytics (CDAC)

Skills: Python, SQL, Machine Learning, Streamlit, Pandas, NumPy, Scikit-learn, Power BI, Tableau
