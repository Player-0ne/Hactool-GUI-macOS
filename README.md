# Hactool-GUI-macOS
Applescript application GUI shell user friendly for hactool utility.

Multiple unpaking files:
NSP (Ninendo Submission Package)
NCA (Nintendo Content Archive)
XCI (GameCard Image)

You need the hacktool utility itself.
The latest compiled version is in the program resources (Hactool/Resources/hactool). 
You must put the Hactool program in the Application folder so that the paths work automatically.

You need (Nintendo Switch) keys (prod.keys, title.keys, tsec_keys.bin) for Hactool to work nca unpaking.
Use LockpickRCM payload and Lockpick homebrew for dumping this keys.
The keys must be in the folder /user/.switch/prod.keys, title.keys, tsec_keys.bin
If you do not have such a folder, create and put the keys there.
Attention, the switch folder starts with a dot, so it is hidden!
Do not change the key file names!

If you want to use the Hactool (GUI) from anywhere, 
you should transfer the hactool utility from the  Hactool/Resources/hactool to /usr/bin/hactool
Also need in Hactool/Resources/Scripts/main.scpt swap the commenting of these lines

#property hactool : "/Applications/Hactool.app/Contents/Resources/hactool"
property hactool : "hactool"

P.S.
I am not the author of hactool. My application is just a shell for this utility.
Link to the original hactool utility. by SciresM - https://github.com/SciresM/hactool 

P.S.P.
I checked the unpacking of all firmware files from 1.0.0 to 8.1.0 and everything works. 
I did not have the patience to unpack manually before that...
