# 🧫 Belly Button Biodiversity Dashboard

**Author:** Logan Dameron  
*A data science project created for educational purposes as part of the edX Data Science Bootcamp.*

---

## 🚀 Overview

This interactive dashboard visualizes microbial biodiversity found in human belly buttons.

The project explores how bacterial species (OTUs) vary across individuals using an interactive dashboard built with D3.js and Plotly.js. All visualizations update dynamically based on user selection.

---

## 🌐 Data Source

- [Belly Button Biodiversity Dataset](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)
- JSON version hosted at:  
  `https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json`

---

## ⚙️ Technologies Used

- JavaScript
- D3.js (for data loading and DOM manipulation)
- Plotly.js (for chart rendering)
- HTML/CSS

---

## 📊 Dashboard Features

The app loads sample data from an external JSON file and updates visuals dynamically.

### ✅ Bar Chart
- Top 10 OTUs found in selected individual
- Uses `sample_values` (bar size)
- `otu_ids` as labels
- `otu_labels` as hover text

### ✅ Bubble Chart
- Displays all OTUs per individual
- Marker size = `sample_values`
- Marker color = `otu_ids`
- Hover text = `otu_labels`

### ✅ Demographic Info Panel
- Shows metadata for selected individual (e.g. age, location, washing frequency)
- Updates on dropdown change

---

## 📁 Folder Structure

```bash
📦 belly-button-challenge
 ┣ 📜 index.html
 ┣ 📜 samples.json
 ┣ 📂 static
 ┃ ┗ 📂 js
 ┃     ┗ 📜 app.js
 ┣ 📜 README.md