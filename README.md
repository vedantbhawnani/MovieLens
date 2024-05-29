# MovieLens Recommendation System

This project explores various recommendation techniques using the MovieLens dataset.

## Dataset

The project utilizes the MovieLens "ml-latest-small" dataset, which contains:

* **ratings.csv:** UserID, MovieID, Rating, Timestamp
* **movies.csv:** MovieID, Title, Genres
* **tags.csv:** UserID, MovieID, Tag, Timestamp
* **links.csv:** MovieID, imdbID, tmdbID

## Techniques Explored

1. **Item-Based Collaborative Filtering:** This technique identifies similar movies based on user ratings and recommends movies similar to those the user has rated highly. 
2. **Genre-Based Recommendations:** This method uses TF-IDF vectorization to analyze movie genres and recommends movies with similar genre profiles to those the user has enjoyed.

## Implementation

The project is implemented using Python libraries such as:

* **pandas:** For data manipulation and analysis
* **numpy:** For numerical computations
* **scipy:** For sparse matrix operations
* **scikit-learn:** For cosine similarity calculations and TF-IDF vectorizer
* **tensorflow:** (Imported but not currently used, potentially for future exploration of deep learning models) 

## Files

* **MovieLens.py:** Contains the Python code for data preprocessing, recommendation algorithms, and example usage. 

## How to Run

1. **Clone the repository:**
   git clone https://github.com/vedantbhawnani/MovieLens-Recommendation-System.git
3. **Install dependencies:**
   pip install pandas numpy scipy scikit-learn tensorflow
5. **Run the script on Google Colab or Jupyter Notebook.**

7. **Experiment with different movie titles and user IDs to get recommendations.**

## Future Improvements

* **Hybrid Recommendation System:** Combine item-based and genre-based approaches for more robust recommendations.
* **Deep Learning Models:** Explore the use of deep learning techniques like autoencoders or recurrent neural networks for more accurate and personalized recommendations. 
* **Evaluation Metrics:** Implement evaluation metrics like precision, recall, and NDCG to assess the performance of different recommendation techniques. 
* **User Interface:** Develop a user interface to allow users to easily interact with the recommendation system. 
