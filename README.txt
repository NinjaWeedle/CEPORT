CEPORT - An on-calc utility for porting your 83+/84+ TI-BASIC programs to the CSE/CE

This program will convert a TI-BASIC program made for the monochrome 83+/84+ to the TI-84+ CE.
I HIGHLY reccommend backing up your program before converting- Use at your own risk!

Only correctly formatted Text( commands will be converted.

Also, this doesn't work right if on the same line you have a Text command followed by more text commands on the same line separated by ":", as only the first Text command on a line is modified.

COMMANDS THAT ARE MODIFIED:

Text( (Including large font)
Pxl-On(
Pxl-Off(
Pxl-Change(
Pxl-Test(

REQUIREMENTS:

Celtic III MUST be installed!
The program you want to convert must be in RAM and unlocked.



Str0 - Stores the program name
Str1 - stores the contents current program line being read
G - The current line being read
F - The total number of lines in the program being read.
A- Location of first comma in string
B- Location of second comma in string
Str2 - Xcoordinate
Str3 - Y coordinate

10/2/2021 Oxiti8.
