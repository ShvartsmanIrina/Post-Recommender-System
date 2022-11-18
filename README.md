## Content-based Post Recommendation System

This is my project on a social media post recommendation system.

The task was to implement a service that will return posts for each user at any time, which will be shown to the user in his social network feed.

To build recommendations for users of posts, I trained the CatBoost model using the content-based approach on the data that contained long texts that had to be vectorized.

To vectorize the texts, I used two approaches. The first approach used tf-idf. The second to build embeddings using a pre-trained transformer RobertaModel.

I compared the two trained models (control model and test model) that I received by doing an A/B test and came to the conclusion that test model the test model gives a statistically significant improvement in recommending posts to users. 

More information can be found in the project notebook.


