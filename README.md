# YouTube_Text_Data_Analysis

Interact with Jupyter Notebook:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/trisha751/YouTube_Text_Data_Analysis.git/HEAD)

## What is Sentiment Analysis?
Sentiment analysis (also known as opinion mining or emotion AI) is the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information. Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine.

### Simple examples:
  - Coronet has the best lines of all day cruisers.
  - Bertram has a deep V hull and runs easily through seas.
  - Pastel-colored 1980s day cruisers from Florida are ugly.
  - I dislike old cabin cruisers.

### More challenging examples:
  - I do not dislike cabin cruisers. (Negation handling)
  - Disliking watercraft is not really my thing. (Negation, inverted word order)
  - Sometimes I really hate RIBs. (Adverbial modifies the sentiment)
  - I'd really truly love going out in this weather! (Possibly sarcastic)
  - Chris Craft is better looking than Limestone. (Two brand names, identifying the target of attitude is difficult).
  - Chris Craft is better looking than Limestone, but Limestone projects seaworthiness and reliability. (Two attitudes, two brand names).
  - The movie is surprising with plenty of unsettling plot twists. (Negative term used in a positive sense in certain domains).
  - You should see their decadent dessert menu. (Attitudinal term has shifted polarity recently in certain domains)
  - I love my mobile but would not recommend it to any of my colleagues. (Qualified positive sentiment, difficult to categorise)
  - Next week's gig will be right koide9! ("Quoi de neuf?" Fr.: "what's new?". Newly minted terms can be highly attitudinal but volatile in polarity and often out of known vocabulary.)



## YouTube Sentiment Analysis
With 2 billion monthly active users, YouTube is the 2nd most popular social media platform and, based on total visitors and page views, 2nd only to Google as the world???s most visited website. Yet, it goes largely untapped when it comes to opinion mining and social listening. YouTube users continue to grow by the day, and YouTube comments can provide a wealth of information and actionable insights for any brand. All those unguarded opinions and open customer feedback are free for the taking when you have the right tools and technologies in place.

### I have tried to analyze and vizualize the YouTube comments dataset by performing below steps:

  1. Gathered YouTube Comments Data
  2. Cleaned the Data
  3. Analyzed and Visualized The Sentiment of YouTube Comments
  4. Performed Exploratory Data Analysis (EDA) for Positive comments
  5. Performed Exploratory Data Analysis (EDA) for Negative comments
  6. Analyzed Trending Tags of YouTube Videos
  7. Regression Analysis of Likes and Views
  8. Regression Analysis of Dislikes and Views
  9. Correlation between Views, Likes, and Dislikes
  10. Emoji Analysis of YouTube Comments

> Libraries Used: pandas, numpy, matplotlib, seaborn, textblob

## Analyzing Trending Tags on YouTube
![tags](https://user-images.githubusercontent.com/30564193/114277229-5318b780-99f8-11eb-9633-25eb93a6f5a8.png)

## Regression Analysis of Likes and Views
![like and views](https://user-images.githubusercontent.com/30564193/114277514-83ad2100-99f9-11eb-9fe9-9ed8ac745d26.png)

## Regression Analysis of Dislikes and Views
![dislikes and views](https://user-images.githubusercontent.com/30564193/114277609-cff86100-99f9-11eb-8a0e-a8d7ab8936fb.png)

## Correlation between Likes, Dislikes, and Views
![correlation](https://user-images.githubusercontent.com/30564193/114277699-4b5a1280-99fa-11eb-8a8b-f450897da6e7.png)

## Emoji Analysis of YouTube Comments
![emoji](https://user-images.githubusercontent.com/30564193/114279090-dc33ec80-9a00-11eb-8707-47df70a79a03.png)
