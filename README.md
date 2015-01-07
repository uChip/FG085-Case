Frequency Generator FG085 Case & Hack
=====================================

This repos contains a [design file](https://github.com/uChip/FG085-Case/blob/master/FuncGenhalfcase1.1.stl) for 3D-printing a case for the JYETech FG085 Frequency Generator kit.  The case uses the front panel and main board from [the kit](http://www.jyetech.com/Products/085/e085K.php).  For the back panel you can use the kit part or there is a design file for a laser cut acrylic back panel with cutouts for bringing the power and USB connectors out the back.  See the BOM file for laser cutting service sources.  

This case design is a variation of the general purpose electronic project case design I did for the [StdBx project](http://www.github.com/StdBx/Series100).  The case is assembled from two identical half-case pieces.  See the [BOM file]() for 3D print sources.  

Hacking the kit:  I mostly assembled the kit per the instructions, but to bring the connectors out the back of the case I did modify a couple of things.  I also used different spacers so as to make case assembly easier.  The spacers are the same height, but are female-female instead of female-male so that the screws can go through mounting tabs in the case.  

The first mod is to install a polarized 2-pin header instead of the included barrel jack connector.  There are holes in the PCB for a 0.1" header already placed so this is easy.  Then just use a panel-mount barrel jack connector (see BOM for part #) and a wire pig-tail back to the PCB power header (also in BOM).  

The second mod is to install a 4-pin header for the USB.  Again, the PCB is already layed out for the header.  My board has both the PCB-mount USB connector and the header.  On the back panel I used a panel mount ruggedized USB mini-B connector.  I had to make a little PCB to breakout the USB connector to a ribbon cable (OSH Park order number and Eagle board file included in BOM) which then runs back to the PCB USB header.  

If you are looking for replacement switches, I have found some that fit and work.  See the BOM file.  

STATUS: As the photos show this project is complete and working.  It went together without too much trouble but there are a couple of things I would change if I did it again.  I sized the channel in the case for the thickness of the back panel in the kit, but then had a new back panel laser cut from 1/16" acrylic.  The new panel is thinner than to one in the kit and therefore a bit more flimsy than I would like.  The one in the kit is just slightly thicker and stiffer and will fit the channel if you want to cut the connector holes yourself.  If I were to make another one, I would widen the channel and cut the back panel from 1/8" acrylic.  Also the back panel design is just a bit too long for the case channel.  Literally just a few seconds of sanding one end will make it fit smoothly, but if I were to make another one I would shorten the length just a little.  

LICENSE: You are free to use this information however you like, but no liability is accepted.  

