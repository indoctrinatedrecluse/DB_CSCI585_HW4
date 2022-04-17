Q1. There are 11 terms in the linear regression for the Boston Housing Dataset out of 13 supplied varibles.
    In a multiple regression prediction, we can check the association between MEDV (our label) and the independent variables.
    The 2 attributes, INDUS and AGE, which are missing, have very high correlation with two other independent variables, NOX and DIS, and can be ommitted (also apparent if we test for Princial Components, see image attached for correlation matrix).
    We also have 11 variables to predict the label, and their coefficients give us an indication of their relative order of weightage (see https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/bs704_multivariable/bs704_multivariable7.html for details).
    The final equation implies that the model trianed depicts MEDV to be most stringly dependent on these 11 columns with a certain weightage, and the numerical value which serves as an axial (height) adjustment.
Q2. I cannot find the equation in Knime so I included the plot with the trained model and also the resulting statistics.
Q3. There are 3 variables in the equation because these are the 3 varibales that we have ended up selecting from the list, and num_rings bears a relationship according to the model we have trained to said variables with the given weight.
    It may be noted that the first independent variable has a negative weightage, and this might mean it is negatively correlated to our label (num_rings).

Footnotes:
1. Each folder refers to a software each, with "weka" corresponding to Q1, "knime" to Q2 and "rapidminer" to Q3.
2. Each folder has screenshots of the results, for Q2 (knime) I have not labelled by question since there are two pictures.
3. I have included the workflows for KNime and RapidMiner Studio in their respective folders, and the stats have been included as Excel sheets, and the model as .model in knime folder.