# Livability for Pittsburgh Neighborhood

## 👥 Team Information  
**Team Name:** Livability Research Men

**Team Members:**  
- Zihan Yuan — ZIY118@pitt.edu
- Yuzhe Wang — YUW420@pitt.edu
- Cortes-Del-Valle Marcos F — mfc56@pitt.edu

---

## 📌 One-Sentence Overview  
This repository builds a data-driven livability score for Pittsburgh neighborhoods using multiple datasets

---

## 📂 Project Description  
In this project, we aim to find the "best" neighborhood in Pittsburgh. We define our "bestness" as "livability" with tree aspects: safety, environment and convenience. we also define our submetric as "crime-scores with variable"x", tree-scores with variable "y" and convenient-scores with variable "z". Finally, we apply linear fumula ( f(x,y,z)=w1x+w2y+w3*z )with pre-defined weights w1, w2 and w3 for our final metric to determine the results. we use 4 dataset for our analysis, the first one is the crime activities happened in the neighhood, the second one and third one are the number of trees in the neighborhood and the size for each neighbor, the last one is the number of transit stop in each neighhood.

---

## 📊 Datasets Used  

- **Crime Data** (`incidents_2024_thru_mar2026.xlsx`)  
  Description: Contains crime incident records used to measure neighborhood safety.  

- **Tree Data** (`Pittsburgh_Trees.csv`)  
  Description: Used to evaluate environmental quality based on tree distribution.  

- **Neighborhood Boundary Data** (`neighborhoods.geojson`, `neighborhoods_size.csv`)  
  Description: Provides geographic boundaries and size information for neighborhoods.  

- **Stops / Convenience Data** (`stops.geojson`)  
  Description: Used to measure accessibility and convenience within neighborhoods. 
---

## 📓 Notebooks  

- **Final Notebook**  
  `Final Notebook Group27.ipynb`  
  → Contains the final results, visualizations, and conclusions.  

- **Sub-metric Notebooks**  
  - `Sub-metric Crime.ipynb` → Crime analysis  
  - `Sub-metric Tree.ipynb` → Environmental analysis  
  - `Sub-metric convenience.ipynb` → Accessibility analysis  

---

## ⚙️ Repository Structure  
Group27 CMPINF11/
│
├── Final Notebook Group27.ipynb
├── Sub-metric Crime.ipynb
├── Sub-metric Tree.ipynb
├── Sub-metric convenience.ipynb
│
├── incidents_2024_thru_mar2026.xlsx
├── Pittsburgh_Trees.csv
├── neighborhoods.geojson
├── stops.geojson
├── neighborhoods_size.csv
