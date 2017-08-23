# 3D PRINTING

This is where you can connect to the quote " You can make almost anything here ".

>What is 3D printing?

The action or process of making a physical object from a three-dimensional digital model, typically by laying down many thin layers of a material in succession.

## Softwares Required:

A few softwares were installed which would be useful in the fabrication lab. Some of the softwares that were told to be installed were:

* AutoCAD ( Ex. : EagleCAD, Rhinoceros)
It is used for creating blueprints for our designs in mind.

![FABLAB class](/images/autocad1.png)

* Cura 
It is a 3D printing slicing application. This is the software that is used to turn our design image into a format that can be used by the 3D printer to print the corresponding 3D object. 
![FABLAB class](/images/curascreen1.png)

## My Assignment

I tried to design a ear phone holder using AutoCad and then 3D prited it using the 3D printer.


![3d printing](/images/3d1.jpg)                                                             ![3d printing](/images/3d2.jpg)

![3d printing](/images/3d3.jpg)

## How to 3D print ?

* STEP 1

First of all you need to design the prototype using any of the appropriate softwares such as Rhinoceros, Adobe Illustrator, Solidworks etc. Why do you have to use the specific softwares ? Well you are going to turn your 2D design to a  3D model , Aren't you? This 2D image must be readable by the 3D printer. This format is the Gcode. 

So the first step is to design the image using any  appropriate software and then save the image in stl format.

>What is G-code?
GCode is the generic name for a control language for CNC (or Reprap) machines. It is a way for you to tell the machine to move to various points at a desired speed, control the spindle speed, turn on and off various coolants, and all sorts of other things. It is fairly standard, and is a useful tool.

Here, I'll show you my design for the ear phone holder using Rhinoceros.
You can download the file in STL format [here](http://liyanafzl.github.io/headset_al_stl.stl)

![3d printing](/images/3dscreen1.png)

After you are done designing, save the file in STL format.

![3d printing](/images/3dscreen2.png)


Now you need to convert this STL file to Gcode. This can be done using the Cura software.

The Cura tell us how much time it would take to print the object. Also we can specify the quality needed for the object ( 20%, 50%, 100% etc) depending on the strength required for the design. Supports need to be generated if necessary. That needs to be specified. After printing , these supports can be removed easily.

![3d printing](/images/3dscreen3.png)

![3d printing](/images/3dscreen4.png)

Now your Gcode file is ready to be fed to the 3D printer. Save it in the memory card that can be inserted into the 3D printer.

![3d printing](/images/3d4.jpg)

Now just rotate the button and select the file.

![3d printing](/images/3d5.jpg)

Print : to select the file from the memory card
Material : to specify what kind of material is loaded into the machine.
Maintainance: to change the setting on the machine regarding nozzle size, power used etc.

After the settings are done, the machine takes a while to start printing because the material has to get heated. Then you can see the 3D printer printing your 2D design layer by layer.

<video src="/images/3Dprinting.mp4" poster="3dposter.jpg" width="320" height="200" controls preload></video>

## File available for download

[Design for ear phone holder]((http://liyanafzl.github.io/headset_al_stl.stl)





