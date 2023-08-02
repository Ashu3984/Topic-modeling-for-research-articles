# Topic-modeling-for-research-articles

Modeling with LDA:

After preprocessed the  data, I have employed the Latent Dirichlet Allocation algorithm to perform topic modeling. LDA is an unsupervised learning technique that assumes each article is a mixture of multiple latent topics, and each topic is a distribution over words. The LDA model iteratively assigns words in each article to different topics based on probabilities, ultimately discovering the most likely topics in the entire corpus.

Perplexity and Coherence Scores:

To evaluate the quality of the topic models, we computed two important metrics: perplexity and coherence scores. Perplexity measures how well the model predicts new data (i.e., unseen articles) based on the trained model. A lower perplexity score indicates better generalization and understanding of the data. Coherence, on the other hand, quantifies the interpretability and consistency of topics. Higher coherence scores imply more coherent and meaningful topics.
