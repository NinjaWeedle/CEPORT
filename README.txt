CEPORT CE 1.0 - An on-calc utility for for porting monochrome 83+/84+ TI-BASIC programs to the CSE/CE

This program will convert a TI-BASIC program made for the monochrome 83+/84+ to look correct on a TI-84+ CSE and TI-84+ CE.

This is a port of CEPORT to the CE. It will not run correctly on monochrome calcs, the TI-84 Plus CE Silver Edition, or on CEs with OS 5.2 or lower.

HOW TO USE:
1. Install Celtic CE. To get it, go here: bit.ly/CelticCE
2. Open CEPORTCE.

You'll then need to enter the name of the program you want to convert. Once you've entered it, press enter. After that, just wait for the conversion to complete- The number in the bottom left represents the percentage of the conversion completed.


Only correctly formatted Text( and Pxl commands will be converted. (Correctly formatted meaning having both X and Y coordinates and having Text( or one of the Pxl commands being the first token on a line)


COMMANDS THAT ARE MODIFIED:

Text( (Including the large font variation that uses -1) - Now the conversions are even smaller!
Pxl-On(
Pxl-Off(
Pxl-Change(
Pxl-Test(

REQUIREMENTS:

Celtic CE MUST be installed for automatic conversion!
The program you want to convert must be in RAM and unlocked. Attempting to convert archived programs may result in a crash!


WARNING: With assembly libraries, there is always a small chance of a crash occuring. If you want to be safe, back up the program you want to convert to a computer before you run CEPORTCE.

2022 Oxiti8.
