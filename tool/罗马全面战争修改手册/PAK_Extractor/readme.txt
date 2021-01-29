Pak extractor
version 0.25
made by Vercingetorix, email: pauldls@hotmail.com
to run copy xpak.bat and xpak.exe to your data\packs folder and run xpak.bat
that's all there is to it!

---------------
--Update List--
---------------


(v0.25)---------
Second release
Added repacking support, bugs fixed.
---------------

(v0.2b)---------
Beta release
Added repacking support.
---------------

(v0.1)---------
First release
---------------


---------------------
--Program Arguments--
---------------------

-mkdir 	: The way the program works is it creates the dirs for the file seperatly from when it actually extracts the files
	  If you have not already created the dirs that the pak file needs, run the program with this option.
-v	: Shows more details such as the current file it is extracting etc. good for debugging.

-pf	: Pack File, option to pack a file. The filename of the control file MUST follow this command.


-----------------------
--How to create a pak--
-----------------------

Create a text file, on the first line write the name of the new pak file you wish to create. 
Each line after that list the name and absolute or relitive path of the filename, 
somewhere in the path you MUST have a data folder as all files are stored relitive to the data folder.
Run xpak with the "-pf" argument followed by the name of your new text file. See the sample.zip if you are unclear on the process.