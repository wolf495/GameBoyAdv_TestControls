# GameBoyAdv_TestControls
This project is me testing how to detect input on the Game Boy Advance. In this, 
I use the command 'gbacc hello -o hello.gba' to compile and create the hello.gba file. 
In order to run this file you need to install a GBA emulator, with the following 
'sudo apt-get install visualboyadvance visualboyadvance-gtk' and use command 'gvba program.gba'. 
In order to use './gbacc' correctly you need to extract the included tar file into your home directory, and change the 
gbacc file so that it points to where you extracted the tar (in gbacc, change the address at the top of the file).

When running the .gba file, the screen should change colors when holding/pressing the 'A' button.
