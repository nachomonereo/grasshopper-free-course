# Grasshopper Free Course

Welcome to the **Grasshopper Free Course** repository, created by **Nacho FC Monereo (@nachomonereo)**.  
This course provides a structured introduction to parametric design using Grasshopper, covering fundamental to advanced concepts through practical exercises.  

The repository includes **Grasshopper definitions (.gh files)** that demonstrate various workflows, algorithms, and modeling techniques applicable to **architecture, design, and digital fabrication**.

---

## 📂 Course Content and Grasshopper Files

Each file corresponds to a **lesson** in the course, designed to progressively introduce key concepts and techniques.

### 1️⃣ **Introduction to Grasshopper**
   - **File:** `day1-introduction.gh`
   - **Description:**  
     - Overview of **Grasshopper’s interface** and workflow.
     - Understanding **nodes, parameters, and data structures**.
     - Creating **basic parametric geometries** using sliders and mathematical expressions.

---

### 2️⃣ **Data Trees & Topography Manipulation**
   - **File:** `day2-lists-topography-tree.gh`
   - **Description:**  
     - Introduction to **data trees and list management** in Grasshopper.
     - Generating **topographic surfaces** from point clouds.
     - Extracting contours and creating **site models**.
     - Using **graph mappers** to control elevation and deformations.

---

### 3️⃣ **Image-Based Geometry & Data Visualization**
   - **File:** `session3-workflow-image.gh`
   - **Description:**  
     - Using **images as input data** for parametric design.
     - Extracting pixel color values and converting them into **height fields**.
     - Generating **density-based geometry** from image brightness.
     - Exploring **raster-to-vector** transformations.

---

### 4️⃣ **Urban Modeling & Panelization**
   - **File:** `session4-elk-city3D-panelization.gh`
   - **Description:**  
     - Importing **real-world urban data** using the **ELK** plugin.
     - Generating **3D city models** from OpenStreetMap data.
     - Applying **panelization strategies** to urban surfaces.
     - Exploring **modular facades and tiling systems**.

---

### 5️⃣ **Surface Design with Parametric Scales**
   - **File:** `session5-scales.gh`
   - **Description:**  
     - Designing **biomimetic surface textures**.
     - Creating **scalable, repeating modules** that adapt to curvature.
     - Implementing **attractor points** to control scale variation.
     - Using **subdivision techniques** for organic patterns.

---

### 6️⃣ **Mesh-Based Topography & Structural Optimization**
   - **File:** `session6-mesh-topography.gh`
   - **Description:**  
     - Generating **site topographies** using meshes.
     - **Smoothing techniques** to refine terrain surfaces.
     - Structural **mesh optimization** for lightweight designs.
     - Converting mesh landscapes into **fabrication-ready geometries**.

---

### 7️⃣ **Physics Simulations with Kangaroo**
   - **File:** `session7-kangaroo.gh`
   - **Description:**  
     - Introduction to **Kangaroo Physics** for real-time simulation.
     - Using **forces and constraints** to generate optimized structures.
     - Exploring **tensile structures**, fabric simulation, and bending.
     - Creating **self-supporting geometries** through iterative adjustments.

---

### 8️⃣ **Environmental Analysis & Evolutionary Optimization**
   - **File:** `session8-ladybug-galapagos.gh`
   - **Description:**  
     - Introduction to **Ladybug** for climate-responsive design.
     - Analyzing **solar radiation, daylighting, and wind flow**.
     - Using **Galapagos (Genetic Algorithms)** for form optimization.
     - Creating **energy-efficient building envelopes**.

---

## 🛠 Required Software & Plugins

To fully explore these files, you need:

- **Rhino 6 or newer** (with Grasshopper).
- **Plugins Required:**
  - [**ELK**](https://www.food4rhino.com/en/app/elk) → for urban data import.
  - [**Kangaroo**](https://www.food4rhino.com/en/app/kangaroo-physics) → for physics-based simulations.
  - [**Ladybug**](https://www.food4rhino.com/en/app/ladybug-tools) → for environmental analysis.
  - **Galapagos** (built into Grasshopper) → for optimization.

---

## 📌 How to Use the Files

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/nachomonereo/grasshopper-free-course.git