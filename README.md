# Polarization Image Processing with Polanalyser

This Jupyter Notebook (`playground.ipynb`) provides a workflow for processing raw polarized images using the [Polanalyser](https://github.com/elerac/polanalyser) library. The pipeline extracts meaningful polarization parameters such as Intensity, Degree of Linear Polarization (DoLP), and Angle of Linear Polarization (AoLP).

## Features
- Demosaic raw polarized images
- Compute Stokes vectors from polarization images
- Convert Stokes vectors to Intensity, DoLP, and AoLP
- Visualize results with color maps
- Display computed measurements under each visualization

## Requirements
Ensure you have the necessary dependencies installed before running the notebook:

```bash
pip install numpy opencv-python matplotlib polanalyser
```

## Usage
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook playground.ipynb
   ```
2. Replace `dataset/dragon.png` with your actual image file path.
3. Run all cells to process the image and visualize results.

## Output
The notebook generates:
- Intensity image
- Degree of Linear Polarization (DoLP) visualization
- Angle of Linear Polarization (AoLP) visualization
- Computed mean values displayed below each plot

## References
- [Polanalyser GitHub Repository](https://github.com/elerac/polanalyser)

