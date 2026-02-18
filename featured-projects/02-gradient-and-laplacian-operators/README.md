# Visualizing the Gradient and the Laplacian with GeoGebra

This project is an interactive tool designed to visualize the behavior of scalar functions $f: \mathbb{R}^2 \to \mathbb{R}$ through the **gradient** and the **Laplacian**.
<img width="1918" height="850" alt="Thumbnail" src="https://github.com/user-attachments/assets/80d0580d-4c84-47c1-b0ba-b1dbaffe1140" />


---

## Interactive Applet
**Access the tool here:** [Visualizing the Gradient and the Laplacian on GeoGebra](https://www.geogebra.org/m/z5sxvuee)  
> **Tip:** For the best experience, click the **Fullscreen** button on the bottom right corner of the window.

---

## Overview

In multivariable calculus, visualizing how a function changes in different directions can be challenging. This applet uses a **three-window system** to bridge the gap between algebra and geometry:

1.  **3D Surface View (Left):** Shows the graph of $f(x,y)$ as a mountain-like surface. It includes a movable point $P$ and its image $f(P)$, along with the gradient vector projected on the $xy$-plane.
2.  **Gradient Field View (Center):** A 2D top-down view focused on the **Vector Field**. Here you can see how the gradient vectors point toward peaks and away from valleys.
3.  **Calculations & Settings (Right):** Here you can input the function, adjust grid parameters, and view real-time analytic calculations for the Gradient and the Laplacian.

---

## Key Features

* **Dynamic Gradient Mapping:** Move point $P$ in either the 2D or 3D window and watch the gradient vector and the Laplacian update their values in the window on the right.
* **Vector Field Visualization:**
    * **Grid Control:** Adjust the separation and boundaries ($x_{min}, x_{max}$, etc.) of the vector grid.
    * **Color Coding:** Vectors are normalized to prevent overlapping, using a color gradient where **blue** indicates a small norm (flat areas) and **red** indicates a large norm (steep areas).
* **Analytic Calculations:** Real-time display of:
    * Coordinates of $P$ and the height $f(P)$.
    * The analytic expression of $\vec{\nabla} f$ and its value at $P$.
    * The analytic expression of the Laplacian $\nabla^2 f$ and its value at $P$.
* **Performance Optimization:** Use the **Compute Gradient** button to generate the field only when needed, saving system resources for complex functions.

---

## Mathematical Interpretation

* **The Gradient ($\nabla f$):** Tells us "which way is up." It always points toward the steepest path to the top of the mountain.
* **The Laplacian ($\nabla^2 f$):** Measures the divergence of the gradient. 
    * $\nabla^2 f < 0$: Vectors are "sinking" into the point (you are near a **peak**).
    * $\nabla^2 f > 0$: Vectors are "sourcing" out of the point (you are near a **valley**).
    * $\nabla^2 f = 0$: A balance of flow, the vectors are sinking into and sourcing out of the point in equal amounts.

---

## Project Documentation

Included in this repository is a detailed technical guide:
* **[Visualizing_Gradient_Laplacian.pdf](./Visualizing_Gradient_Laplacian.pdf)**

The PDF covers the fundamental definitions of scalar fields, and the geometric interpretation of the gradient and the Laplacian, and a full user manual for the GeoGebra applet.

---


## About the Project

This is part of an ongoing project for the YouTube channel [Sandrodmun](https://www.youtube.com/@sandrodmun) where we study subjects in mathematics and physics rigorously. We use interactive apps like this one to transform abstract concepts into visual environments that are easier to grasp.

The project is ambitious and aims to provide full, rigorous courses. Stay tuned for more interactive tools and deep-dives into Vector Calculus!

---
