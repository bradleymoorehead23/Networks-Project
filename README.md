# Hot 100 Analysis: A Network Approach to Changes in Popular Music Collaborations Over Time
## This repository contains our code and data.

### Data:
1. In the data/artists folder, the file `artists_{year}.csv` contains the names and offical Spotify `uri`s of the Hot 100 artists for that year, and `artist_genres.csv` lists the top genre of each artist according to Spotify.
2. In the data/adj_matrices folder, the file `adj_matrix_{year}.csv` contains the adjacency matrix derived from that year's Hot 100 data.

### Code:
In the notebooks folder, `network_creation.ipynb` was used to create the adjacency matrices, `verification.ipynb` was used to verify the names and `uri`s of artists in the `artists_{year}.csv` files, `analysis.ipynb` was used to obtain our analytical results, and `genre_labels.ipynb` was used to retrieve the top genre of each artist from Spotify.
