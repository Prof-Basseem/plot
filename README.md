Chemical Data Visualization with Python
This repository contains Pandas, NumPy, Matplotlib, and Seaborn Python code for chemical data visualization.
## Overview
Chemical data is often complex and can be visualized. Python is used to visualize QCl compound infrared (IR) spectroscopy data in this repository. The 'T.CSV' file contains wavenumbers and absorbance data.
## Code
The [Jupyter Notebook] (QCl.ipynb) contains the data visualization code. The code does these things:
Importing data manipulation and visualization libraries
Reading 'T.CSV' with Pandas and naming columns 'Wavenumber(cm-1)' and 'Absorbance.'
Seaborn line plot of IR data with inverted x-axis and adjusted limits
- Save the plot as high-resolution 'QCl.png'
Open Jupyter Notebook in your Python environment to run the code and view the data.
## Use
To use this code:
1. Clone the repository locally.
2. Launch Jupyter Notebook QCl IR Visualization.ipynb.
3. Run notebook cells to visualize QCl IR data.
4. The repository will store 'QCl.png'.
Required
For code execution, you need:
Python 3, Jupyter Notebook, Pandas, NumPy, Matplotlib, and Seaborn
Install libraries using `pip` or `conda` as needed.
The dataset
This visualization uses 'T.CSV,' which contains QCl's IR spectroscopy wavenumbers and absorbance.
## Author
Mahmoud Basseem I. Mohamed
## License
The [LICENSE] file details the MIT license for this project.
