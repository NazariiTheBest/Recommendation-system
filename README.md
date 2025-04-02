# Recommendation-system

This project is a simple movie recommendation system using Natural Language Processing (NLP) techniques. It takes a movie title as input and returns a list of similar movies based on text-based features.

Project Overview

This project follows these steps:

Importing Libraries – Load necessary Python libraries.

Loading the Dataset – Import movie data into a Pandas DataFrame.

Text Vectorization – Convert movie descriptions into a numerical format using CountVectorizer.

Calculating Cosine Similarity – Compute similarity between movies based on text features.

Getting Movie Recommendations – Retrieve and output movies most similar to the given title.


<b>Steps in the Jupyter Notebook</b>

1. Importing Libraries

The following libraries are used:

![image](https://github.com/user-attachments/assets/e67df7a3-d061-446b-9690-3e13889f2d14)


2. Loading the Dataset

The dataset is loaded into a Pandas DataFrame:

![image](https://github.com/user-attachments/assets/0816821b-5c65-4b47-82cd-2778bf73d796)


Ensure that the dataset contains a column named 'title' and a column with text-based features (e.g., 'description').

3. Text Vectorization

We use CountVectorizer to transform movie descriptions into a numerical format:

![image](https://github.com/user-attachments/assets/9feb93e6-564b-49e4-a83d-e4fff0542593)

This creates a sparse matrix where each row represents a movie, and each column represents a word.

4. Calculating Cosine Similarity

Compute similarity between movies:

![image](https://github.com/user-attachments/assets/7a0ed72c-1cb4-4dc9-9c95-6e608d2a96e0)

This results in a matrix where similarity[i][j] represents how similar movie i is to movie j.

5. Getting Movie Recommendations

Define a function to find similar movies:

![image](https://github.com/user-attachments/assets/bf68f41b-1109-4df4-a263-39500090faee)

Tests:

1. Similar to <b>Skyfall</b>

![image](https://github.com/user-attachments/assets/3e428a12-a466-435e-a5e7-98435ba296c5)


2. Silimar to <b>Mulan</b>

![image](https://github.com/user-attachments/assets/a51ad62d-5c16-45fe-97c5-a68a3cbfe334)


3. Similar to <b>Avatar</b>

![image](https://github.com/user-attachments/assets/9f9fca2c-ccab-4a8b-8178-2f288adc6edf)


4. Similar to <b>Star Wars</b>

![image](https://github.com/user-attachments/assets/60096ca8-a482-4499-8d01-8e9ba6ce341d)


5. Similar to <b>Interstellar</b>

![image](https://github.com/user-attachments/assets/e57d6bd4-812e-434d-b3fb-e3f4f10c4d13)
