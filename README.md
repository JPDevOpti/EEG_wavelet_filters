## EEG Signal Analysis with Wavelet Filtering

This repository provides tools for analyzing EEG (electroencephalography) signal data using wavelet thresholding. It includes functionality for loading EEG data, performing wavelet decomposition, applying thresholding to filter out noise, and visualizing the results. The main components of the repository are:


1. **Data Loading**: Methods to read and preprocess EEG signal data from CSV files.
2. **Wavelet Transform:**: Functions for applying Discrete Wavelet Transform (DWT) to decompose the signal into different frequency components.
3. **Thresholding:**: Techniques for applying thresholding to wavelet coefficients to reduce noise.
4. **Visualization**: Functions to create plots of the original and filtered signals to assess the effect of wavelet filtering.



## Features

- **Load EEG Data**: Import EEG signal data from CSV files with time and amplitude columns.
- **Wavelet Transform**: Perform wavelet decomposition using a specified wavelet type and varying levels of decomposition..
- **Thresholding**: Apply universal thresholding to wavelet coefficients to filter out noise.
- **Plotting**: Generate visualizations of both the original and filtered EEG signals for comparison.

## Requirements

To run the code in this repository, you need to have the following Python packages installed:

- **`numpy`**: A library for numerical computations and array manipulations.
- **`pandas`**: A library for data manipulation and analysis, especially for handling CSV files.
- **`matplotlib`**: A library for creating static, animated, and interactive visualizations in Python.
- **`scipy`**: A library for scientific and technical computing, including signal processing tools.
- **`pywt`**: The PyWavelets library for wavelet transform and analysis.

You can install these dependencies using pip. Open your terminal or command prompt and run the following command:

```bash
pip install numpy pandas matplotlib pywt
