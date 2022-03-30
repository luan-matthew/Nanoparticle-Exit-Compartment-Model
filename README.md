# Nanoparticle Exit Compartment Model

MATLAB script modeling nanoparticle exit from solid tumours over 120 hours. 

The MATLAB script quantifies the amount of nanoparticles that exit solid tumours via the lymphatics and the blood using a four compartment model. Model rate constants and initial conditions are optimized to best predict the experimental data using a bounded variation of fminsearch - fminsearchbnd. Model validation is performed by assessing the correlation coefficient between experimental values and model predictions for data used during model development (training data), and data withheld from model development (validation data), and by performing sensitivity analysis. 

The model is run from nanoparticle_exit_model.mlx. This MATLAB interactive file requires the directory locations of B16F10_IDg.csv, fminsearchbnd.m, and sensitivity_analysis.mlx. The mode outputs plots for the model predictions, the goodness-of-fit assessment, and the lymphatic and blood exit quantities over the course of 120 hours. 

fminsearchbnd can be downloaded from the MathWorks file exchange via the following link: https://www.mathworks.com/matlabcentral/fileexchange/8277-fminsearchbnd-fminsearchcon
