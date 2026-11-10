# 📊 04. Data Visualization

This directory focuses on the graphical representation of information and data to identify patterns, trends, and outliers using both static and interactive plotting libraries.

## 🎯 Learning Objectives
*   **Core Plot Types:**
    *   Histogram
    *   BoxPlot & BoxenPlot
    *   LinePlot
    *   BarPlot
    *   Scatter Plot
*   **Advanced Visualizations:**
    *   ViolinPlot
    *   Heatmap
    *   PairPlot & JointPlot
    *   CatPlot & RelPlot
*   **Customizing Figures:** Axes, Labels, Legends, Colors, and Themes.
*   **Subplots and Grid Layouts**
*   **Visual Exploratory Data Analysis (EDA)**
*   **Interactive Dashboards:** Building web-based interactive data applications using Plotly and Dash.

## 🛠️ Tools
*   **Python**
    *   Matplotlib
    *   Seaborn
    *   Plotly (Interactive Visualizations)
    *   Dash (Web Application Framework)

## 🚀 Interactive Dashboard Application

This repository includes an interactive web application built with **Dash** and **Plotly**. The application runs a local server and provides a user interface to filter and analyze the EPA fuel economy dataset dynamically.

### Features
*   **Dynamic Filtering:** Filter data by Year Range (using a slider) and Transmission Type (using a checklist).
*   **Interactive Visualizations:**
    *   A Histogram displaying the distribution of Annual Fuel Costs, color-coded by vehicle class.
    *   A Scatter Plot visualizing the relationship between Engine Displacement (`displ`) and Fuel Cost.
*   **Cross-filtering:** Selecting points on the Scatter Plot automatically updates the data table to show only the selected vehicles.
*   **Data Table:** A dynamic table displaying raw data for the top 10 results or the specific points selected on the graph.

### How to Run the Dashboard
To launch the interactive dashboard, run the corresponding Python script from your terminal:

```bash
python <your_dash_script_name>.py