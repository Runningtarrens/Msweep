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

If you build a lot of keyboards or repair them, you know the hassle of having to open the cases, screw/ unscrew and taking apart the whole thing everytime you need to reflow a solder point, an led or maybe even just reset the MCU. Also for any sweep build youll need to have alot of screws and a few standoffs just keep the halfs together. With the Msweep you dont need to unscrew anything to access the PCB or any screw or standoff to use this case. The Case supports magnetic tenting legs.

Feel free to join the Discord Server, if you have questions about the case or just want to have a chat: https://discord.gg/TRQFN7fyU5


# The Case

![MagneticCorne2]()
![MagneticCorne3]()
![MagneticCorne4]()

# Bill of Materials

To print this case youll need:
* about 120 gramms of Filament
* 16 Neodymium Magnets (14mm x 4mm x 2,5mm)
*  (Optional) 4 Neodymium Magnets round (10mm x 1mm)

# How to print
 
 I always print in PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with, because if you want to put the magnets in, you have to open the enclosure and might be having problems with warping or cracked prints because of that.

## Slicing

### Settings for the Print:

* 0.10 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp

### Getting the magnets in

To get the magnets in, the M600 command is used. The printer makes a pause. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to each other and dont repel each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is.

### Top
The print is paused on the top half after the 42 layer or 4.2mm hight.
![MagneticCorne5]()


#### Position of the Pockets for the Magnets
![MagneticCorne6]()



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting and a transparent basis, 3 pauses. 2 to get the magnets in and 1 to just change the filament. If you dont want magnetic tenting and dont want another colour for the top part, youll only need one pause for the magnets.

#### Overview of the Part.

![MagneticCorne7]()

#### First pause for the round magnets needed for the tenting

![MagneticCorne8]()


#### Second pause to change the filament (different colour)

![MagneticCorne9]()


#### Third pause for the magnets to close the case

![MagneticCorne10]()


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
