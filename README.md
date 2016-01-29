#Loader look like AwardBIOS - ElicoBIOS.

##It supports:
####1. Grayscale and colour monitors

####2. Settings system (Open .Elico folder > Open "Cmos" file with any Text Editor > Edit settings > Save)

####3. Password 

####4. Animated and static splash screen, also EPA logo on POST screen

####5. Device listing (System Configurations screen)

####6. Basic bootloader without sandboxing (Sorry, i don't know how to add it). It supports up to 12 items for your OS's or programs, and 13'th item for disk

####7. Missing of any of core files, or .Elico folder

####8. Blocking Ctrl+T. It means you can't terminate BIOS while it booting

####9. Something else about what I maybe forgot :D

##Adding your OS to bootloader:

####Open .Elico folder > Open "initrd" file with your favourite text editor > Add a new (blank, thank you Cap) string with pressing "Enter ↵" key > Then write something looks like this:
>TestOSName;testosloaderfile

####[WARING: Do not add more than you need new strings! Else you get error in bootloader.]

##Screenshots:
####Enter password:
<a target="_blank" href="http://itmages.ru/image/view/2806852/20862d4c"><img src="http://storage2.static.itmages.ru/i/15/0726/h_1437910432_3652964_20862d4c2c.png" /></a>
####If you entered incorrect password:
<a target="_blank" href="http://itmages.ru/image/view/2806853/74dee43f"><img src="http://storage2.static.itmages.ru/i/15/0726/h_1437910432_5241722_74dee43fc1.png" /></a>
####Static splash screen:
<a target="_blank" href="http://itmages.ru/image/view/2806856/945f5fdf"><img src="http://storage4.static.itmages.ru/i/15/0726/h_1437910433_3880244_945f5fdf9f.png" /></a>
####Animated splash screen:
<a target="_blank" href="http://itmages.ru/image/view/2779095/d91d16c6"><img src="http://storage3.static.itmages.ru/i/15/0719/h_1437347506_9735670_d91d16c6df.png" /></a>
####POST screen:
<a target="_blank" href="http://itmages.ru/image/view/2779094/3dc7747f"><img src="http://storage3.static.itmages.ru/i/15/0719/h_1437347506_1277453_3dc7747f6c.png" /></a>
####CMOS checksum error. This happens if Cmos file is missing:
<a target="_blank" href="http://itmages.com/image/view/2782144/c891e65f"><img src="http://storage3.static.itmages.com/i/15/0720/h_1437406448_4814435_c891e65f98.png" /></a>
####System Configurations screen:
<a target="_blank" href="http://itmages.ru/image/view/2779096/c4577b6b"><img src="http://storage4.static.itmages.ru/i/15/0719/h_1437347507_3487485_c4577b6b37.png" /></a>
####BootLoader:
<a target="_blank" href="http://itmages.ru/image/view/2779093/b92e933a"><img src="http://storage3.static.itmages.ru/i/15/0719/h_1437347506_7019229_b92e933a97.png" /></a>
####BootLoader with disk inserted:
<a target="_blank" href="http://itmages.ru/image/view/2782790/7f515b4b"><img src="http://storage2.static.itmages.ru/i/15/0720/h_1437419587_5307582_7f515b4bba.png" /></a>
####If you have many OS'es in initrd and disk inserted:
<a target="_blank" href="http://itmages.ru/image/view/2806854/0c4730a5"><img src="http://storage2.static.itmages.ru/i/15/0726/h_1437910432_5962023_0c4730a5de.png" /></a>

##Special thanks to:
####[DomanoSV] (https://github.com/DomanoSV) for original ElectronusBIOS and cool idea
####[The_Pie] (https://www.youtube.com/user/cybershadow0) for downloading and test my first'est version of this loader
####;)
