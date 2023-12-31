# TLDR
This base file is setup in the format so that you can declare all necessary variables to run AMR-Wind in one file, and by running the "base\_file\_transform" code you can generate the needed 3 input files (Spinup, Precursor, and Turbines) to run AMR-Wind. To use the transformation code, you MUST change the output\_folder variable to the location of your base file alongside changing the precursor\_file\_name to match that of your base file name. Both these variables are at the very top of the transformation code. Then simply run the code (I used VScode).

The code is divided into three sections: Spinup, Precursor, and Turbines with each section being defined by a semicolon. Please DO NOT delete these semicolon comments as they provide the premise for transforming the base file. If you wish to run the "Error Checker" code it will ensure the variables the user has defined match with the type declared in the commented brackets. Please DO NOT delete these brackets if you wish to error check your code. Please see the bottom of this file if there is anymore AMR-Wind variables you would like to add to the code. They have been formatted to simply be able to copy and paste the currently commented out variable into your desired section of the base file.

Please see the tutorial file for a more in-depth explanation.

This code was developed by myself as a part of an internship with NREL's Wind Energy Science group with mentorship from Ashesh Sharma through the GEM fellowship. Any questions can be direcred to sydrich@stanford.edu as I will no longer access my NREL email.
