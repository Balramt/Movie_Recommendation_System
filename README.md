# Movie_Recommendation_System
This project is a Movie Recommendation System implemented in Python. It utilizes data from two CSV files: tmdb_5000_movies.csv and tmdb_5000_credits.csv. The system recommends movies based on user preferences by analyzing movie details such as genres, keywords, cast, and crew.


Features
Data Loading: The system loads movie data from CSV files (tmdb_5000_movies.csv and tmdb_5000_credits.csv).

Data Preprocessing: The project includes data preprocessing steps such as removing unnecessary columns, handling missing values, and transforming data for analysis.

Content-Based Filtering: It uses content-based filtering to recommend movies to users. This involves extracting relevant features from movie descriptions, genres, keywords, cast, and crew.

Cosine Similarity: The system calculates cosine similarity between movies based on their features to determine similarity scores.

Recommendation: Given a movie as input, the system recommends a list of top movies that are similar to the input movie.



How to Use
Clone the repository to your local machine.
Ensure you have Python and required libraries (e.g., pandas, scikit-learn, nltk) installed.
Run the recommend function in the Python script with the name of the movie as an argument to get movie recommendations.
Example Usage:
recommend("Batman Begins")
This will provide a list of movie recommendations based on "Batman Begins."

Credits
The movie data is sourced from tmdb_5000_movies.csv and tmdb_5000_credits.csv.
The project uses Python libraries such as pandas, scikit-learn, and nltk for data processing and analysis.
