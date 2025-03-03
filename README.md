# Hydropower System Analysis

## Overview
This project provides an interactive web application for analyzing **fluid dynamics, structural integrity, control systems, predictive maintenance, environmental impact, and system reliability** in hydropower plants. The system allows users to input various parameters and receive results along with a downloadable ZIP file containing a report with preventive actions.

## Features
- **Fluid Dynamics Analysis**: Calculates water flow velocity and turbulence.
- **Structural Integrity Assessment**: Predicts life expectancy based on material strength and stress factors.
- **Control System Optimization**: Determines optimized flow rate for grid demand.
- **Predictive Maintenance**: Estimates failure risk using sensor data.
- **Environmental Impact Analysis**: Evaluates the effect of water quality and habitat change.
- **Material Science Application**: Computes enhanced material lifetime based on durability and wear rate.
- **System Reliability & Risk Assessment**: Estimates overall system reliability.
- **Downloadable Report**: Generates a ZIP file with analysis results and preventive actions.

## Installation
1. Clone the repository:
   ```sh
   git clone [https://github.com/PSivaMallikarjun/hydropower-analysis](https://github.com/PSivaMallikarjun/HydroInsight-AI-Powered-Hydropower-Analysis).git
   cd hydropower-analysis
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   python app.py
   ```

## Usage
- Open the web app in a browser.
- Enter system parameters (e.g., flow rate, pressure drop, material strength, etc.).
- Click **Analyze** to process the inputs.
- View the analysis results on the interface.
- Download a detailed **ZIP report** with results and preventive actions.

## Sample Input Values
| Parameter               | Example Value |
|-------------------------|--------------|
| Flow Rate (m³/s)       | 10           |
| Pressure Drop (Pa)     | 500          |
| Material Strength (MPa)| 250          |
| Stress Factor         | 5            |
| Grid Demand (MW)      | 100          |
| Response Time (s)     | 10           |
| Sensor Data (%)       | 80           |
| Water Quality (%)     | 90           |
| Habitat Change Impact | 2            |
| Material Durability   | 20           |
| Wear Rate            | 1            |
| Risk Factor          | 2            |

## Performance Optimization
- **Asynchronous Report Generation**: The downloadable ZIP file is generated using multi-threading to reduce processing time.
- **Efficient Computation**: Optimized mathematical models ensure fast and accurate results.

## Technologies Used
- **Python** (NumPy, SciPy, Matplotlib, Gradio)
- **Gradio** (Interactive UI)
- **FPDF** (Report Generation)
- **ZIP File Handling** (Fast Report Compression)

## Future Enhancements
- Implement AI-based anomaly detection for predictive maintenance.
- Support for real-time hydropower monitoring.
- Integration with IoT sensors for automated data input.

## Author
**Siva Mallikarjun Parvatham**

## License
This project is licensed under the **MIT License**.

![Screenshot 2025-03-03 080410](https://github.com/user-attachments/assets/c46ad230-e50f-43db-b307-881b6fcaf9a5)
![Screenshot 2025-03-03 082455](https://github.com/user-attachments/assets/c9c0b8f8-6714-4571-941a-aa87f51dbc8b)


