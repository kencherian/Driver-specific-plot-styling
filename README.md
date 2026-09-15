# Driver-Specific Plot Styling

## Overview
This repository contains a Python-based data visualization project focused on generating custom, driver-specific plots. It is designed to analyze and visualize telemetry, race pace, and performance metrics, tailored specifically for Formula 1 racing data. The core analysis is conducted within Jupyter Notebooks, providing an interactive environment for exploring high-speed data and extracting competitive insights.

## Features
* **Driver-Specific Visualizations:** Custom color palettes and styling automatically applied to individual drivers and constructors.
* **Telemetry Analysis:** Generate speed, throttle, braking, and gear-shift traces across different circuit sectors.
* **Interactive Notebooks:** Easy-to-use Jupyter environments (including `Untitled0.ipynb`) for rapid data exploration and manipulation.
* **Custom Styling Themes:** Apply dark mode, specialized grids, and high-contrast markers tailored for motorsport data visualization.

## Technologies Used
* **Python 3.x**
* **Jupyter Notebook**
* **Matplotlib & Seaborn** (for advanced data visualization)
* **Pandas** (for data manipulation)
* **FastF1** (for retrieving timing and telemetry data)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Driver-specific-plot-styling.git
   cd Driver-specific-plot-styling
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Launch Jupyter Notebook in the project directory:
   ```bash
   jupyter notebook
   ```
2. Open `Untitled0.ipynb` to view the initial data loading and plot generation examples.
3. Modify the target driver variables (e.g., 'VER', 'HAM', 'NOR') to generate new telemetry plots with their respective team colors and styling overlays.

