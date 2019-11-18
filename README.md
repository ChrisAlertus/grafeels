# grafeels

A small one-day weekend project playing around with spacy, pyDictionary and networkX to visualize clusters of feeling words.

The project ends by defining the edges of a hypothetical adjacency matrix where an (undirected) edge is drawn between two feeling words if the similarity of their corresponding word vectors is above the 99.5th quantile of feeling word similarities.
The resulting graph visualization in NetworkX shows a multi-component graph with many clusters of emotional adjectives.
