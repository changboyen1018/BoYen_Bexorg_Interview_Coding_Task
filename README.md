# Real-Time Sine Wave Plotter

## Overview
This PyQt5-based application is designed for real-time plotting of sine waves, allowing users to dynamically interact with the wave parameters such as amplitude, frequency, and offset. It showcases proficiency in using PyQt5, matplotlib, and Python for developing responsive GUI applications with complex backend computations.

## Usage
To run the application, execute the Bexorg_Interview.ipynb fiile in each parts independently.

## How to Operating the GUI
- 'Amplitude', 'Frequency', 'Offset': Enter values in these fields to adjust the characteristics of the sine wave.
- Start Plotting: Click the "Start" button to begin real-time plotting. The GUI will start displaying the data in real time (with assigned data).
- Stop Plotting: Click the "Stop" button to pause the data plotting.
- Adjust Parameters: For part 2&3, to change the parameters, first click the "Stop" button to pause the plotting. After adjusting the parameters, click the "Start" button again to apply the new settings and resume plotting.
- Save Data: For thr Part 3, the data will be saved as a .npy file and the timestamps as a .txt file, both named based on the current date and time.
- Exit the Application: Simply click the "Exit" button or close the window using the window manager.

## Documentation
The code is well-commented, providing detailed explanations of the functionality of each component between lines. The following sections are included:

- GUI Design: Documentation on the GUI layout and design choices.
- Functionality Integration: Descriptions of how each feature is implemented and integrated.
- Data Logging: Explanation of the data logging mechanism.
- Acknowledgments
    - PyQt5: For the GUI framework. [PyQt5 Documentation](https://www.riverbankcomputing.com/static/Docs/PyQt5/)
    - matplotlib: For plotting capabilities. Matplotlib [Documentation](https://matplotlib.org/)
    - pyqt5-tools: For additional PyQt5 tools. [Riverbank Computing](https://www.riverbankcomputing.com/software/pyqt/)


## Features
- **Dynamic Plotting**: Visualize sine waves in real time with adjustable parameters.
- **Interactive GUI**: Users can start and stop the plotting process via the GUI, enhancing interaction.
- **Multithreading**: Utilizes PyQt's QThread to ensure the GUI remains responsive during intensive computational tasks.
- **Data Logging**: Logs data with precise timestamps every minute to ensure accuracy and no data loss.


## Contributing
Contributed by Bo-Yen (Danny) Chang, assisted with LLM tools for refinement.
changboyen@berkeley.edu
