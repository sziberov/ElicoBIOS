#Loader look like AwardBIOS - ElicoBIOS.

##It supports:
####1. Grayscale and colour monitors

####2. Basic settings system (Open startup file and scroll to "--BIOS SETUP" line)

####3. Password 

####4. Animated and static splash screen, also EPA logo on POST screen

####5. Device listing (System Configurations screen)

####6. Basic bootloader without sandboxing (Sorry, i don't kow how to add it)

####7. Missing of any of core files, or .Elico folder

####8. Blocking Ctrl+T. It means you can't terminate BIOS while it booting

####9. Something else about what i maybe forgot :D

##Adding your OS to bootloader:

####Open .Elico folder > Open "initrd" file with your favourite text editor > Add a new (blank, thank you Cap) string with pressing "Enter ↵" key > Then write something looks like this:
>TestOSName;testosloaderfile

####[WARING: Do not add more than you need new strings! Else you get error in bootloader.]

##Screenshots:
<a target="_blank" href="http://itmages.ru/image/view/2779095/d91d16c6"><img src="http://storage3.static.itmages.ru/i/15/0719/s_1437347506_9735670_d91d16c6df.png" /></a>
<a target="_blank" href="http://itmages.ru/image/view/2779094/3dc7747f"><img src="http://storage3.static.itmages.ru/i/15/0719/s_1437347506_1277453_3dc7747f6c.png" /></a>
<a target="_blank" href="http://itmages.ru/image/view/2779096/c4577b6b"><img src="http://storage4.static.itmages.ru/i/15/0719/s_1437347507_3487485_c4577b6b37.png" /></a>
<a target="_blank" href="http://itmages.ru/image/view/2779093/b92e933a"><img src="http://storage3.static.itmages.ru/i/15/0719/s_1437347506_7019229_b92e933a97.png" /></a>

##Special thanks to:
####DomanoSV for original ElectronusBIOS and cool idea
####The_Pie for downloading and test my first'est version of this loader
####;)
