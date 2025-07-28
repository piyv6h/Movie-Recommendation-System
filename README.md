# Movie-Recommendation-System
This project is a movie suggestion engine that reads your taste and delivers spot-on recommendations, knows what you’ll love before you do. Built using Python and machine learning libraries. It takes a user's favorite movie as input and using content-based filtering and fuzzy matching, the system suggests similar movies based on features such as genres, cast, director, and more. Powered by a dataset of 4,800+ movies, it delivers smart, instant suggestions through a clean Google Colab interface.

Features:
> Content-based filtering using textual metadata
> TF-IDF Vectorization for feature extraction
> Cosine Similarity to compute similarity scores
> Interactive console input for personalized recommendations

Tech Stack:
> Python
> Pandas & NumPy
> Scikit-learn (TfidfVectorizer, cosine_similarity)
> Google Colab
> CSV data for movie metadata

Dataset:
The dataset used (Movies_data.csv) includes:
> Title
> Genres
> Keywords
> Original Language
> Tagline
> Cast
> Director

How it works?
1. The system uses the following features:
   genres, keywords, original_language, tagline, cast, director
2. Null values in selected features are replaced with empty strings.
3. All selected features are combined into a single string for each movie.
4. The combined feature strings are converted into numerical vectors using TF-IDF Vectorizer.
5. Cosine similarity is used to compute similarity scores between movies.
6. The user provides a favorite movie name, and the system finds the most similar movies based on the computed similarity matrix.

How to run?
1. Open the notebook in Google Colab.
2. Mount your Google Drive (required to load the dataset).
3. Run all the cells in order.
4. Enter your favorite movie name when prompted.
5. Get a list of recommended movies, enjoy!

Improvements & Future Work




