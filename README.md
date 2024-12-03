# Formula-1-Data-Analysis - 2021 Abu Dhabi GP Minisector Comparison

This project focuses on analyzing Formula 1 telemetry data from the 2021 Abu Dhabi GP to explore critical race strategies, including pit stop decisions and performance comparisons between drivers. Using Python and data visualization tools, this analysis provides insights into telemetry, lap times, mini-sectors, and overall race performance.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Data Sources](#data-sources)
4. [Features Implemented](#features-implemented)
5. [Key Visualizations](#key-visualizations)
6. [Technologies Used](#technologies-used)
7. [How to Run the Project](#how-to-run-the-project)
8. [Example Visualizations](#example-visualizations)
9. [Future Enhancements](#future-enhancements)
10. [Acknowledgments](#acknowledgments)

---

## **Introduction**
Formula 1 is a data-driven sport where race strategies and driver performance are heavily influenced by telemetry and analytics. This project utilizes Python to analyze telemetry data from the 2021 Abu Dhabi GP

The analysis includes:
- Fastest lap comparisons.
- Driver performance in mini-sectors.
- Visualizing speed telemetry and track positions.

---

## **Project Objectives**
1. **Understand race strategies** through telemetry data.
2. **Compare driver performances** in terms of speed, lap times, and sector times.
3. **Visualize telemetry data** to provide clear insights into key race moments.
4. Analyze the impact of pit stops and track conditions on race outcomes.

---

## **Data Sources**
The data for this project was sourced from the [FastF1 Python library](https://theoehrly.github.io/Fast-F1/), which provides access to F1 telemetry and timing data.

---

## **Features Implemented**
1. **Data Loading and Preprocessing**:
   - Fetch telemetry and lap data using FastF1.
   - Handle missing data and ensure clean datasets for analysis.

2. **Driver Comparisons**:
   - Fastest lap analysis for Max Verstappen (VER) and Lewis Hamilton (HAM).
   - Speed telemetry comparison across the track.

3. **Mini-sector Analysis**:
   - Divide the track into mini-sectors for granular performance analysis.
   - Identify the fastest driver in each mini-sector.

4. **Visualization**:
   - Interactive visualizations of telemetry data.
   - Heatmaps for speed distribution in mini-sectors.

5. **Race Strategy Insights**:
   - Evaluate the impact of pit stops and track conditions on lap times.

---

## **Key Visualizations**
- **Speed Comparison**: A detailed track map showing speed telemetry for each driver.
- **Mini-sector Heatmap**: Highlights the fastest driver in each mini-sector.
- **Fastest Lap Overlay**: Compares the fastest laps of VER and HAM with color-coded telemetry.

---

## **Technologies Used**
- **Python**: Primary programming language.
- **FastF1**: Library for accessing Formula 1 telemetry data.
- **Matplotlib**: Visualization library for static plots.
- **NumPy**: Data manipulation and processing.
- **Pandas**: Data handling and analysis.

---

### **Prerequisites**
Ensure the following are installed:
- Python 3.8+
- `FastF1`, `matplotlib`, `numpy`, and `pandas`.

### **Resources**
1. [F1 technical](https://www.f1technical.net/?sid=45f6f2f90e5e16a2675832501df04150)
2. [Formula 1](https://www.formula1.com/)
3. [Fast1](https://docs.fastf1.dev/)

---


## **Thank You**







