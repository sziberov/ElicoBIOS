#Loader look like AwardBIOS.

##It supports:
####1. Grayscale and colour monitors

####2. Basic settings system (Open startup file and scroll to "--BIOS SETUP" line)

####3. Password 

####4. Animated and static splash screen, also EPA logo on POST screen

####5. Device listing (System Configurations screen)

####6. Basic bootloader without sandboxing (Sorry, i don't kow how to add it)

####7. Missing of any of core files, or .Elico folder

####8. Something else about what i maybe forgot :D

##Adding your OS to bootloader:

####Open .Elico folder > Open "initrd" file with your favourite text editor > Add a new string with pressing "Enter ↵" key > Then write something looks like this:
>TestOSName;testosloaderfile

####[WARING: Do not add more than you need new strins! Else you get error in bootloader.]
