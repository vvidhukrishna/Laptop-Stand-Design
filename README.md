# Laptop Stand Design

A reverse-engineering and mechanical design project focused on recreating, 
analysing, and eventually improving a commercially available adjustable 
laptop stand using CAD, engineering calculations, and simulation.

**Repository:** [Laptop-Stand-Design](https://github.com/vvidhukrishna/Laptop-Stand-Design)

## Overview

This project investigates the design of a portable, foldable, and 
height-adjustable laptop stand, using the Cipto Aluminium Portable 
Foldable Laptop Stand (Model H1427) as the reference product.

The initial phase involves measuring and modelling the existing 
product in SolidWorks to understand its component architecture, 
adjustment mechanism, joints, and load paths. The resulting CAD model 
will serve as a baseline for engineering analysis and a future redesigned version.

Rather than stopping at geometric replication, the project aims to connect
CAD modelling with material selection, structural analysis, mechanism validation, 
and design improvement.

## Design Objectives

- Develop a CAD model of the reference stand through physical measurements and 
- reverse engineering.
- Understand the stand's folding mechanism, adjustment positions, and component 
- interactions.
- Evaluate candidate materials against strength and design requirements.
- Assess structural performance under representative laptop loading conditions.
- Validate mechanism motion and investigate structural behaviour using engineering 
- simulation tools.
- Develop an improved design based on the findings from the baseline model.

## Current Design Specifications

| Parameter | Specification |
|---|---|
| Reference product | Cipto Aluminium Portable Foldable Laptop Stand, Model H1427 |
| Intended application | Laptop support for desk use |
| Target laptop mass | 2–3 kg |
| Design approach | Reverse engineering followed by redesign |
| CAD software | SolidWorks |
| Structural analysis | ANSYS — planned |
| Mechanism modelling | MATLAB / Simscape Multibody — planned |

These are preliminary project requirements and tool choices. 
Simulation results and physical test results will be documented as they 
become available.

## Work Completed

### 1. Design Specification

Established the initial design requirements, constraints, and engineering direction 
for the project.

### 2. Reverse Engineering

Measured the reference product using basic dimensional and angle-measuring instruments 
to establish approximate component dimensions, pivot locations, and adjustment geometry.

### 3. CAD Component Modelling

Developed individual SolidWorks part models representing the stand's principal 
components and mechanical features.

### 4. Preliminary Material Selection

Established strength-based material selection criteria and evaluated candidate 
materials against the preliminary design requirements. Further structural verification 
will be required before finalising the material choice.

### 5. Assembly Development

Created an initial assembly structure to organise the model's components and 
establish the overall product configuration. Assembly constraints and mechanism motion 
remain subjects for further development and validation.

## Engineering Workflow

1. **Requirements and specifications** — establish functional requirements, 
loading assumptions, and constraints.
2. **Reverse engineering** — measure and interpret the reference product's 
geometry and mechanism.
3. **CAD development** — model components and construct the baseline assembly.
4. **Material selection** — compare candidate materials using mechanical 
properties and engineering criteria.
5. **Mechanism validation** — investigate joint constraints, degrees of freedom, 
and adjustment motion.
6. **Structural analysis** — evaluate stresses, deformation, and structural 
performance under representative loading.
7. **Design iteration** — identify opportunities to improve strength, stability, 
usability, and manufacturability.
8. **Verification and documentation** — compare analytical predictions, simulation 
results, and physical test results where available.

## Planned Tools

- **SolidWorks:** Part modelling, assemblies, engineering drawings, and design documentation.
- **MATLAB / Simscape Multibody:** Mechanism modelling and motion validation.
- **ANSYS:** Finite element analysis and structural performance evaluation.
- **Git / GitHub:** Version control, milestone tracking, and engineering documentation.

## Project Roadmap

| Milestone | Scope | Status |
|---|---|---|
| v0.1 | Initial design specification | Completed |
| v0.2 | Preliminary CAD components and design development | In progress |
| v0.3 | Complete CAD assembly | Planned |
| v0.4 | Engineering analysis | Planned |
| v0.5 | Prototype-ready design documentation | Planned |
| v1.0 | Final validated design | Planned |

Milestones may be refined as the design and validation process develops.

## Repository Structure

The repository is organised around the CAD model, design documentation, and 
supporting engineering work. Its structure will evolve as additional analysis 
and design deliverables are completed.

- `CAD models in SLDPRT/` — native SolidWorks component files.
- `Laptop_Stand_v0.1.pdf` — initial design specification.

Additional directories for assemblies, engineering drawings, simulation files, 
and neutral CAD exports may be added as those deliverables become available.

## Current Limitations

- The baseline CAD assembly has not yet been fully validated for mechanism motion.
- Material selection requires further verification through structural analysis.
- Simulation-based performance claims have not yet been established.
- The redesigned model and physical prototype remain future project objectives.

## Future Work

- Complete and validate the SolidWorks assembly.
- Develop engineering drawings with appropriate dimensions and tolerances.
- Validate the mechanism using MATLAB / Simscape Multibody.
- Perform structural analysis using ANSYS.
- Compare alternative materials and investigate design improvements.
- Evaluate the redesigned stand against the original requirements.
- Document verification results and conclusions.

## Author

**Vidhu Krishna**  
Mechanical & Aerospace Engineering  
[GitHub](https://github.com/vvidhukrishna)

---