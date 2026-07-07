# 🎬 Movie Recommendation System Using Machine Learning

## 📌 Project Overview

This project focuses on building a **Movie Recommendation System** that suggests movies to users based on their interests and preferences.

The system analyzes movie information and user behavior to recommend similar or relevant movies. Recommendation systems are widely used in platforms like streaming services to improve user experience.

---

## 🎯 Objectives

* Build a system that recommends movies based on user preferences.
* Analyze movie data and find similarities between movies.
* Apply machine learning techniques for recommendation.
* Improve user experience by providing personalized suggestions.

---

## 📂 Dataset Description

The dataset contains information about movies, including details required for generating recommendations.

### Important Features:

* **Movie ID** – Unique identifier for each movie.
* **Title** – Name of the movie.
* **Genres** – Categories associated with the movie.
* **Ratings** – User ratings for movies.
* **Overview/Description** – Movie storyline information.
* **Keywords** – Important terms related to the movie.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Natural Language Processing (NLP)
* Google Colab

---

## 🔍 Exploratory Data Analysis (EDA)

EDA is performed to understand the movie dataset.

### Analysis Includes:

* Checking dataset information.
* Handling missing values.
* Analyzing movie genres.
* Studying rating distributions.
* Understanding movie popularity patterns.

### Visualization Techniques:

* Bar charts
* Histograms
* Count plots
* Distribution plots

---

## 🧹 Data Preprocessing

The preprocessing steps include:

* Removing unnecessary columns.
* Handling missing values.
* Combining important movie features.
* Text cleaning.
* Feature transformation.

---

## 🤖 Recommendation Approach

The recommendation system uses similarity-based techniques.

### Content-Based Filtering:

* Uses movie features such as genres, keywords, and descriptions.
* Calculates similarity between movies.
* Recommends movies similar to the user's selected movie.

### Techniques Used:

* Text Vectorization
* TF-IDF Vectorizer
* Cosine Similarity

---

## ⚙️ Working Process

1. Load movie dataset.
2. Clean and preprocess movie information.
3. Convert text features into numerical vectors.
4. Calculate similarity between movies.
5. Generate movie recommendations.
6. Display recommended movies.

---

## 📊 Model Evaluation

The recommendation system can be evaluated using:

* Recommendation accuracy
* Similarity score
* User feedback
* Precision and Recall (for recommendation tasks)

---

## 📈 Results

The system successfully recommends movies based on similarity between movie features.

Example:

**Input:** Selected movie
**Output:** List of similar recommended movies

---

## 🚀 How to Run the Project

### Install Required Libraries

```bash id="5r9m1n"
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Steps:

1. Open the notebook in Google Colab/Jupyter Notebook.
2. Upload the movie dataset.
3. Run all cells sequentially.
4. Enter a movie name.
5. Get recommended movies.

---

## 📁 Project Structure

```text id="xq7k4z"
Movie-Recommendation-System/
│
├── Dataset/
│   └── movies.csv
│
├── Notebook/
│   └── Movie_Recommendation.ipynb
│
├── README.md
│
└── Requirements.txt
```

---

## 🔮 Future Improvements

* Add collaborative filtering.
* Use deep learning-based recommendation models.
* Include user-based personalization.
* Deploy as a web application.
* Add real-time movie recommendations.

---

## 👨‍💻 Author

Anuska Biswas

---

## ⭐ Conclusion

This project demonstrates how machine learning and natural language processing techniques can be used to build a movie recommendation system. By analyzing movie features and similarities, the system provides personalized movie suggestions and improves user experience.
