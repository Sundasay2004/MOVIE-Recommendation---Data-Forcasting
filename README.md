# 🎬 Movie Recommendation System using Collaborative Filtering (R)

A complete **Movie Recommendation System** built in **R** using **Collaborative Filtering** techniques. This project analyzes movie ratings, explores user behavior, computes movie similarities, and generates personalized movie recommendations using the **Item-Based Collaborative Filtering (IBCF)** algorithm provided by the **recommenderlab** package.

The project also includes comprehensive **Exploratory Data Analysis (EDA)**, visualization, preprocessing, normalization, similarity analysis, and recommendation evaluation.

---

# 📖 Project Overview

Recommendation systems have become an essential part of modern digital platforms such as Netflix, Amazon Prime, Spotify, YouTube, and e-commerce websites. This project demonstrates how collaborative filtering can be used to recommend movies based on users' historical ratings.

The system processes movie and rating datasets, constructs a user-item rating matrix, calculates similarities between users and movies, trains an Item-Based Collaborative Filtering model, and generates personalized movie recommendations.

---

# 🎯 Objectives

* Build a personalized movie recommendation system.
* Analyze user rating behavior.
* Perform Exploratory Data Analysis (EDA).
* Generate movie recommendations using Collaborative Filtering.
* Visualize rating distributions and similarity matrices.
* Learn practical applications of recommendation systems.

---

# ✨ Features

* Import and preprocess movie datasets
* Data cleaning and transformation
* Genre extraction and encoding
* User-item rating matrix construction
* Exploratory Data Analysis (EDA)
* Movie popularity analysis
* User similarity computation
* Movie similarity computation
* Rating normalization
* Binary rating conversion
* Training and testing dataset creation
* Item-Based Collaborative Filtering (IBCF)
* Personalized Top-N Movie Recommendations
* Data visualization using ggplot2

---

# 📂 Dataset

The project uses the MovieLens dataset containing:

### movies.csv

Contains:

* Movie ID
* Movie Title
* Genres

### ratings.csv

Contains:

* User ID
* Movie ID
* User Rating
* Timestamp

---

# 📊 Technologies Used

* R Programming
* recommenderlab
* ggplot2
* data.table
* reshape2

---

# 🧠 Machine Learning Technique

This project uses:

## Item-Based Collaborative Filtering (IBCF)

The recommendation engine predicts movies based on similarities between items (movies) rather than users.

Workflow:

```text
User Ratings
        │
        ▼
User-Item Rating Matrix
        │
        ▼
Movie Similarity Matrix
        │
        ▼
Item-Based Collaborative Filtering
        │
        ▼
Top-N Personalized Recommendations
```

---

# 📈 Exploratory Data Analysis

The project includes:

* Dataset summary
* Rating distribution
* Genre analysis
* Most viewed movies
* Heatmaps
* Average ratings per user
* Rating normalization
* Binary preference analysis

---

# 📊 Visualizations

The system generates several visualizations, including:

* Top Viewed Movies
* User Similarity Heatmap
* Movie Similarity Heatmap
* Rating Distribution
* Average User Rating Distribution
* Normalized Rating Heatmaps

---

# ⚙ Data Processing Pipeline

```text
Movie Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Genre Encoding
        │
        ▼
Rating Matrix Creation
        │
        ▼
EDA & Visualization
        │
        ▼
Similarity Computation
        │
        ▼
Model Training (IBCF)
        │
        ▼
Movie Recommendations
```

---

# 🤖 Recommendation Algorithm

The recommendation model uses:

* Item-Based Collaborative Filtering (IBCF)
* Cosine Similarity
* Top-N Recommendation Strategy
* User Preference Analysis

---

# 📁 Project Structure

```text
Movie-Recommendation-System/

│── movies.csv
│── ratings.csv
│── movie_recommendation.R
│── README.md
```

---

# 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
```

### Open R or RStudio

Install required packages:

```r
install.packages(c(
"recommenderlab",
"ggplot2",
"data.table",
"reshape2"
))
```

Load libraries:

```r
library(recommenderlab)
library(ggplot2)
library(data.table)
library(reshape2)
```

Run:

```r
source("movie_recommendation.R")
```

---

# 📌 Results

The system successfully:

* Builds a user-item rating matrix
* Computes user similarities
* Computes movie similarities
* Trains an Item-Based Collaborative Filtering model
* Generates personalized movie recommendations
* Visualizes user behavior and rating distributions

---

# 🎯 Applications

Recommendation systems are widely used in:

* Netflix
* Amazon Prime
* Disney+
* Spotify
* YouTube
* Amazon
* E-commerce platforms
* Online streaming services

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

* Recommendation Systems
* Collaborative Filtering
* Machine Learning Fundamentals
* Data Preprocessing
* Data Visualization
* Exploratory Data Analysis
* Cosine Similarity
* User Preference Modeling
* Item Similarity Analysis

---

# 🔮 Future Improvements

* User-Based Collaborative Filtering
* Matrix Factorization (SVD)
* Hybrid Recommendation System
* Deep Learning Recommendation Models
* Content-Based Filtering
* Real-Time Recommendation API
* Web Application Integration
* Recommendation Evaluation Metrics (Precision, Recall, RMSE)

---

# 👨‍💻 Author

**Sundas Malik**

Bachelor of Data Science

Interested in Machine Learning, Artificial Intelligence, Recommendation Systems, Data Analytics, and Software Development.

---

# ⭐ If you found this project useful, consider giving it a star!
