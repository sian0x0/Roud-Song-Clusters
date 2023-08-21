# Background
English-language folk songs have a long tradition and have changed over time. Songs are not easily idenifiable by name alone, and lyrics often have variations. Steve Roud began indexing his own collection in the 1970s, and his Roud Index has become the standard for grouping together different versions of the same song. He is still indexing as of 2023.

Could a machine learning algorithm hope to match his skill? Given the lyrics, would it choose the same groupings of songs, where the line between "same" and "different" is fuzzy? Could it help with future indexing?

# Data
Extracted from Ballad Index and Digitrad (Mudcat) databases.

# Embeddings
Done using `instructor-large`. Dimensionality reduction with t-SNE.

# Soft clustering
Done with HDBSCAN

# Visualisation
Done with `plotly.express`.
