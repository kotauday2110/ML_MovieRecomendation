# 🎬 Movie Recommendation System

> An intelligent recommendation system that suggests movies similar to your favorite ones using text-based similarity and machine learning techniques.

---

##  Description

This project builds a simple but effective **Movie Recommendation System** using **cosine similarity** on text features. It takes your favorite movie as input and recommends the top 30 similar movies based on content analysis. It's perfect for beginners learning recommendation systems and text similarity in machine learning.

---

## Features

- 📥 Takes user input via the terminal (movie name)
- 🔍 Uses `difflib.get_close_matches` for fuzzy matching
- 🧠 Calculates similarity using a cosine similarity matrix
- 📊 Outputs a sorted list of the top 30 similar movies
- 🛠️ Built with basic machine learning tools (no deep learning required!)

---

## 🛠️ Technologies Used

- 🐍 Python
- 📊 pandas
- 🤖 scikit-learn
- 🔍 difflib

---

## 📁 Project Structure


---

## ⚙️ How It Works

1. Loads a movie dataset containing titles and features.
2. Converts your input movie name to the closest match in the dataset.
3. Uses cosine similarity to find how similar other movies are to your selected one.
4. Sorts and prints the top 30 most similar movie titles.

---

## 🧪 Example Output

> User Input: `avatar`
>
> Movies suggested for you:

Avatar

Alien

Guardians of the Galaxy

Moonraker

Space Dogs

Alien 3



