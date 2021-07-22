# Epithelial-folding-at-Segment-Boundaries
Here is the repository for the manuscript titled "Pinching and pushing:  fold formation at the *Drosophila* segment boundary". Here, we are simulating the fold formation at the T1-T2 segment boundaries that occurs during late stages of Drosophila embryogenesis. We simulate a cross-section of T1-T2 segment using Surface Evolver. Here, the force file and parameters were adapted and modified from  https://github.com/BanerjeeLab/AAVM

# Authors
  Vijay Kumar Naidu Velagala (vvelagal@nd.edu)

 # System Requirements 
 To run this code, you need to download Surface Evolver from http://facstaff.susqu.edu/brakke/evolver/evolver.html
 
 # Running the simulation
 
   "Wildtype.fe" is the surface evolver file that contains the geometry for the T1-T2 cross-section, and the tensions for apical,basal and lateral sides. 
    This file will simulate the fold formation at T1-T2 segments in a wild type embryo. <br> <br>
   "Hhoverexpression.fe" is the surface evolver file for simulating the fold formation in a T1-T2 cross-section for Hh overexpression embryo.<br><br>
   "parameter.inp" file contains the values of the parameters.<br><br>
   "Forcefile.secmd" contains the commands that apply horizontal forces on the T2 segment and dynamically evolve the system.<br> <br>
    To run the simulation, you need to update the folder in the output variable in the "Forcefile.secmd". <br> <br>
    After updating the output folder, simulations can be run  by double clicking on the .fe files in Windows. <br> <br>
   
  
   Parameters | Value
------------ | -------------
Lenght scale | Content from cell 2
Force scale | Content in the second column
Viscosity   | 
 
