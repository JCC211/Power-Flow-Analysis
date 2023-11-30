# Power-Flow-Analysis

Comparing different power flow analysis methods. All analysis methods are performed on the same 3 bus system where bus details are specified in the file power_flow.ipynb. One assumption made was the property of transmission lines to be mostly reactive, therefore the admittance matrix Y only contains the imaginary terms for line impedances. True values are determined in the MATLAB files which include a simulink model.

The file power_flow.ipynb compares performance using Newton-Raphson method, modified Newton-Raphson method, and fast decouple load flow method.
