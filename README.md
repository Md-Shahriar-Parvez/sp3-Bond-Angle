# Deriving the sp³ Bond Angle from Pure 3D Euclidean Geometry

An independent mathematical derivation of the sp³ bond angle **109.47°** using elementary three-dimensional Euclidean geometry and trigonometry.

## Overview

The tetrahedral geometry associated with **sp³ hybridization** is a familiar result in structural chemistry, with an ideal bond angle of approximately **109.47°**. Rather than treating this angle as a given result, this independent study reconstructs it from first principles using a purely geometric approach.

The derivation models the four surrounding atoms as the vertices of a **regular tetrahedron**, with the central atom located at the centroid. Starting from the geometry of an equilateral triangular face, the derivation progressively determines the tetrahedron's height, the distance from the centroid to each vertex, and finally the angle subtended by two vertices at the central atom.

The final geometric relationship is

**cos θ = −1/3**

giving

**θ = cos⁻¹(−1/3) ≈ 109.47°**

The derivation is intentionally developed without using vector dot products, relying instead on elementary geometric relationships and the **Law of Cosines**.

## Mathematical Approach

The derivation proceeds through the following geometric steps:

1. **Equilateral triangular face**
   Determine the face height and circumradius from elementary Euclidean geometry.

2. **Tetrahedral height**
   Use the resulting right triangle to determine the height of the regular tetrahedron.

3. **Centroid-to-vertex distance**
   Determine the distance between the tetrahedron's centroid and each vertex.

4. **Bond angle**
   Construct the isosceles triangle formed by the central atom and two surrounding vertices and apply the Law of Cosines.

This leads directly to the exact relation

**cos θ = −1/3**

and therefore

**θ = cos⁻¹(−1/3) ≈ 109.47° ≈ 109°28′**

## Motivation

This work originated from a broader interest in understanding familiar scientific results through **first-principles reasoning** rather than simply accepting established formulas.

The tetrahedral bond angle provides a particularly clear example: a result commonly encountered in chemistry can be reconstructed entirely from the geometry of a regular tetrahedron. The exercise therefore focuses less on obtaining a new chemical result and more on developing a transparent mathematical path from basic geometric principles to a well-known physical quantity.

## Contents

* `Bond_Angle_SP3.pdf` — Complete derivation and mathematical discussion
* `README.md` — Overview of the study

## Scope

This note concerns the **ideal tetrahedral geometry** associated with four equivalent directions from a central point. The purpose is to derive the geometric angle mathematically; it does not attempt to model deviations from the ideal tetrahedral angle caused by lone pairs, unequal substituents, steric effects, or other molecular interactions.

## Author

**Md. Shahriar Parvez**  
Department of Mechanical Engineering  
Bangladesh University of Engineering and Technology (BUET)  
Dhaka, Bangladesh
---

*This is an independent mathematical study conducted as part of my broader interest in first-principles derivations and geometric reasoning.*
