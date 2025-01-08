# Pen2Graph
This project was done as a final project in CS 6172 at Cornell University. It automates the generation of visually matching node-edge graph programs from hand-drawn sketches by leveraging vision-language models and differential evolution, combining visual input with mathematical constraints to guide program earch.

[Final Project Report](https://github.com/zzigak/Pen2Graph/blob/main/pen2graph.pdf)


## Overview

The Pen2Graph pipeline takes as input:
- An image of a hand-drawn sketch of a node-edge graph (visual constraint).
- A specification describing the graph's connectivity (mathematical constraint).

Using these inputs, the system:
1. Generates a parametrized program (e.g., in Matplotlib) via a vision-language model (VLM).
2. Optimizes the program's parameters using differential evolution to produce a rendering that visually matches the input sketch.

