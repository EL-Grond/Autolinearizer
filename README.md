# Autolinearizer
Tool for creating correlations between variables from given measurement data
By August Andersson
Usage:
By inserting a collection of data points connected to variable names and SI-units and the order of linearization, the program will determine the exponent for each variable. It does this by choosing the longest series of measurement where the variable in question varies the most while undetermined variables are kept constant. 
Disclaimer:
The values inserted in the initial file such as the file path and variable names are examples and can be easily changed.
"Vibrerande värden" demonstrates the format of data which the program accepts.
The program can only linerize correlations of the form I = Ka^Ab^B... and not I = (a+k)^Ab^B... where a,b... are variables and k is a constant.
