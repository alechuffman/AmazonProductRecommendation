# Amazon Product Recommendation
![image](https://user-images.githubusercontent.com/75642633/113227045-7c8e5200-9246-11eb-94d9-c322d3795425.png)

Amazon's home page is some of the most valuable real estate on the internet. The products that get recommended on the home page can capture the attention of millions of people. This means it's incredibly important for Amazon to recommend the right products. Nobody wants to see products that they don't want. This is why Amazon spends so much time, effort, and money to develop the right algorithms to recommend products. That's why I decided to create my own product recommendation system. 

When it comes to recommendation systems, there are many different ways one can go about doing it. The approach I took was collaborative filtering. The collaborative filtering method makes recommendations by factoring in what similar users have liked and makes a prediction based on this. Collaborative filtering can be user-based or item-based. In user-based collaborative filtering, predictions are made based on similar users taste. In item-based collaborative filtering, predictions are made based on the similarity of the products and averages the users ratings of them.

Content based recommender systems could also be used in this context by taking descriptions of the products and using those to make recommendations. One downside to this approach is that you could end up with very similar products and not enough variety. This approach wasn't used.


For more information on collaborative filtering and recommendation systems, check out Google's course on recommendation systems which really helped me understand the topic:
https://developers.google.com/machine-learning/recommendation/collaborative/basics


**The data can be found here:** https://snap.stanford.edu/data/web-FineFoods.html
