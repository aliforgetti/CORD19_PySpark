# COVID-19 Research Paper Recommendation Engine for Researchers

In this project we developed the framework for a recommendation engine to assist COVID -19 researchers in finding research papers that are similar to a paper of their interest. This type of work can facilitate the process of literature review which can involve searching through multiple research papers in order to find something that is appropriate. 
To do this we used Latent Dirichlet Allocation (LDA) to extract a distribution of topics within each paper abstract. We also used Sentence-BERT to represent each paper abstract as an embedding of length 768. Finally, we implemented a unified approach of aggregating the cosine similarity from these two items and recommended papers that had a high cosine similarity from both of these representations. 

