# Finnair Project

## Overview
This project was made during my internship at Finnair, designed to assist aviation professionals. The EFB app allows users to input specific parameters, and the application gives an output based on these parameters.

## Features
- **Aircraft Selection**: Choose from various aircraft models with corresponding parameters.
- **Parameter Input**: Enter values for key parameters.
- **Computation**: Compute the result based on input parameters.
- **CSV Data Parsing**: The app loads CSV files based on the parameters and calculates results.
- **Interactive UI**: Includes sliders, pickers, and segmented controls to allow easy and accurate data input for users.
- **Adaptivity**: The application supports portrait and landscape mode, in addition to light and dark mode.

## Key Components
- **TableView Cells**: Custom cells (slider, picker, time picker, custom etc.) that allow users to input data for different aircraft parameters.
- **CalculationManager**: A core logic module that handles data parsing, logic, and the calculations.

## How it Works
1. **Select Aircraft Type**: Users select an aircraft type, and the app adjusts the available parameters accordingly.
2. **Input Parameters**: Users provide values for parameters in the custom cells.
3. **Calculations**: The app processes the provided inputs, applies the logic for the selected aircraft model, and retrieves relevant values from the CSV data to do calculations.
4. **Display Results**: The result is displayed with validation checks, and users can adjust inputs to see different outcomes.

## Requirements
- iOS 13.0+
- Swift 5.0+

![picture1](./images/IMG_0015 2.jpg)
![picture2](./images/IMG_0016 2.jpg)
![picture3](./images/IMG_0020 2.jpg)
![picture4](./images/IMG_0018 2.jpg)
