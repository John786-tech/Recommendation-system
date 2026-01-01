# 🎬 Movie Recommendation System

A Content-Based Recommendation System built using Python and Machine Learning. This system suggests movies to users based on the similarity of their plot descriptions.

**Internship Project:** Task-4 at *MyDailyWork*

## 🚀 Overview
This project implements a recommendation engine that uses **Content-Based Filtering**. Instead of relying on user ratings, it analyzes the content (plot summaries) of movies to find similarities.

If a user likes a movie like *The Matrix*, the system analyzes keywords (e.g., "hacker," "war," "reality") and suggests other movies with mathematically similar descriptions.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
    * `pandas` (Data manipulation)
    * `scikit-learn` (Machine Learning: TF-IDF & Cosine Similarity)

## 🧠 How It Works
1.  **Data Ingestion:** Loads a dataset of movies with titles, genres, and descriptions.
2.  **Vectorization (TF-IDF):** Converts text descriptions into numerical vectors. This highlights unique and important words in each plot.
3.  **Similarity Calculation:** Uses **Cosine Similarity** to calculate the angle between movie vectors.
    * *Score close to 1:* Movies are very similar.
    * *Score close to 0:* Movies are unrelated.
4.  **Recommendation:** Sorts movies by their similarity score and returns the top matches.

## 💻 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/John786-tech/movie-recommendation-system.git](https://github.com/John786-tech/movie-recommendation-system.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas scikit-learn
    ```
3.  **Run the script:**
    You can run the script in a Jupyter Notebook or as a standard Python file.
    ```bash
    python recommendation_system.py
    ```

## 📊 Example Output

**Input:**
> "The Matrix"

**Recommendations:**
1.  *Star Wars* (Score: 0.82)
2.  *Interstellar* (Score: 0.75)
3.  *Blade Runner* (Score: 0.68)

## 👨‍💻 Author
**Jahaan Gauri**
* **LinkedIn:** [Jahaan Gauri](https://www.linkedin.com/in/jahaan-gauri-705182349/)
* **GitHub:** [John786-tech](https://github.com/John786-tech)

---
*Created for the MyDailyWork Internship Program.*
