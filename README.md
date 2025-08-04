
# Movie Recommendation System 🎬

This project is a content-based movie recommender system built using Python and machine learning libraries like **scikit-learn** and **pandas**. It suggests movies similar to a user’s favorite based on description similarities using TF-IDF and cosine similarity.

## 📂 Dataset

- The dataset is read from a CSV file named `movies.csv`.
- It contains details about movies such as **title**, **genre**, **overview**, etc.

## 🔧 Technologies & Libraries Used

- Python 🐍
- NumPy
- Pandas
- scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- difflib (for close match detection)

## 🚀 How It Works

1. **Text vectorization** using TF-IDF on movie descriptions.
2. **Cosine similarity** is used to find how similar each movie is to others.
3. Takes input of a movie name from the user.
4. Returns a list of similar movies based on content.

## 📦 Setup Instructions

1. Clone the repository or download the notebook.
2. Make sure you have the required libraries installed:
    ```bash
    pip install numpy pandas scikit-learn
    ```
3. Place `movies.csv` in the same directory as the notebook.
4. Run the notebook to explore and test the recommendation system.

## 🖥️ Sample Usage

```python
# Example
Enter your favourite movie: Inception

Top 10 movies similar to Inception:
1. Interstellar
2. The Prestige
3. Memento
...
