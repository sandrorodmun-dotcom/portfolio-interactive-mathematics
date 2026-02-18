<div>
<br class="Apple-interchange-newline">

# Visualizing Change of Basis in $\mathbb{R}^2$ with GeoGebra

This project is an interactive tool designed to visualize how the coordinates of a vector change when we switch between different bases.

<img width="1918" height="736" alt="Thumbnail" src="https://github.com/user-attachments/assets/b68cab6d-07e9-49f1-bf20-66866b7acbc0" />


---

## Interactive Applet

**Access the tool here:** [Change of Basis in R2 on GeoGebra](https://www.geogebra.org/m/uuxbyzbc)  

> **Tip:** For the best experience, click the three dots in the top right and select **"Open in App"**. This allows you to resize the windows.

---

## Overview

In linear algebra, a basis provides a coordinate system for a vector space. While the "Canonical Basis" is the most common, different problems are often easier to solve in alternative bases. This applet shows how changes of basis work in $\mathbb{R}^2$, both algebraically and geometrically. To do this, we have 2 windows:

1.  **Geometric Plane (Left):** A visual environment where you can drag vectors $\vec{v}$, $\vec{u}_A, \vec{u}_B$ (Basis $u$), and $\vec{w}_A, \vec{w}_B$ (Basis $w$). You can see how $\vec{v}$ is decomposed along different axes.
2.  **Coordinate Calculator (Right):** A numerical engine that displays the coordinates of all vectors in the three bases and explicitly shows the **Change of Basis Matrix** $M_{w \leftarrow u}$.

---

## Key Features

* **Dynamic Vector Manipulation:** Drag the heads of basis vectors to see how the background grid and coordinates update in real-time.
* **Automatic Matrix Generation:** Watch as the applet constructs the matrix $M_{w \leftarrow u}$ by expressing the vectors of $\mathcal{B}_u$ in terms of $\mathcal{B}_w$.
* **Coordinate Translator:** Input a custom vector $\vec{a}$, choose its source basis, and immediately see its representation in all other systems.
* **Projection of the Vector:** Toggle "Show Components" to see the projections of the vector $\vec{v}$ onto the vectors of the basis.
* **Linear Independence Testing:** Observe what happens to the matrix and the coordinate values when basis vectors become parallel (linearly dependent).

---

## Mathematical Context

If we have two bases $\mathcal{B}_u = \lbrace \vec{u}_A, \vec{u}_B \rbrace$ and $\mathcal{B}_w = \lbrace \vec{w}_A, \vec{w}_B \rbrace$, the coordinates of a vector $\vec{v}$ are related by the **Change of Basis Matrix**:

$$\\begin{pmatrix} d_1 \\\\ d_2 \\end{pmatrix}_{\\mathcal{B}_w} = M_{w \\leftarrow u} \\cdot \\begin{pmatrix} c_1 \\\\ c_2 \\end{pmatrix}_{\\mathcal{B}_u}$$

The columns of $M_{w \leftarrow u}$ are the coordinates of the "old" basis vectors expressed in the "new" basis. This matrix is invertible (nonsingular) as long as the basis vectors remain linearly independent:

$$\det(M_{w \leftarrow u}) \neq 0$$

---

## Project Documentation

Included in this repository is a detailed technical guide:
* **[Change_of_Basis_Guide.pdf](./Change_of_Basis.pdf)**

The PDF covers the definition of a basis, the step-by-step derivation of the change of basis matrix, the formula for the inverse transformation, and a full manual for the GeoGebra applet.

---

## About the Project

This is part of an ongoing project for the YouTube channel [Sandrodmun](https://www.youtube.com/@sandrodmun) where we study many different subjects in mathematics and physics rigorously with precise definitions and proofs, and interactively, with apps and games like the ones in this repository.

The project aims to make abstract concepts, results, and theorems a bit more intuitive and accessible. Stay tuned for more interactive tools and full courses!

---
</div>
