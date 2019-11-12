# SC_Identification
Input: compound 
<br/>   (type:str) (chemical composition - A<sub>x</sub>B<sub>y</sub>C<sub>z</sub>)

Compound is classified as either a Superconductor or non-superconductor using a trained xgboost Classifier.

If the compound is a superconductor,
1. Critical Temperature is predicted
2. Cross referenced with the existing superconductor database (Supercon) to check if its a known super conductor or not.
