# Traffic-Flow-Forcasting

Traffic Flow Forecasting using GCN + Transformer + Cross-Attention

Project Overview

This project implements a hybrid deep learning model for spatio-temporal traffic forecasting by combining Graph Convolutional Networks (GCNs), Transformers, and a Cross-Attention mechanism. Traffic prediction is a complex problem influenced by both spatial dependencies (road network structure) and temporal patterns (traffic changes over time).

The model works as follows:

GCN Module – Captures spatial dependencies using the road network adjacency matrix and node features.

Transformer Module – Captures temporal dependencies from sequential traffic data.

Cross-Attention Module – Fuses spatial and temporal embeddings, highlighting important interactions.

Dense Layers – Generate final traffic predictions for multiple nodes simultaneously.

Features / Highlights

Joint modeling of spatial and temporal dependencies.

Multi-output prediction for all nodes in the network.

Improved interpretability through attention weights.

Averaged or node-wise predictions with visualization.

Tools & Technologies

Language: Python

Libraries: PyTorch, NumPy, Pandas, Matplotlib, Scikit-learn

Environment: Jupyter Notebook

Usage

Clone the repository.

Load your traffic feature dataset (X_train, X_test) and adjacency matrix (Adj.csv).

Run the notebook to train the hybrid model and generate predictions.

Visualize results using provided plotting functions.

Future Enhancements

Incorporate external factors such as weather, events, and accidents.

Enable real-time dynamic updates for traffic graphs.

Extend to multi-city networks for better generalization.

Optimize for deployment and enhance explainability of predictions.
