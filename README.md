# Ookami Data
Add translations for each line after the `=` sign.  
Line breaks are represented by a `|`.  
Comments can be added at the end of lines by using `#`.  
## wsb_input.txt
Main script file.  
The text is automatically wordwrapped, but a `|` can be used to force a line break.  
New textboxes can be added by appending `>>` followed by the new text.  
To blank out a line, use a single `!`. If just left empty, the line will be left untranslated.  
## dat_input.txt
Miscellaneous text used for item descriptions, rumors, etc.  
The text for the "goods.dat" file is automatically wordwrapped.  
## bin_input.txt
System text.  
Control codes are specified as `<XX>` or `UNK(XXXX)`, they should usually be kept.  
## images.txt
A list of text contained in the images in the work_IMG folder.  
## opening.ass
At the bottom of the file, the opening theme lyrics should be translated.  
If needed, use Aegisub to split or merge the lines.  
