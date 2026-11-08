# Research Community Detection Using Large-Scale Co-Authorship Networks

## Project Overview
This project focuses on identifying research communities by analyzing large-scale co-authorship networks using graph mining and community detection techniques.

## Dataset
- **Dataset:** DBLP Co-authorship Network
- **Source:** Stanford Network Analysis Project (SNAP)
- **Nodes:** 317,080 researchers
- **Edges:** 1,049,866 collaboration relationships

## Algorithms Used
- Louvain Algorithm
- Greedy Modularity Algorithm

## Technologies Used
- Python
- Google Colab
- NetworkX
- Pandas
- NumPy
- Matplotlib
- Apache Spark Structured Streaming

## Key Results
- Identified 202 communities in the full network using Louvain.
- Achieved a modularity score of 0.8208 on the full network.
- Louvain achieved better performance than Greedy Modularity in the 2,000-node comparison experiment.
- Demonstrated simulated real-time processing of 1,900 events.
- Achieved a maximum observed streaming throughput of approximately 1,361 events per second.

## Project Notebook
The complete implementation and analysis are available in the Google Colab notebook uploaded in this repository.

## Dataset Source
https://snap.stanford.edu/data/com-DBLP.html
