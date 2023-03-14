# nano-vhdl
Syntax highlighting for VHDL files in Linux "nano" editor

## Setup
To add this syntax  highlighter for VHDL in nano you have to manually add this file in this directory  "/usr/share/nano" and then 
make sure that in "/etc/nanorc" the line "include "/usr/share/nano/*.nanorc" " is not commented out.
And that's it! :)

## Bug report
This is just an alpha version, i didn't add much things after all. All keywords have the same colour, and they are not divided into different
"groups". But even with these few things there can be some bugs (due to the fact that nano uses posix extended regular expressions, and i'm really not a pro in it XD ). So if you find any problem just open an issue.

## Next things to implement

TODO:

- [] --> Check if there are other things except keywords that has to be
       highlighted.
- [] --> Implement header and magic in the nanorc file
- [] --> I just coded every vhdl keyword to have the same color. Sort
       them into different groups, such as, control flows, data
       types, and so on and so forth, and map them with different
       colors.
- [] --> Add support for common imported libraries such as numeric_std
       and the one for std_logic.


