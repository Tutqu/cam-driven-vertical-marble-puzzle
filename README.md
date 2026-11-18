# cam-driven-vertical-marble-puzzle

## Description:
Cam-and-follower mechanism design and iterative prototyping for a vertical STEM marble puzzle toy (UWaterloo ME100).

# The Conundrum Column: Vertical Mechanical Marble Puzzle

## Project Overview
Developed for **ME100: Introduction to Mechanical Engineering Practice I** at the University of Waterloo (October – Present), **The Conundrum Column** is a STEM-focused educational toy designed to foster cognitive development, problem-solving, and fine motor skills in young children. 

Users must navigate a marble from the base of a 15 cm × 15 cm vertical tower to the top using only exterior mechanical controls—such as cranks, levers, buttons, and pull strings—without ever making direct physical contact with the marble.

**Subsystem Scope:** This repository specifically documents the **Cam-and-Follower Actuation Sublevel**, which represents my individual section of the larger multi-level prototype developed in collaboration with a six-person engineering team.



## Key Mechanism Design
**No-Contact Actuation:** Converts rotational input from an external hand crank into recurring vertical output via a camshaft and follower, providing substantial ball movement per handle turn.
**Hinged Impact Platform:** Utilizes a rotating cam to push a triangular wooden platform upward from beneath a reference plane, striking and advancing the marble along the track.
**Design Selection:** Evaluated alternative concepts such as static ridge-and-groove sliding plates, but selected the rotational cam architecture to avoid complex acrylic wall extrusions, floating supports, and poor external accessibility.


## Engineering Challenge & Resolution
**The Problem:** During the first cardboard prototyping phase, our initial automotive-inspired dual-cam and bent-wire follower system exposed critical mechanical limitations. Scaling the interlocked components within the constrained 15 cm × 15 cm footprint proved difficult, the follower was too heavy for the cam to lift reliably, and a lack of axial constraints caused inconsistent vertical motion alongside height-offset calculation issues between the two cams.
**The Fix:** To resolve these instabilities in Prototype 2, I simplified the architecture to a **single-cam design** anchored directly onto a wooden shaft to eliminate wire slippage. I also mounted the triangular impact platform directly onto a hinged follower—eliminating the need for springs or support wires—and fabricated the layered wood components with a panel saw and handheld buffer, successfully validating smooth vertical displacement.



## Next Steps
* **Path Optimization:** Refining the triangular platform ridge geometry to prevent interference with the marble's natural rolling pathway.
* **System Integration:** Designing outer acrylic wall mounting interfaces and coupling this sublevel with neighboring team subsystems (such as an elevator, ramp, or scissor lift) to bridge vertical levels.

