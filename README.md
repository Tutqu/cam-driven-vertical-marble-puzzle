# cam-driven-vertical-marble-puzzle

## Description:
Cam-and-follower mechanism design and iterative prototyping for a vertical STEM marble puzzle toy (UWaterloo ME100).

# The Conundrum Column: Vertical Mechanical Marble Puzzle

## Course & Project Context
This repository contains the design documentation, concept sketches, and prototyping history for **The Conundrum Column**, developed as the design project submission for **ME100: Introduction to Mechanical Engineering Practice I** (October 2026 – Present). 

The ME100 course focuses on foundational engineering principles, design methodology, and analytical reasoning. Applying these concepts, this project presents a viable STEM-focused educational product engineered to challenge users and foster critical problem-solving skills.

---

## Project Overview & Scope
The primary objective of **The Conundrum Column** is to aid children's cognitive development and fine motor skills through an engaging, mechanical vertical marble puzzle. Users must navigate a marble from the base of a 15 cm × 15 cm vertical tower to the top using only external mechanical controls—such as levers, cranks, pull strings, and buttons—without making direct physical contact with the marble.

**Subsystem Scope:** This repository specifically documents the **Cam-and-Follower Actuation Sublevel**, which represents one individual section of the full multi-level prototype developed in collaboration with a six-person engineering team.

---

## Key Features & Mechanical Design (Cam-and-Follower Sublevel)

* **No-Contact Object Transportation:** Internal mechanisms manipulate and translate the marble across vertical and horizontal axes exclusively through external user inputs.
* **Cam and Follower Drive System:** 
  * Converts rotational input from an external hand crank into recurring vertical output via a camshaft and follower mechanism.
  * Evolved from initial multi-grooved cam concepts to a refined single-cam architecture to maximize ball contact frequency while minimizing required handle rotations.
* **Hinged Impact Platforms:** Integrates a movable triangular base emerging from beneath a reference plane to strike, elevate, and guide the marble along the track.

---

## Prototyping & Iteration History

The sublevel mechanism underwent three distinct phases of engineering evaluation and physical prototyping:

1. **Initial Ideation & Concept Selection**
   * Evaluated a two-piece static plate slider with a ridge-and-groove track, but overruled it due to floating support requirements, poor external accessibility, and complex acrylic wall extrusions.
   * Selected a rotational cam-and-follower system inspired by automotive valvetrains to achieve recurring vertical actuation.
2. **Prototype 1: Cardboard & Dual-Cam Architecture**
   * Built a visual scale model featuring staggered dual cams driven by a bent wire crankshaft.
   * **Identified Failure Modes:** Scaling the interlocked components within a constrained 15 cm × 15 cm footprint proved difficult; the follower was too heavy for the cam to lift, lacked axial constraints (causing erratic vertical motion), and introduced height-offset calculation inconsistencies.
3. **Prototype 2: Refined Wood & Single-Cam Architecture**
   * Pivoted to a single-cam design anchored directly to a wooden rod (eliminating wire-slippage issues) and mounted the triangular impact plane directly onto a hinged follower to eliminate springs and guide wires.
   * Fabricated thin layered wood components using a panel saw and shaped the cam profile with a handheld buffer, successfully validating reliable vertical displacement of the impact platform.

---

## Remaining Engineering Challenges & Next Steps
* **Path Interference:** Evaluating and mitigating potential collisions between the emerging triangular platform ridges and the marble's natural rolling path.
* **Enclosure & Wall Integration:** Designing precise cut-extrusions and mounting interfaces for the outer acrylic walls.
* **Multi-Level Integration:** Coupling this cam-driven sublevel with neighboring team subsystems—such as a scissor lift, ramp, or elevator mechanism—to transport the marble between vertical levels.

---

## Repository Structure

```text
├── Sketches/               # Initial ideation, cam profiles, and layout drawings
├── CAD/                    # 3D part and assembly models
├── Prototyping/            # Physical prototype photos, dimensions, and test observations
├── Documentation/          # ME100 Conundrum Column Report and design matrices
└── README.md
