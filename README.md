# Bachelor Thesis

**Title:** From Solar Geometry to Direct Current Output: A Mathematical Approach to Photovoltaic System Modeling

## Overview

This thesis focuses on the mathematical modeling of photovoltaic (PV) systems to simulate their direct current (DC) power output under various environmental conditions. The core of the model is based on a well-known single-diode five-parameter model, which is calibrated using minimal data provided by manufacturers. The thesis also incorporates thermal and transposition models to estimate operating conditions such as cell temperature and solar irradiance.

## Structure

The thesis is organized into the following chapters:

1. **Introduction**  
   Provides an overview of the research objectives, the significance of PV system modeling, and the structure of the thesis.

2. **Solar Geometry and Radiation**  
   Introduces the fundamentals of solar geometry and radiation, including methods to estimate in-plane irradiance.

3. **Photovoltaic System Modeling**  
   Details the physical modeling of PV systems, including the five-parameter model and thermal models.

4. **Application and Analysis of the Model**  
   Applies the developed model to a real-world PV system and evaluates its accuracy using error metrics such as rMBE and rMAE.

5. **Conclusion**  
   Summarizes the findings, discusses limitations, and suggests directions for future research.

## Key Features

- **Five-Parameter Model:** A robust approach to modeling the current-voltage characteristics of PV cells.
- **Thermal Models:** Includes both a simplified model and the Sandia National Laboratories model for estimating cell temperature.
- **Error Analysis:** Evaluates model accuracy using relative mean bias error (rMBE) and relative mean absolute error (rMAE).

## Data Sources

Meteorological data, including temperature, wind speed, and irradiance, were obtained from nearby weather stations. The model was applied to a 4.62 kW PV system in Bavaria, Germany.

## Figures and Tables

The thesis includes several figures and tables to illustrate key concepts, such as:

- Relationship between solar irradiance and cell temperature.
- Influence of wind speed on module temperature.
- Thermal coefficients for different module types and mounting configurations.

## Tools and Software

- **LaTeX:** Used for writing and formatting the thesis.
- **MATLAB/Python:** (If applicable) Used for simulations and data analysis.

## Acknowledgments

This thesis was supervised by **Prof. Dr. Oliver Junge** and advised by **Dr. Vadim Gorski** at the Technical University of Munich.

## License

This thesis is the intellectual property of the author and is not licensed for public use or distribution without explicit permission.

---