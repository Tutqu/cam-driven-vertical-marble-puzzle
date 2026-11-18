# cam-driven-vertical-marble-puzzle

## Description:
Cam-and-follower mechanism design and iterative prototyping for a vertical STEM marble puzzle toy (UWaterloo ME100).

# The Conundrum Column: Vertical Mechanical Marble Puzzle

## Project Overview
Engineered for **ME100: Introduction to Mechanical Engineering Practice I** at the University of Waterloo (October – Present), **The Conundrum Column** is an interactive STEM mechanical puzzle designed to develop spatial reasoning and fine motor skills in young children. 

Constrained within a compact **15 cm × 15 cm vertical footprint**, the system challenges users to transport a marble from the base of the tower to the top exit exclusively through exterior mechanical interfaces—cranks, levers, buttons, and pull strings—without direct physical contact with the marble.

**Subsystem Ownership:** This repository documents the **Cam-and-Follower Actuation Sublevel**, representing my dedicated mechanical subsystem within the full multi-level prototype developed in collaboration with a six-person engineering team.



## Mechanical Architecture & Design Rationale
* **Kinematics & Motion Conversion:** Translates continuous rotational input from an exterior hand crank into recurring vertical actuation via a custom camshaft and follower assembly, maximizing marble displacement per handle revolution.
* **No-Contact Impact Actuation:** Integrates a hinged, triangular wooden impact platform beneath a reference plane; as the cam rotates, the platform emerges to impart controlled upward and forward momentum to the marble.
* **Concept Trade-Off Analysis:** Evaluated alternative actuation methods—including static ridge-and-groove sliding plates—before selecting the rotational cam-and-follower architecture to eliminate floating support structures, reduce friction, and avoid complex pass-through extrusions in the outer acrylic enclosure.

##Sketches
<img width="592" height="275" alt="image" src="https://github.com/user-attachments/assets/067cfcac-e685-4166-a5db-4a56e6b0e564" />

<img width="797" height="256" alt="image" src="https://github.com/user-attachments/assets/383ef3ee-4cd4-4e90-8298-25d928c8cecc" />

##Prototypes
<img width="306" height="280" alt="image" src="https://github.com/user-attachments/assets/a9ad0c9b-c4f0-4eb0-b7a6-8cadd80e8af3" />
<img width="380" height="263" alt="image" src="https://github.com/user-attachments/assets/d616a58f-517f-4be9-93cd-9695bb3aaae5" />
https://github.com/user-attachments/assets/5a31ac2f-d174-4374-9e30-d1005381dd79



## Engineering Challenge & Iterative Resolution

### The Problem: Kinematic Instability & Packaging Constraints
During initial physical testing with a cardboard scale model, an automotive-inspired **staggered dual-cam and bent-wire follower** configuration exposed critical mechanical failure modes:
* **Packaging & Tolerance Stack-Up:** Interlocked components were difficult to package within the strict 15 cm × 15 cm spatial envelope, and slight height discrepancies between the dual cams created inconsistent displacement profiles.
* **Excessive Follower Mass & Friction:** The follower assembly was too heavy for the cam profile to lift smoothly under manual crank torque, while a lack of proper axial constraints allowed the follower to twist and bind rather than translate purely vertically.
* **Torque Slippage:** Relying on a bent wire crankshaft allowed the cams to slip under load rather than transmitting positive rotational torque.

### The Technical Fix: Kinematic Simplification & Direct Coupling
To eliminate binding, reduce part count, and improve mechanical reliability in **Prototype 2**, I redesigned the mechanism around core Design for Assembly (DFA) principles:
* **Single-Cam Optimization & Positive Drive:** Eliminated the secondary cam to remove dual-offset tolerance issues and anchored a single, precision-shaped wooden cam directly onto a rigid wooden drive shaft, ensuring positive torque transmission with zero slippage.
* **Integrated Hinged Follower:** Replaced the separate spring-and-wire follower assembly by mounting the triangular impact plane directly onto a hinged pivot arm, constraining motion to a single controlled degree of freedom and drastically reducing moving mass.
* **Fabrication & Validation:** Manufactured the layered wood components using a panel saw and hand-profiled the cam lobe with an abrasive buffer, successfully validating smooth, repeatable vertical actuation under manual cranking.



## Future Engineering Roadmap
* **Pathway Interference Mitigation:** Refining the ridge geometry of the emerging triangular platform to prevent unintended collision with the marble's natural rolling trajectory.
* **System-Level Integration:** Designing precision mounting interfaces for the outer acrylic walls and coupling this sublevel's exit path with neighboring team subsystems (vertical lift/scissor mechanism) to enable continuous multi-stage marble progression.


