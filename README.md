#INTERNSHIP
AI Powered News Search App (Level-1) BY - SHANJAYKM

URL of news app created is https://node-red-sslpbjp.eu-gb.mybluemix.net/red/#flow/f68edee1.27416

Search from Slack can be done by following steps. The slack bot will respond to certain key words in the input , below is a sample dialog. Remember to @ the bot each time, or start a private chat. Make sure to invite your bot into other channels using /invite @.

user: @SHANJAYKM hello @watson_news: Hello.

user: @SHANJAYKM news please @watson_news: Hi there! What news are you interested in?

user: @SHANJAYKM olympic @watsonn_news: You want me to search for news articles about 'olympic'?

user: @SHANJAYKM yes @watson_news: OK searching...

Features of created UI are: 1) Search any news 2) Sentiment analysis using bar chart 3) Sentiment of particular news 4) News category also displayed 5) For searching any news you only have to type your query and click on submit button.

Query Watson Discovery News using the Watson Discovery service

In this code pattern, we build a Node.js web application that uses the Watson Discovery service to access Watson Discovery News.

Watson Discovery News is a default data collection that is associated with the Watson Discovery Service. It is a data set of primarily English language news sources that is updated continuously, with approximately 300,000 new articles and blogs added daily.

This code pattern demonstrates two use cases for accessing Watson Discovery News:

Trending Topics in the News: Identify popular topics over the past 24 hours. Topics can be general, or for a specific industry or category.

Search: Query for the most relevant new articles about a specific topic or subject. Results will include enrichment data, such as article summary text and sentiment analysis.

Some of main parts of projects are:

The user interacts with the Watson Discovery News Server via the app UI.
User input is processed and routed to the Watson Discovery News Server.
The Watson Discovery News Server sends user requests to the Watson Discovery Service.
The Watson Discovery Service queries the Watson News Collection.
The Watson Discovery Service responds to Slack search requests.
