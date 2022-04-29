# Analyzing-Sentiment-of-Reddit-Comments-for-Content-Creators-And-Users

## **Background**
Reddit boasts over 430 million monthly active users and is one of the largest forum community social media networks on the internet. The site has a series of posts and users can comment on them and upvote/downvote posts and comments. Due to its popularity and engagement by its anonymous users, Reddit is a great platform for content creators to share their content to increase viewers. As a third-party service, our team plans to create a tool for content creators to better understand the sentiment of Reddit comments on their posts by predicting the emotions of their comments.

## **Motivation**
As a third-party service, our main goal is to provide insights and directions about the comments under the posts to assist creators to produce better content.

Nowadays, content creation comes in all shapes and sizes and the trending topics keep changing based on popular taste. Therefore, creators are always struggling to find appealing topics and to create innovative content. In order to attract more attention and likes, creators want to ensure that their contents match their audiences’ expectations as well as align well with the content theme. In addition, content creation is a time-consuming process. Oftentimes, creators spend day and night coming up with a single idea that may not correctly target their audience.
We would like to create a tool that is able to address all the possible problems mentioned above by using sentiment analysis and training a deep learning model. Firstly, we want to assist creators to target their audience more effectively. Second, we are able to help creators to reduce the time spent on contributing content, so they could have more time to adjust their content to target audiences accurately.
## **Dataset**
GoEmotions Dataset
https://github.com/google-research/google-research/tree/master/goemotions

- The datasets combined contain approximately 70,000 rows and 37 columns. Some useful columns are the whole comment and which subreddit it is from. The dataset also provides the timestamp of the comment.
- Columns from 'admiration', 'amusement' to 'neutral' are dummy variables that label the comments’ emotions. (The emotion categories are admiration, amusement, anger, annoyance, approval, caring, confusion, curiosity, desire, disappointment, disapproval, disgust, embarrassment, excitement, fear, gratitude, grief, joy, love, nervousness, optimism, pride, realization, relief, remorse, sadness, surprise.)
- Other variables such as the id of the comment, username of the comment author, link to the comment/post are also recorded if needed.
- Worth noting that there is a variable called “example_very_unclear” that tells if the comment is unclear to label.
