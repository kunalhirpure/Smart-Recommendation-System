Sentiment-Based Movie Recommendation System

Overview

This project is a Sentiment-Based Movie Recommendation System that suggests movies based on the user's mood. Using TextBlob, the system performs sentiment analysis on movie descriptions (overview) to classify them as Positive, Neutral, or Negative. Based on the user's inputted mood, the system recommends movies that align with their emotions.

Features

🎭 Sentiment Analysis on Movie Descriptions using TextBlob.

🎯 Personalized Movie Recommendations based on user mood.

🎲 Random Movie Suggestion for a fun, surprise element.

🌟 Top Movies Sorted by Sentiment Score to find the most uplifting films.

Dataset

The dataset used should contain at least the following columns:

title: The movie name

overview: A brief description of the movie

The sentiment score is calculated based on the overview column.

Installation & Setup

To run this project, follow these steps:

1. Install Dependencies

Ensure you have Python installed, then install the required libraries:

2. Clone the Repository

3. Run the Jupyter Notebook

You can open and run the Jupyter Notebook (Sentiment_Based_Movie_Recommendation.ipynb) using:

How It Works

Load the dataset: The program reads a CSV file containing movie data.

Perform sentiment analysis: Using TextBlob, each movie's description is analyzed, and a sentiment score is assigned.

Categorize movies: Based on sentiment polarity, movies are categorized as Positive, Neutral, or Negative.

Get recommendations: The user inputs their mood, and the system suggests movies accordingly.

Explore additional features: Users can also get a random movie suggestion or see the top-rated movies based on sentiment scores.

Usage Example

Run the script, and enter your mood when prompted:

Future Enhancements

🎬 Integrate with movie rating APIs to refine recommendations.

📈 Enhance sentiment analysis with NLP models like VADER or BERT.

🏷️ Include genre-based filtering for more tailored results.

Contributing

Contributions are welcome! Feel free to fork this repo, improve it, and submit a pull request.

License

This project is licensed under the MIT License.
