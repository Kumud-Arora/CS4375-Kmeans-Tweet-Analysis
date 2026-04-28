# CS4375-Kmeans-Tweet-Analysis

K-Means clustering on health tweets using Jaccard distance.
 
## How It Works
 
- Tweets are preprocessed (URLs, mentions, punctuation removed) and converted to word sets
- Jaccard distance measures similarity between tweets
- K-Means clusters tweets for K = 5, 10, 15, 20, 25
- SSE is reported for each K
  
## Results
 
| K  | SSE     |
|----|---------|
| 5  | 1117.22 |
| 10 | 1076.99 |
| 15 | 1046.73 |
| 20 | 1033.44 |
| 25 | 1026.84 |
 
## Run It
 
https://colab.research.google.com/github/Kumud-Arora/CS4375-Kmeans-Tweet-Analysis/blob/main/kmeans_tweets.ipynb 
