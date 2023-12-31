# ExaWind_AMR-Wind_Automation
This repository contains the script and directions needed to automatically generate AMR-Wind input files, ExaWind input files, and an AMR-Wind error checker. 

The AMR-Wind folder contains an example AMR Base File that can be edited to contain the contents of your choosing. This example file is based on Alex Rybchuk's amr-wind-tutorial (https://github.com/rybchuk/amr-wind-tutorial). Also in this folder is the tranformation code that takes the AMR base file and will automatically transform it into the needed Precursor, Spinup, and Turbine files to run AMR Wind. Lastly, there is an error checker script that takes the AMR Base File as an input and will check the decalred variables for valid variable types, declarations, and physics.

The ExaWind folder contains an example ExaWind Base File that can be edited to contain the contents of your choosing. The file contains all the necessary variables to generate the needed AMR-Wind and Nalu-Wind inputs files (of particluar use is the ability to generate as many Nalu turbine files as you desire automatically). This example file is based on Jon Rood's 16 turbine uniform inflow example (https://github.com/Exawind/exawind-cases/tree/main/16_turbs_uniform_inflow). Also in this folder is the transformation code that takes the ExaWind Base file and will automatically transform it into the needed AMR-Wind background flow file and n number of Nalu-Wind turbien files as declared by the user. There is an included file in this folder: a yaml error checker that is NOT functional but included for the sake of future use.

More detailed instructions for how to use the automation code is included in each the AMR-Wind and ExaWind folders.

In the Logistics Information folder you will find a document containin feedback from ExaWind stakeholders from interviews performed with various users/developers of the code. Included in this folder is also the final presentation for my (Sydney Richardson) GEM presentation.

This code was developed by myself as a part of an internship with NREL's Wind Energy Science group with mentorship from Ashesh Sharma through the GEM fellowship. Any questions can be direcred to sydrich@stanford.edu as I will no longer access my NREL email.
