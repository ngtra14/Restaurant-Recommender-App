# Restaurant-Recommender-App
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
The user interface consists of two main sections. On the left panel, users input their opinions for three restaurants, rating three aspects—food, service, and time—on a scale of 1 to 5.

After submitting their preferences, the system generates recommendations for three restaurants based on the user's sentiment and preferences.
