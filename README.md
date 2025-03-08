# Movie Recommendation System

## Overview
This is a **Movie Recommendation System** built using **Machine Learning**. It suggests movies based on content similarity, utilizing **TF-IDF Vectorization** and **Cosine Similarity**.

## Features
- Takes a movie name as input from the user.
- Finds the closest matching movie title in the dataset.
- Computes similarity scores using **TF-IDF** and **Cosine Similarity**.
- Recommends the **top 30 most similar movies** based on content features.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Difflib

## Dataset
The system uses a **CSV file (movies.csv)** that contains information about movies, including:
- **Genres**
- **Keywords**
- **Tagline**
- **Cast**
- **Director**

## How It Works
1. **Preprocessing:**
   - Fill missing values in selected features.
   - Combine features into a single text string.
   - Convert text data into numerical vectors using **TF-IDF Vectorizer**.

2. **Finding Similar Movies:**
   - Compute **cosine similarity** between movies.
   - Sort movies based on similarity scores.

3. **User Input and Recommendation:**
   - The user enters a favorite movie name.
   - The system finds the closest match in the dataset.
   - It retrieves and displays the **top 30 most similar movies**.

4. Enter a movie name when prompted.
5. Get a list of recommended movies!

## Example Output
```
Enter your favourite movie name: Inception
Movies suggested for you:
1. Interstellar
2. The Matrix
3. Shutter Island
4. The Prestige
...
```

## Future Improvements
- Improve recommendations using **Deep Learning (Neural Networks)**.
- Add **Collaborative Filtering** for personalized recommendations.
- Integrate with a **Web App (Flask/Django)**.

