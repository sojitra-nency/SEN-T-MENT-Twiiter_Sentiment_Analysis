# SEN-T-MENT
An analysis of public opinion on well-known individuals through Twitter.

This Sentiment Analysis project aims to provide an easy and efficient way to analyze the sentiments of recent tweets. It is built using Python and the Flask framework and makes use of the Tweepy API to retrieve tweets in real-time. The goal of this project is to enable users to input keywords related to a particular topic or individual, retrieve recent tweets based on the keywords, and analyze the sentiment of these tweets to gain insights into public opinion.

Here's a step-by-step guide on how to use this project:

##Installation: 

To use this project, you'll need to install the required packages such as Flask, Tweepy, TextBlob, and Matplotlib. You can install them by running the following command in your terminal:

pip install Flask Tweepy TextBlob Matplotlib
Set up Twitter API: You'll need to set up a Twitter API account and generate API keys to be able to retrieve tweets. Go to the Twitter developer site and sign up for a developer account. After signing up, create a new project and generate API keys.

Configure the Tweepy API: In the code, replace the placeholder API keys with the ones you generated in the previous step.

Run the application: Once you have installed all the necessary packages and set up the API keys, you can run the application. To run the application, open the terminal and navigate to the project folder. Then, run the following command:

Copy code
python app.py
Enter keywords: Once the application is running, you can access it through a web browser at http://localhost:5000/. Enter the keywords related to the topic or individual you want to analyze, and hit the submit button.

Retrieve tweets: The application will use the Tweepy API to retrieve recent tweets based on the keywords you entered. The retrieved tweets will be displayed in a tabular format.

Analyze sentiment: The sentiment of the retrieved tweets will be analyzed using the TextBlob library. The sentiment of each tweet will be classified as either positive, negative, or neutral.

Visualize results: The results of the sentiment analysis will be displayed in the form of graphs. The pie chart will show the distribution of sentiments, while the bar graph will show the number of positive, negative, and neutral tweets.

By following these steps, you can easily analyze the sentiment of recent tweets based on the keywords of your choice and gain insights into public opinion.
