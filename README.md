#### Music Recommendation System

In this project, we developed a music recommendation system that leverages sentiment analysis. Here's an overview of the process:

1. **Data Collection and Preprocessing**: We began by collecting a Twitter dataset. To prepare this data for analysis, we filtered out unnecessary characters such as exclamation marks, emojis, and other irrelevant words. We also identified and removed stopwords and non-informative action words.

2. **Sentiment Mapping**: Using the cleaned dataset, we mapped sentiments using the TextBlob library. This tool helped classify the tweets based on the emotions they conveyed.

3. **Data Visualization**: To visualize the data, we used a word cloud to represent words associated with specific emotions. This provided a clear and immediate view of the words most frequently tied to particular moods.

4. **Training the Neural Network**: After visualizing the data, we trained an artificial neural network (ANN) with 10 epochs (iterations). This ANN model learned to detect the mood of any input text based on the training data.

5. **Mood-Based Song Recommendation**: Once the neural network could accurately identify mood from text, we utilized a separate dataset containing song names and associated moods. Using the Flask framework, we integrated this functionality to recommend songs that match the detected mood. Additionally, we provided links to the songs on YouTube and Spotify for easy access.

This combination of sentiment analysis and neural networks allowed us to create a personalized music recommendation system that aligns users' emotions with corresponding songs.
