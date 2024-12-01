# Restaurant Recommender App with Sentiment Analysis
A network-based restaurant recommendation system that uses sentiment analysis on user reviews and restaurant preferences of similar users to offer personalized, location-based suggestions.

This tool integrates user-item collaborative filtering with sentiment analysis to provide personalized recommendations based on both historical behaviors and specific individual preferences. By leveraging aspect-based sentiments extracted from user reviews, the model identifies user inclinations toward food quality, service timeliness, and distinct taste profiles. This approach enables the delivery of dining suggestions that are not only relevant but also customized to meet users’ personal dining expectations.

# Installation and Starting  
This restaurant recommendation system app is built using Python and JavaScript.

1. Install [Anaconda](https://www.anaconda.com/download).  
2. Create the environment: `conda create --name app_env python=3.12 -y`. 
3. Install dependencies with `requirements.txt`: 
    - `pip install -r requirements.txt`
3. Launch the app: `python app.py`.  
4. Open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.  
5. Enable location permissions in your browser.  

# User Guide  
The user interface is divided into two main sections: the left panel allows users to rate three restaurants based on three aspects—food, service, and time—using a 1 to 5 scale.

After submitting their preferences, the system generates recommendations for three restaurants based on the user's sentiment and preferences.

# Credit

This is the team project done in my DVA course with collaboration from my teammates: Steve, Cuong and Jonathan. 
