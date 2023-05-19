# ECE204-Project-3
This project explores Unsupervised machine learning for deciphering the structure of multidimensional datasets
We used our mutations file for the project.
In this project we are analyzing head and neck squamous cancer. 
Run the jupyter notebook with your mutations file and use the appropriate number of mutations, in our case we observe 96 mutations.
<br/>

To use SigProfilerPlotting (https://github.com/AlexandrovLab/SigProfilerPlotting) use the following steps:  
```
pip install SigProfilerPlotting
```
Import in python3:  
```
import sigProfilerPlotting as sigPlt  
sigPlt.plotSBS(matrix_path, output_path, project, plot_type, percentage=False)  
```
Where matrix_path, output_path, project, and plot_type must be strings (surrounded by quotation marks, e.g."/Users/ebergstr/Desktop/test_sample").
<br/>

To use signature.tools.lib (https://github.com/Nik-Zainal-Group/signature.tools.lib) use the following steps:  
```
git clone https://github.com/Nik-Zainal-Group/signature.tools.lib.git  
```
Enter the R environment from the main directory of signature.tools.lib:  
```
install.packages("devtools")  
devtools::install()
```
Import in R:
```
library(signature.tools.lib)
```
