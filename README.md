# Autolinearizer
Tool for creating correlations between variables from given measurement data
By August Andersson
Usage:
By inserting a collection of data points connected to variable names and SI-units, the program will determine the exponent for each variable. It does this by first determining which variable will give the most secure result when linearizing with respect to which variables' exponents are already determined. With the chosen variable it then chooses the longest series of measurement where the variable in question varies the most while undetermined variables are kept constant. It can also handle composite variables on the form (a/b*c)^A where arbitrary amounts of division and multiplication can be performed.
Disclaimer:
The values inserted in the config file such as the file path and variable names are examples and can be easily changed.
"Vibrerande värden" demonstrates the format of data which the program accepts.
The program can only linerize correlations of the form I = Ka^Ab^B... and not I = (a+k)^Ab^B... where a,b... are variables and k is a constant.
