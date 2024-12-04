# Santa Cruz Tidal Simulation

This project simulates the ocean tides in Santa Cruz. The goal is to model tidal variations and analyze experimental data, including the impact of the Hunga Tonga-Hunga Ha'apai tsunami on the tidal measurements.

## Requirements
- Python 3.x
- numpy
- scipy
- matplotlib
- pandas

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/tidalreport-c4.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tides-simulation
    ```

3. Install the necessary Python libraries:
    ```bash
    pip install numpy
    pip install pandas
    pip install Matplotlib
    python -m pip install scipy
    ```

## Project Overview

1. **Tidal Model**: Define an oscillatory function to model the intra- and inter-day variations of the tide.
2. **Curve Fitting**: Fit the model to experimental tidal data.
3. **Residual Analysis**: Subtract the model from the data and plot residuals to assess statistical significance.
4. **Tsumanai Deviation**: Analyze the deviation caused by the tsunami event.

## Contributors
-  Hassan Afify
-  Blue Eslami
