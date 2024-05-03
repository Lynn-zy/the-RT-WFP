# What is this repository for?
The RT-WFP is a algorithm for slope length extraction based on TIN.

# Environment
python3 and an IDE for running the python code.

# How to run the code? 
Download all the files, and running RT-WFP.ipynb in an IDE that supports running jupyter files. Make sure that all the extension packages used by the code (located in the first cell of the source code) is installed correctly. After configuring the data file in the 6th and 12th cells,it can be run automatically with one click. 

# Sample data description
All data were exported after processing by Arcmap 10.6.
## 300mcenterpoint.csv--Sample points data
p.xy is the xy coordinate of the sample point; Tri_index is the index of the triangular surface on which the sampling point is located; Slope_Pct and Aspect are the slope(percentage) and slope aspect of the triangular surface, respectively.
## 300mspacejoin.csv--Triangular surfaces data
Tri_index is the index of the triangular surface on which the sampling point is located; Slope_Pct and Aspect are the slope(percentage) and slope aspect of the triangular surface, respectively; Node_Index is the number of the triangular surface node; TinNod.xyz is the xyz coordinate of the triangular surface node.
