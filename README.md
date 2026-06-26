# Cross-Modal Scene Graph Alignment

This project implements a hypergraph-based neural matching framework for cross-modal scene graph alignment.

## Features
- Scene graph representation for image and text
- Hypergraph neural encoding
- Sinkhorn-based differentiable matching
- Hungarian algorithm for inference

## Pipeline
1. Load dataset
2. Extract scene graphs
3. Encode using hypergraph network
4. Compute affinity matrix
5. Apply Sinkhorn normalization
6. Perform Hungarian matching

## Run
```bash
python main.py
