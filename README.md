# Customer Segmentation Using Transformer-based Models and Word2Vec Embeddings on Google Reviews

2025 Spring - LLM final project

Indiana University Bloomington, M.S.Informatics

### data preparation

Web scraping from Google reviews, and got 607 pairs of reviews and ratings.

### Embeddings

- use Word2Vec to create a vector for each review.
- normalize ratings (0-5) to align with the embedding scale. (make it 0-1)
- concatenate the embedding + rating into one vector.
- Other embeddings:
  - Llama 2-7b-chat-hf
  - Sentence transformer BERT(all-mpnet-base-v2)
  - Sentence transformer BERT(all-MiniLM-L6-v2)
  - falcon-7b

### K-means clustering

- choose the number of clusters
- Silhouette score --> get ideal k
- PCA --> visualize to clustering with ideal k

### Simulated test

- generate marketing strategies for the n groups of users
- use GPT to impersonalize the three customer
- AI customers rate the strategies.

## Result

- If you're interested in the final report, please check [here](https://drive.google.com/file/d/1Y6opZvpWeFPsV9UVdH9uJ-HPSKIvXNsY/view?usp=sharing)
- The report was submitted on May 4th, 2025.

## Citation

Please cite this work if you plan to reference it in your project.
