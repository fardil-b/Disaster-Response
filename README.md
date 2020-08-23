# Disaster-Response
### Building a Disaster Response Pipeline from tweets

Following a disaster there are normally millions of communications either directly or via social media, right at the time when disaster response organisations have their least capacity to filter and then pull out the messages which are the most important. Furthermore, not all messages are relevant to the disaster response professionals (maybe 1 in 1000). The way that disasters are typically responded to, is that different organisations will take care of different parts of the problem. One organisation will care about water, another about medical supplies, another will care about blocked roads…. Keyword searching might not be ideal for example searching for the word “water”, might not necessarily match with someone who needs drinking water it may miss people who do not use the word “water” instead say the word  “thirsty” . So supervised machine learning based approaches are going to be a lot more accurate that key word searching.

#### Project workflow: 
1.	Data processing, ETL pipeline to extract data from source and save them in proper database
2.	Machine learning pipeline to train a model able to classify text messages in categories
3.	Webb app to show model result in real time including visualization
