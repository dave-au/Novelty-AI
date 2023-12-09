# Novelty-AI
This is a POC project for generating mathematically novel ideas, using LLM embeddings, linear algebra and dirty, dirty hackery.

The blog post describing this project can be found here: https://medium.com/@david.taylor_45137/mining-the-embedding-cosmos-a-venture-into-unchartered-narratives-ad122d2d103a

The TL;DR - 
LLM's store semantic concepts as embeddings (vectors) within a highly dimension embedding space (latent space).
For concepts that are similar, the vectors are closer together in the embedding space.
Instead of seeking similarity, I've worked on an approach to find embeddings that are the most distant from a known data set of embeddings. This yields embeddings that represent novel concepts.

Keywords / phrases:
 LLM
 embedding
 cosine similarity
 linear algebra
 embedding inversion
 brute-force
