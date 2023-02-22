# Msweep
![Msweep_Banner](https://github.com/Runningtarrens/Msweep/blob/main/pics/Msweep%20banner.JPG)

A Repo for the Magnetic case of the Sweep keyboard



![Msweep_1](https://github.com/Runningtarrens/Msweep/blob/main/pics/PXL_20230216_123414472.jpg)


Content:

* Preface
* The case
* Bill of Materials
* How to print
* Files
* Tangented
* More Pics
* Legend
* License

# Preface

If you build a lot of keyboards or repair them, you know the hassle of having to open the cases, screw/ unscrew and taking apart the whole thing everytime you need to reflow a solder point, an led or maybe even just reset the MCU. Also for any sweep build youll need to have alot of screws and a few standoffs just keep the halfs together. With the Msweep you dont need to unscrew anything to access the PCB or any screw or standoff to use this case. In other magnetic cases i used to embedd the magnets in the print. That brought some problems with it, that made the process really strenuous. So now the magnets get glued into the case. But because of the postion of the magnets, you only see them if you pull the halfs apart or look at the bottom of the case, because the Case supports magnetic tenting legs and has magnets on the bottom of the case.

Feel free to join the Discord Server, if you have questions about the case or just want to have a chat: https://discord.gg/TRQFN7fyU5


# The Case

![Msweep_2](https://github.com/Runningtarrens/Msweep/blob/main/pics/PXL_20230222_173008931.jpg)
![Msweep_3](https://github.com/Runningtarrens/Msweep/blob/main/pics/PXL_20230222_173025124.jpg)
![Msweep_4](https://github.com/Runningtarrens/Msweep/blob/main/pics/PXL_20230222_173233067.jpg)

# Bill of Materials

To print this case youll need:
* about 115 gramms of Filament
* 24 Neodymium Magnets (10mm x 2mm x 2mm)
*  (Optional) 4 Neodymium Magnets round (10mm x 1mm)
*  Strong glue for the magnets

# How to print
 
 I always print in PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with. The printer and your settings for ASA and ABS must be on point so that the magnet pockets will be in the correct size. I recommend PLA because it has the best surface finish and is super easy to work with, any printer can print it.

## Slicing

### Settings for the Print:

* 0.20 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp

### Getting the magnets in

Here is where the Msweep differs from the Mcorne cases. The Magnets are not embedded in the print anymore. That has a few upsides.
* The print doesnt need to be stopped mid print
  That allows more printers to run the Gcode, because some models dont have the M600 command to pause the print automatically.
  There is no problem with the fitting of the magnets, the pockets are bigger and wider, which helps with tolerances.
  The pausing of the print brings discoluration of the filament, because for a while the filament gets cooked in the Hotend.
  You dont need to stick around the printer for the hole time to put the magnets in when the printer halts.
 * Stronger magnetic force holding the halfs together
 * No more play between the halfs because of the plastic that seperates the magnets.


### Top
The print is pretty straight forward. Only little thing that needs to be done is adding a bit of support for the front edge because there is a overhang with a curve, and you cant print curves in the air. So it needs support on this spot. If you want to make the top finish extra nice you can iron it or just reduce the flow for the toplayer to about 91%.
![MagneticCorne5](https://github.com/Runningtarrens/Msweep/blob/main/pics/top%20slicer.JPG)



### Bottom

Only thing to thing about here is the reduced flow or the ironing for the toplayer. because its the mate area for the top part. So setting the toplayer extrusion to 91% or just iron the last layer goes along way.

![Msweep_6](https://github.com/Runningtarrens/Msweep/blob/main/pics/bot%20slicer.JPG)


### Gluing of the magnets



#### Overview of the Part.

![Msweep_7]()

#### First pause for the round magnets needed for the tenting

![Msweep_8]()


#### Second pause to change the filament (different colour)

![Msweep_9]()


#### Third pause for the magnets to close the case

![Msweep_10]()


### Tenting Legs

![MagneticTentingLegs]()

Print 4 of them upright. But you need a prim to have enough surface that sticks to the build plate or it will get loose while printing.




# Files

## latest files

* corne split_bot_rechts_v4.stl
* corne split_top_right_reinforced_tentless_v4.stl
* corne split_top_right_reinforced_v4.stl
* magnet_tenting_30mm.stl

Version v4 is the latest for the case. I made some corrections so the inner keys ( T and Z dont scratch on the case).
I only uploaded the right side as .stl but you can just mirror it in your slicer software to get the left version of it. 


The .stl are to slice yourself. (There are also .3mf files which are already dialed in and provide the exact settings i use.).
The .3mf are in rework for now.


# Tangented

* Magnetic tenting legs - Added to the files directory
* Msweep Travel Case - big maybe
* Msweep alu version - big maybe





# More Pics

![MagneticCornegif1]()
![MagneticCornegif2]()


#### Bottom

![MagneticCorne11]()


#### Top underside

![MagneticCorne12]()


#### Top upside

![MagneticCorne13]()


#### USB Port

![MagneticCorne14]()


#### TRS Port

![MagneticCorne15]()


#### Detail view 

![MagneticCorne16]()


#### Detail view close up

![MagneticCorne17]()


# Legend

* MCU = Microcontroller unit

# License

Print and modify all you want, but please dont sell my desgin (digital or printed).
