# Visualizing Graph Isomorphisms with GeoGebra

This project is an interactive tool and game designed to help develop an intuition for **Graph Isomorphisms**. In graph theory, two graphs are isomorphic if they are "the same" structurally, even if they are drawn differently. This applet allows you to manipulate scrambled graphs to match a target structure, making the process of finding an isomorphism more visual.
<img width="1335" height="522" alt="Thumbnail" src="https://github.com/user-attachments/assets/8c34bc98-7041-4266-ae99-6e8100ffa457" />

---

## Interactive Applet
**Access the tool here:** [Graph Isomorphisms Game on GeoGebra](https://www.geogebra.org/m/vhcja6kr)  
> **Tip:** For the best experience, click the three dots in the top right and select **"Open in App"**. This allows you to hide/show objects easily, and provides the most flexible interface for solving complex graphs.

---

## Overview

A graph $G = (V, E)$ is defined by its **Vertices** (nodes) and its **Edges** (connections). The core challenge of this project is understanding that the *position* of these vertices does not change the identity of the graph.

The applet presents a "Two-Graph Challenge":

1.  **The Target Graph (Left/Static):** A graph shown in its most recognizable, symmetrical form (e.g., a Square, Petersen, or Heawood graph).
2.  **The Random Graph (Right/Dynamic):** An isomorphic copy of the target, but with vertices $P_i$ placed at random coordinates.

Your goal is to find the **isomorphism**—the mapping—by dragging the random vertices until the two shapes match perfectly.

---

## Key Features

* **Diverse Library of Famous Graphs:** Practice with structures like the **Petersen Graph** (10 nodes, 15 edges), the **Heawood Graph**, or the complex **Coxeter Graph**.
* **Custom Challenge Mode:** Use the **Random** option to generate your own graphs. You can adjust sliders to choose the exact number of vertices and edges for a unique puzzle.
* **Interactive Manipulation:** Click and drag any vertex $P_i$ to rearrange the graph's layout in real-time.
* **Assistance Tools:**
    * **Show/Hide Labels:** Toggle vertex names to help identify the mapping $f: V_1 \to V_2$.
    * **The Solve Button:** Stuck on a 28-vertex monster? Click "Solve" to see the vertices automatically migrate to their isomorphic positions.

---

## Mathematical Context

Two graphs $G_1$ and $G_2$ are **isomorphic** ($G_1 \cong G_2$) if there exists a **bijective function** $f: V_1 \to V_2$ such that:
$$\lbrace u, v\rbrace \in E_1 \iff \lbrace f(u), f(v)\rbrace \in E_2$$.

This is known as **edge preservation**. In this game, when you place $P_1$ on top of vertex $A$, you are visually defining the mapping $f(A) = P_1$. As the number of vertices ($n$) increases, finding this mapping becomes a computationally hard problem.

---

## Project Documentation

Included in this repository is a detailed technical guide:
* **[Graph_Isomorphisms_Guide.pdf](./Graph_Isomorphisms_Guide.pdf)**

The PDF covers the formal definition of undirected graphs, the properties of bijective mappings, examples of edge preservation, and a full user manual for the GeoGebra applet's different modes.

---

## About the Project

This is part of an ongoing project for the YouTube channel [Sandrodmun](https://www.youtube.com/@sandrodmun) where we study many different subjects in mathematics, physics, etc., rigorously with precise definitions and proofs, and interactively, with apps and games like the ones in this repository.

The project aims to make abstract concepts, results, theorems, etc. more intuitive and accessible. Stay tuned for more interactive tools and full courses!

---
