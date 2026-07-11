# Badminton Court Coverage Simulator

An interactive badminton doubles coverage simulator built with pure HTML, SVG, and JavaScript.

The application estimates which player can reach every point on the court by combining human movement physics instead of relying on simple geometric partitioning.

## Features

- Interactive drag-and-drop player positioning
- Real badminton court dimensions (6.10 × 13.40 m)
- Dynamic coverage visualization
- Dead-zone detection
- Direction-aware movement model
- Human reaction time simulation
- Acceleration-based movement
- Maximum reachable distance constraint
- Mobile-friendly interface
- No external dependencies

## Mathematical Model

Coverage is computed using multiple movement models:

- Euclidean Distance
- Human Reaction Time
- Accelerated Motion (kinematics)
- Maximum Running Speed
- Directional Movement Penalty
- Blind Spot Penalty
- Reachability Threshold
- Earliest Arrival Time Competition
- Grid-based Spatial Classification
- Dynamic Boundary Extraction

## Physical Parameters

- Court dimensions according to BWF
- Reaction time: 0.18 s
- Maximum speed: 4.5 m/s
- Acceleration: 12 m/s²
- Maximum reach: 4 m
- Direction-dependent movement cost

## Technologies

- HTML5
- SVG
- Vanilla JavaScript

No frameworks or external libraries are required.
