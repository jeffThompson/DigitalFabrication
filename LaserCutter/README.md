# LASER CUTTER

* [Machine details](#machine-details)  
* [Safe materials](#safe-materials)  
* [Prep your file for cutting](#prep-your-file-for-cutting)  
* [Send your file to ULS](#send-your-file-to-uls)  
* [Manually set the Z-height](#manually-set-the-z-height)  
* [Materials settings](#materials-settings)  
* [Cut it out!](#cut-it-out)  
* [Alternative machines](#alternative-machines)  
* [Other resources](#other-resources)  

- - -

### MACHINE DETAILS

| Make  | Universal |
| :---- | :----- |
| Model |  |
| Software | Illustrator, Acrobat, ULS (Windows only) |
| Max width | `24 inches` |
| Max height | `18 inches` |

- - -

### SAFE MATERIALS  
The laser cutter is definitely the most dangerous tool in the Fab Lab and requires careful attention when running it. Aside from the risk of fire, the choice of materials is really crucial. You're not actually cutting, but burning through the material!

**THINGS YOU *CAN* CUT**  
* Anything stocked by the Fab Lab  
* Anything listed on the Laser Cutter Materials Database (student-purchased materials still require faculty approval) 
* Acrylic (cast is better than extruded)  
* Paper, matboard, chipboard, and corrugated cardboard  
* Plywood, bamboo, solid wood, and cork  
* 100% cotton fabric  
* Craft felt (the synthetic stuff, which is acrylic)  
* Leather (but it's stinky!)  
* Laser-friendly rubber stamp material  
* EVA/craft foam  

**THINGS YOU CAN ENGRAVE (BUT NOT CUT)**  
* DuraBlack  
* Stone  
* Glass  
* Steel/stainless with Cermark or other marking fluid applied  

**THINGS YOU *CANNOT* CUT**  
* Materials you purchased but that haven't been approved by a VA&T faculty member  
* Acrylic that doesn't say "acrylic" on the paper coating  
* Acrylic that has a plastic film on it (can be removed and optionally replaced with transfer tape)    
* PVC plastic  
* Mystery plastics of any kind  
* Material that is warped  

Why is this so important? Take PVC as an example: this is a plastic commonly used in plumbing and is quite cheap. But the "C" in PVC stands for chloride. If you cut it with the laser, PVC releases chlorine gas – essentially a chemical weapon that can literally kill you! Other plastics release gasses that can melt the inside of the laser cutter or do other really bad things. 

**No materials can be cut or engraved unless either purchased from the Fab Lab or approved by a VA&T faculty member – no exceptions!** 

- - -

### PREP YOUR FILE FOR CUTTING  
Before we can cut anything, we have to be sure the file is ready to go.

**OUTLINE TEXT, OVERLAPPING SHAPES**  
Like the vinyl cutter, the laser cutter can't handle text that hasn't been converted to outlines. It will also cut all the way around overallaping shapes. See the `VinylCutter` folder for more info on fixing this.

**COLOR MODE!**  
The laser cutter relies on the color of your shapes to determine if something should be cut or engraved. It's really picky about this, so it is important to make sure everything is correct.

* Go to `File > Document color mode...` and be sure `RGB` is selected  
* Cut: select all shapes that are to be cut and change their stroke to `rgb(255, 0, 0)`. It's a good idea to remove fill color too  
* Vector engrave: select these shapes and set their stroke to `rgb(0, 0, 255)`  
* Raster engrave: anything *not* following the settings above will be seen as raster engraving... even a line that's `rgb(254, 0, 0)`! Generally, set the fill color to a grayscale value for raster engraving: `0` = darkest, `255` = no engraving  

**STROKE WEIGHT**  
The last thing we need to do is change the stroke weight of our lines to `0.001 inches` (this will auto-change to be in points). Weirdly, anything thicker will fail. This makes your artwork really tough to see, so do this right before cutting!  

**FILE EXPORT**  
When done, go to `File > Save as...` and save a copy of your file as a `PDF`. I like to append `YourFilename-CUT.pdf` to files that are ready to cut so it's easy to tell the difference.  

- - -

### SEND YOUR FILE TO ULS  
Once exported as a `PDF`, transfer your file to the laser cutter computer. Open it in Adobe Acrobat. The laser software, ULS, appears like a printer to Acrobat.

* `File > Print...`  
* Be sure `VLS4.0/6.0` is selected as the printer (should be the default)  
* Hit `Print` (don't worry, it won't cut yet!)  
* Click the little red diamond logo to open ULS  

You should see your file show up!

- - -

### MANUALLY SET THE Z HEIGHT  

\[ coming soon \]


- - -

### MATERIALS SETTINGS  
The type and thickness of material will change how well the laser cuts considerably. We've tried to simplify this as much as possible for you!

**ONLINE MATERIALS DATABASE**  
The easiest way to get your settings correct is to use our online materials database. Either bookmark the site and pull it up or scan the QR code posted right near the laser cutter! Find your material to see the settings you need to use.

Let's say you want to cut 1/8" black acrylic. The database tells us we need to...

* Set the material to `Plastic > Acrylic > Cast Acrylic, Deep Engraving`  
* Set the thickness to `0.118 inches` (or measure with a caliper)  
* Adjust the raster and vector engraving down by `-50%`  

Be sure to click `Apply`, close the materials window, then re-open it to double-check all your settings are correct.

> Note! Some materials require additional steps to be used. For example, clear acrylic has a film on it that can't be safely cut. You'll need to remove it and apply transfer tape instead. Be sure to read the entire materials page before cutting.

- - -

### CUT IT OUT!  
Now for the fun part – cutting something! 

Turn on the laser cutter, lay your material on the honeycomb bed, and close the lid. The laser will home itself and, when done, the play button in ULS will turn green. Adjust the position of your design to where you want it to be cut from.

**The next steps are super important for your safety and the workers in the Fab Lab!**

* Turn on the fume extractor  
* Turn on the air assist compressor  

You should be ready to cut: just hit the play button in the ULS software and off it goes! Be sure to stay by the machine the whole time it's cutting.

> A little flame is normal on some materials, but **if anything really catches fire, open the lid immediately!** This will usually put the fire out. If it doesn't either remove the part and stamp on it or spray it with the fire extinguisher! It's much better to make a huge mess than burn down the building.

When cutting is finished, let the fume extractor run for a few minutes before opening the lid – this allows all the nasty burned fumes to be removed.

- - -

### ALTERNATIVE MACHINES  
The laser cutter is by far the most expensive machine in the Fab Lab. New, with the filter unit and air assist, the machine cost about $30,000... definitely out of most people's budget! Unlike 3D printers, there haven't been nearly as many consumer-level laser cutters available until recently.

* Glowforge: the most popular "consumer" laser cutter. Works quite well and has a large community. Stuck with proprietary and cloud-based software to run the machine, not as powerful  
* There are a number of "diode" laser cutters on the market for really cheap. These are ok for really thin stuff and some engraving, but don't expect the results (or safety features) of a machine like ours  

- - -

### OTHER RESOURCES  
Find something useful? Please send it to me and I'll add it to the list!

