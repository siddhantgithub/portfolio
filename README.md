# Welcome To My Website
## Projects
### Librobuddy - Collaborative Filtering + NLP based book recommendation engine
#### Description: A book recommendation engine that uses collaborative fitlering and a HuggingFace transformer model to provide book recommendations based on user personality. Overall flow:

- Develop a recommendation model based on collaborative filtering using PyTorch. Amazon book review dataset is used for the recommendation engine
- Use Book Embeddings (latest parameters) to cluster books using K-means clustering
- Generate cluster big-five personality type using a Hugging Face transformer model
- To generate book recommendations, ask a User to provide 3 - 4 line bio 
- Use a HuggingFace transformer model to assess user big-five personality from the bio
- Identify a book cluster that matches closely to the user personality and provide top rated books from the cluster

##### [GitHub Link](https://github.com/siddhantgithub/LibroBuddy)
