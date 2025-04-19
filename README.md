# llm-segmentation

### data preparation

Done - Web scraping from Google reviews, and got 607 pairs of reviews and ratings. (v)

### Embeddings

- use Word2Vec to create a vector for each review. (v)
- normalize ratings (0~5) to align with the embedding scale. (make it 0~1) (v)
- concatenate the embedding + rating into one vector. (v)
- Other embeddings:
  - Llama (waiting for approval)
  - OpenAI
  - BERT
  - falcon-7b

### K-means clustering

- choose the number of clusters
- Elbow method -> find ideal k
- PCA --> visualize to find ideal k

### clustering test

- Silhouette score

### Simulated test

- generate marketing strategies for the n groups of users
- use Gpt to impersonalize the three customer
- AI customers rate the strategies.
