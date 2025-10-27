# Book-Recommendation-System - Analyzing Big Data
Big Data Analysis project that builds a personalized book recommendation engine using Python and collaborative filtering.


## Project Overview:
This project builds a **personalized book recommendation system** using collaborative filtering and big data processing techniques.  
It was developed as part of the IFT 511 course to analyze user preferences and recommend books based on reading patterns and ratings.


## Step I – Data Cleaning & Preparation
- Imported raw `Ratings.csv` file and mapped unique `User-ID` and `ISBN`.  
- Generated LIBSVM-formatted data for machine learning processing.  
- Ensured clean user-book mapping and consistent rating values.  
- Output file: `user_booklibsvmnew.libsvm`


## Step II – Recommendation Algorithm
- Implemented a **collaborative filtering** algorithm in Python.  
- Calculated **cosine similarity** between users based on their reading histories.  
- Identified top 10 nearest neighbors for each user.  
- Generated top 5 book recommendations with weighted scores (1–10).  
- Produced output in CSV format: `library_suggestions.csv`


## Core Concepts
- Data preprocessing with Pandas  
- Similarity calculation using cosine distance  
- Dictionary-based data structures for efficiency  
- File I/O with LIBSVM and CSV formats  
- Collaborative filtering recommender pipeline  


## Example Output
| User_ID | Book_ID | Book_Title | Recommendation_Score |
|:--------:|:--------:|:-----------|:--------------------:|
| 1 | 547 | “The Da Vinci Code” | 9.7 |
| 1 | 601 | “Angels and Demons” | 8.9 |


## Technologies Used
- Python 3  
- Pandas, Math, Collections (defaultdict)  
- LIBSVM format  
- CSV file generation for results  


## 🧩 Files in Repository
