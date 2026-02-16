# Visualizing Complex Functions with GeoGebra

This project is an interactive tool designed to visualize the behavior of complex-valued functions $f: \mathbb{C} \to \mathbb{C}$. Since complex functions map a 2D input (real and imaginary) to a 2D output, they effectively exist in 4D space. This applet uses a **two-plane mapping** method to make these transformations intuitive and visually accessible.
<img width="1916" height="725" alt="Thumbnail_1" src="https://github.com/user-attachments/assets/383fae1f-3001-47aa-be87-941c97c37611" />

---

## <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/b814f35e-6993-492d-baff-e05a91e25aa8" /> Interactive Applet
**Access the tool here:** [Visualizing Complex Functions on GeoGebra](https://www.geogebra.org/m/axw5rbzs)  
> **Tip:** For the best experience, click the three dots in the top right and select **"Open in App"**. This allows you to resize windows and access the full input capabilities of GeoGebra.

---

## 📖 Overview

In real analysis, we graph functions like $f(x) = x^2$ on a 2D Cartesian plane. In complex analysis, we need a different approach. This project implements a side-by-side visualization:

1.  **Domain Plane (Left):** Where you define your input $z = a + bi$.
2.  **Image Plane (Right):** Where the resulting $f(z) = c + di$ is plotted.

By moving $z$ or tracing specific paths, you can see how complex functions rotate, stretch, and transform the complex plane.

---

## 🛠 Key Features

* **Dynamic Mapping:** Drag point $z$ and watch $f(z)$ move in real-time.
* **Path Tracing:** Toggle "Show Path" to visualize the geometry of transformations (e.g. f(z)=e^z takes diagonal straight lines into spirals, horizontal lines into rays coming out of the origin, and vertical lines into circles centered at the origin).
* **Grid Analysis:** Analyze how horizontal and vertical lines transform in the **Image Plane**. This is a nice way of studying **conformal mappings**.
* **Parametric Input:** Define exact paths $x(t)$ and $y(t)$ to see how specific mathematical curves are transformed.
* **Custom Functions:** Input any complex expression directly into the $f(z)$ input box. Some nice functions to try are $z^2$, $exp(z)$, $sin(z)$, etc.

**Note:** The exponential $e^z$ has to be entered as $exp(z)$.

---

## 📂 Project Documentation

Included in this repository is a detailed technical guide:
* **[Visualizing_Complex_Functions.pdf](./Visualizing_Complex_Functions.pdf)**

The PDF covers the fundamental differences between real and complex analysis, the mathematics behind parametric path mapping, and a full user manual for the GeoGebra applet.

These notes are intended to be a quick reference for using the applet, more rigorous notes on Complex Analysis and other subjects are also on their way!


---

## <img width="40" height="44" alt="00_Logo_Version_2_no_white_square" src="https://github.com/user-attachments/assets/4fc2a239-9398-4277-8c3c-2f9760efe5db" /> About the Project

This is part of an ongoing project for the YouTube channel [Sandrodmun](https://www.youtube.com/@sandrodmun) where we will study many different subjects in mathematics, physics, etc., rigorously with precise definitions and proofs, and interactively, with apps and games like the ones in this repository that will make the concepts easier to grasp.
The project is ambitious and far-reaching so it will take some time until I can upload the full courses to the YouTube channel, but I will try to upload part of the full courses soon!



---
