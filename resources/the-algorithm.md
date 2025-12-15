Description  of how they rank, choose tweets.
> "What is the probability you will interact with another user in the future?”
> 
> “What are the communities on Twitter and what are trending Tweets within them?” 

## Candidate sources
We attempt to **extract the best 1500 Tweets from a pool of hundreds of millions through these sources**. 
We find candidates from people you follow (In-Network) and from people you don’t follow (Out-of-Network). 
Today, the For You timeline consists of 50% In-Network Tweets and 50% Out-of-Network Tweets on average, though this may vary from user to user.


> [Chat] The goal of each candidate source is to pull potential candidates (Tweets) from the huge global set into a manageable pool (~1500 Tweets) that the algorithm can then rank and filter for your “For You” timeline.
>
> > A component that suggests possible Tweets to consider based on some criteria or modeling approach.



The most important component in ranking In-Network Tweets is Real Graph. Real Graph is a model which predicts the likelihood of engagement between two users. The higher the Real Graph score between you and the author of the Tweet, the more of their tweets we'll include.


# Out of network sources
**Analyzing the engagements of people you follow or those with similar interests.**
- What Tweets did the people I follow recently engage with?
- Who likes similar Tweets to me, and what else have they recently liked?


