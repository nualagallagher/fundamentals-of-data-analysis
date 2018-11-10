# Fundamentals of Data Analysis

## Background on Anscombe's Quartet:
Anscombe’s quartet consists of 4 datasets that have very similar x and y values, however once plotted on a graph, each one is entirely different. These datasets were developed by Francis Ancombe in 1973. Francis was an English statistician who was educated at the University of Cambridge. It is important to note the value for x in the first 3 datasets is exactly the same throughout and that each dataset is made up of eleven points on the x and y axis. ( Anscombe, F. J. (1973). "Graphs in Statistical Analysis". American Statistician. 27 (1): 17–21)

Anscombe's Quartet is a great demonstration that datasets that are very similar numerically have huge variations when plotted. From this we can see the importantance to analyse data graphically and not alone on it's content.


## Running the python script in Jupyter Notebook:
To run the script to invesigate the data of Anscombe's Quarteet you must have already downloaded Visual Studio Code (https://code.visualstudio.com/) and Python (https://anaconda.org/anaconda/python).

1. Please find the script in the file fundamentals of data analysis assignment.ipynb within the Fundamentals of Data Analysis Depository. Copy this code and save to a new file or download it. Name it as you desire
2. Open Visual Studio Code (VSC).
3. To open the Integrated Terminal, click **View** and then click the **integrated terminal** or alternatively use the shortcut cntrl +'.
4. Type **jupyter notebook** into the Intergrated Terminal and press enter. A new internet tab will be opened.
5. In the Notebook Dashboard navigate to find the notebook: clicking on its name will open it in a new browser tab.
6. You can run the notebook document step-by-step (one cell a time) by clicking on a cell and pressing shift + enter. An sterisk between two square brackets [*] will appear when the code is running. Once the code is run a number will appear between two square brackets eg [1].
7. You can run the whole notebook in a single step by clicking on the menu Cell -> Run All.
8. To restart the kernel (i.e. the computational engine), click on the menu Kernel -> Restart. This can be useful to start over a computation from scratch (e.g. variables are deleted, open files are closed, etc.).

## Results: 
After running the script you will see scatter graphs for each dataset along with the best fit line. The means, mav and min are calculated for each 'x' and 'y' value in the dataset along with the standard deviation. The values of 'm' and 'c' in the equation of the line are also calculated. These values help determine the best fit line.

The above calculations and plots are discussed in more detail in the script.
