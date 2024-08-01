# SMOCaseStudy
A Case Study on the implementation and effectiveness of Sequential Minimal Optimization for binary classification

The following implementation only make use of the following Kernels
- Gaussian Kernel

# What is SMO ? 
SMO is one of the techniques for solving the dual problem of Support Vector Machines, leveraging Coordinate Ascent

# Findings
The following are the speed of the algorithm, (Without Multi-Threading) relative to the number of training data, where the parameters are 10%, Using Guassian Kernels. 

100 - 0.1 seconds

1000 - 10 seconds

10000 - 10 minutes


The duration of training seem to increase exponentially as the number of training data increases.
These findings are consistent with the finding of the paper below. 

# Remarks
A cleaner version of the code can be found inside SMOClass.py

# References 
https://www.researchgate.net/publication/2624239_Sequential_Minimal_Optimization_A_Fast_Algorithm_for_Training_Support_Vector_Machines
