# SC_Identification
Input: compound 
<br/>   (type:str) (chemical composition - A<sub>x</sub>B<sub>y</sub>C<sub>z</sub>)

Compound is classified as either a Superconductor or non-superconductor using a trained xgboost Classifier.

If the compound is a superconductor,
1. Critical Temperature is predicted
2. Cross referenced with the existing superconductor database (Supercon) to check if its a known super conductor or not.



NOTE: 

For CLASSIFICATION_POSTIVES.csv file, check this link 
https://drive.google.com/file/d/10-8bFUfOssDiezEj3Ml3HzFGP6ojRG3l/view?usp=sharing
(file is larger than 25mb)
