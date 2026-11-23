# Clustering sensor readings in C++

The program groups timestamped observations by sensor and identifier, forms distance-based groups, and merges them into clusters. Follow the [sample CSV](data/test_Data.csv) through [the entry point](main.cpp) into [the clustering implementation](srcs/clusterize.cpp).

Build with `make` from the repository root. When comparing grouping changes, start with the same input so differences in cluster membership are visible.
