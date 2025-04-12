# Redesigning the AWS Heatmap: Visualizing Cooling Degree Days (CDD)

This project is a redesign of the original AWS Cooling Degree Days (CDD) heatmap. The goal was to enhance interpretability, interactivity, and accessibility through thoughtful visualization, guided by data visualization theory and FAIR principles.

---

## Table of Contents

- [Overview](#overview)
- [Visualizations Included](#visualizations-included)
- [Tools & Libraries](#tools--libraries)
- [Theory & Frameworks](#theory--frameworks)
- [Project Information](#project-information)
- [Navigation Instructions](#navigation-instructions)
- [References](#references)

---

## Overview

The original AWS heatmap lacked contrast, context, and metadata transparency. This project presents an improved visualization suite using Python to communicate Cooling Degree Days data more effectively through three distinct charts.

---

## Visualizations Included

1. **Heatmap** – Improved contrast and interactivity, spatial-temporal CDD overview  
2. **Snake Race Bar Chart** – Animated chart visualizing annual trends and rankings  
3. **Radial Bar Chart** – Emphasizes the cyclical, seasonal nature of CDD data  

All charts support:
- **Hover-based interaction** for tooltip insights  
- **Playback controls** for animated transitions through years  

---

## Tools & Libraries

- `pandas` – Data handling  
- `numpy` – Data simulation (original dataset unavailable)  
- `plotly` – Interactive and animated data visualizations  

---

## Theory & Frameworks

- **Visualization Theory**
  - Heatmaps: spatial + scalar encoding (Munzner, 2014, p.145)  
  - Snake bar charts: ranking + time (Munzner, 2014, p.125)  
  - Radial charts: seasonal patterns (Munzner, 2014, p.130)  
- **FAIR Principles** (Wilkinson et al., 2016):  
  - *Findable, Accessible, Interoperable, Reusable*  
- **LLM Accessibility Research** (Choe et al., 2024):  
  - Integrating large language models enhances accessibility and understanding for non-expert users.

---

## Navigation Instructions

- **`InfoVis Redesign.pdf`** – Full written explanation of critique, theory, redesign and research  
- **`Infovis redesign.ipynb`** – Open in Jupyter or Colab to view/edit the Python visualizations  
- **`cooling_degree_days_2014_2024.xlsx`** – Data file used in the redesign  
- **`infovis redesign poster.pdf`** – Summary poster suitable for presentation with all visualizations included  

---

## Project Information

- **Author**: Gbemisayo Motunrayo Aderonke Adelaja 
- **Instructor**: Professor Luyao Zhang 
- **Course**: INFOSCI 301- Data visualization and Asethetics 
- **Institution**: Duke Kunshan University
- **Acknowledgement**: Thanks to the instructors and peers who provided feedback throughout the project.

**Disclaimer**: This project was created for academic purposes. The dataset used is simulated and does not represent actual climate data from AWS.

---

## References

- Choe, G., Ragan, E., & Stasko, J. (2024). *LLMs for Visualization Accessibility*.  
- Munzner, T. (2014). *Visualization Analysis and Design*. CRC Press.  
- Ware, C. (2012). *Information Visualization: Perception for Design*. Morgan Kaufmann.  
- Wilkinson, M. D., et al. (2016). *The FAIR Guiding Principles*. Scientific Data.  
- AWS (2024), Gartner (2024), Yurbi (2023), Transcenda (2022)

---
## Project Poster

![Project Poster](./InfoVis Redesign.pdf)
