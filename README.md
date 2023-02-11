# SEN-T-MENT
An analysis of public opinion on well-known individuals through Twitter.

This web application, developed using Python and the Flask framework, allows users to analyze the sentiment of recent tweets related to famous personalities by simply entering keywords related to the personalities they are interested in. The application leverages the capabilities of the popular "Tweepy" API, which establishes a real-time connection with Twitter and collects text and metadata from the platform. The collected data is then processed using sentiment analysis techniques to determine the overall sentiment of the tweets. The results of the sentiment analysis are visually represented through the use of graphs, providing users with a comprehensive and intuitive understanding of the sentiment of the tweets related to the famous personalities they are interested in.

Here's a step-by-step guide on how to use this project:

##Installation: 

To use this project, you'll need to install the required packages such as Flask, Tweepy, TextBlob, and Matplotlib.

You can install them by running the following command in your terminal:

pip install Flask 

pip install tweepy

pip install textblob

pip install matplotlib


##Set up Twitter API: 

You'll need to set up a Twitter API account and generate API keys to be able to retrieve tweets. 
Go to the Twitter developer site and sign up for a developer account. After signing up, create a new project and generate API keys.


##Configure the Tweepy API: 

In the code, replace the placeholder API keys with the ones you generated in the previous step.


##Run the application: 

Once you have installed all the necessary packages and set up the API keys, you can run the application. To run the application, open the terminal and navigate to the project folder. Then, run the following command:

python main.py


##Enter keywords: 

Once the application is running, you can access it through a web browser at http://localhost:5000/. 
Enter the keywords related to the topic or individual you want to analyze, and hit the submit button.


##Retrieve tweets: 

The application will use the Tweepy API to retrieve recent tweets based on the keywords you entered. 
The retrieved tweets will be displayed in a tabular format.

##Analyze sentiment: 

The sentiment of the retrieved tweets will be analyzed using the TextBlob library. 
The sentiment of each tweet will be classified as either positive, negative, or neutral.


##Visualize results: 

The results of the sentiment analysis will be displayed in the form of graphs.
The pie chart will show the distribution of sentiments, while the bar graph will show the number of positive, negative, and neutral tweets.


By following these steps, you can easily analyze the sentiment of recent tweets based on the keywords of your choice and gain insights into public opinion.
