# Interactive-network-visualization
Interactive force-directed network visualization using D3.js v5 with drag-to-pin nodes and degree-based styling.
# Interactive Network Visualization — Graph Analytics with D3.js

[D3.js](https://img.shields.io/badge/D3.js-Visualization-orange)
[JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
[Data Visualization](https://img.shields.io/badge/Data-Visualization-blue)

## Project Overview
This project demonstrates an **interactive force-directed network visualization** built using **D3.js v5**.  
The visualization explores similarity relationships between board games using nodes and links in a dynamic graph layout.

## Designed as part of advanced data visualization work, this project highlights skills in:

- Interactive data visualization
- Network graph analytics
- Front-end data storytelling
- Event-driven UI design

---

## Demo Preview


[Interactive Graph Demo](assets/demo.png)


---

## Problem Statement
Understanding relationships between entities is critical for many data-driven systems:

- Recommendation engines
- Social network analysis
- Knowledge graph exploration
- Pattern discovery in relational datasets

This visualization allows users to explore connectivity patterns through interaction.

---

### Features

## Force-Directed Layout
- Physics-based graph simulation
- Dynamic node positioning
- Collision handling for clarity

## Visual Encoding
- Node size scaled by degree
- Color gradient representing connectivity strength
- Edge styling based on similarity values

## User Interaction
- Drag nodes to reposition network
- Pin nodes by dragging
- Double-click to unpin nodes
- Labels move dynamically with nodes

## Clean DOM Structure
- SVG-based rendering
- Structured layout for maintainability
- Modular HTML, CSS, JS setup

---
## Architecture

Data (CSV)

   ↓
   
D3 Data Binding

   ↓
   
Force Simulation Engine

   ↓
   
SVG Rendering Layer

   ↓
   
Interactive Events

---

## Tech Stack
- **D3.js v5**
- JavaScript (ES6)
- HTML5 / SVG
- CSS
- Python HTTP Server (local testing)

---

## How to Run Locally

Clone the repository:

```bash
git clone https://github.com/bharathvardhan/interactive-network-visualization.git
cd interactive-network-visualization
```
start local server:
```bash
python3 -m http.server 8000
```
open in browser:
```bash
http://localhost:8000/Q2/Q2.html
```

## Project Structure
interactive-network-visualization/
 ├── Q2/
 │    ├── Q2.html
 │    ├── board_games.csv
 │    └── d3-dsv.min.js
 ├── assets/
 └── README.md


 ## Impact & Insights

- This project demonstrates how interactive visualization improves exploratory analysis:
- Highlights highly connected nodes through size encoding
- Reveals structural clusters via force simulation
- Enables manual spatial organization through node pinning
- Improves interpretability of relational datasets

## Author

Bharath Vardhan Reddy Ravula
M.S. Data Analytics Engineering — George Mason University
