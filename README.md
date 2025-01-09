# Pen2Graph
This project was done as a final project in CS 6172 at Cornell University. It automates the generation of visually matching node-edge graph programs from hand-drawn sketches by leveraging vision-language models and differential evolution, combining visual input with mathematical constraints to guide program earch.

![Screenshot 2025-01-08 at 04 07 11](https://github.com/user-attachments/assets/d6a7dae9-fa62-4bea-a7ec-dffeabfb49a5)

[Final Project Report](https://github.com/zzigak/Pen2Graph/blob/main/pen2graph.pdf)


## Overview

The Pen2Graph pipeline takes as input:
- An image of a hand-drawn sketch of a node-edge graph (visual constraint).
- A specification describing the graph's connectivity (mathematical constraint).

Using these inputs, the system:
1. Generates a parametrized program (e.g., in Matplotlib) via a vision-language model (VLM).
2. Optimizes the program's parameters using differential evolution to produce a rendering that visually matches the input sketch.

## Sample Results
### Hand-drawn to program 
<img width="316" alt="2" src="https://github.com/user-attachments/assets/d63892ce-a1f4-46f2-98d2-0d3eafd0b26b" />

### Synthetic to program
<img width="368" alt="1" src="https://github.com/user-attachments/assets/9ed2340e-2a9f-4846-8be4-2ea22d23558b" />




