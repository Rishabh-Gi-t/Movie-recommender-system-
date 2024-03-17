--Movie Recommender System

This is a simple movie recommender system built using Streamlit, a Python library for creating web applications. The system suggests movies based on similarity scores calculated using collaborative filtering techniques.

-Usage

1. Clone the repository to your local machine:

```bash
git clone <repository_url>
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Ensure you have Python installed on your machine.

4. Run the Streamlit app:

```bash
streamlit run app.py
```

5. Once the Streamlit app is running, you will see a dropdown menu where you can select a movie from the available options.

6. Click on the "Recommend" button to get the recommendations based on the selected movie.

## Files

- `app.py`: This is the main Python script containing the Streamlit application code.
- `movie_dict.pkl`: This pickle file contains a dictionary with movie details.
- `similarity.pkl`: This pickle file contains similarity scores between movies.

## Functionality

- The `recommend` function takes a movie name, a DataFrame of movie details, and a similarity matrix as input and returns a list of recommended movies based on similarity scores.
- The Streamlit app displays a dropdown menu where the user can select a movie.
- When the user clicks on the "Recommend" button, the app recommends similar movies based on the selected movie.
- The recommended movies are displayed on the app interface.

## Libraries Used

- `streamlit`: For creating the web application interface.
- `pickle`: For reading pickle files containing movie data and similarity scores.
- `pandas`: For data manipulation and analysis.

## Acknowledgments

- This project utilizes collaborative filtering techniques for recommending movies.
- Movie data and similarity scores are precomputed and stored in pickle files.
- The project structure and code are kept simple for demonstration purposes.

Feel free to customize and extend the functionality of this recommender system according to your requirements!
