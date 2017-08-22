

# Electronics Production and CNC

Our aim in this section was to complete PCB milling and cutting and also to solder the PCB. Unfortunately we couln't accomplish this due to technical crisis.Anyway I have listed the basic knowledge we got through the course.

* Basic Information

1. [What is Electronics Production ?](http://www.radio-electronics.com/info/manufacture/)
Jaseel sir gave us a basic idea of what is done in Electronics production using the CNC (Computer Numerical Control Router).

2. What is CNC?
CNC router (Or Computer Numerical Control router) is a computer-controlled cutting machine related to the hand held router used for cutting various hard materials, such as wood, composites, aluminium, steel, plastics, and foams.
![GitHub Logo](/images/cncmachine.png)

Refer tutorial by [AJITH KUMAR M.G.](http://archive.fabacademy.org/archives/2017/fablabtrivandrum/students/155/week6.html)

* Some factual information

>In order to use the CNC, we must decide what kind and size of bit is required to do the said task.
![Bits](/images/bits.jpg)
The first two steps while working on a PCB are :
Tracing - For this we can use bit size of 1/64 inches.
Cutting - For this we can use bit size of 1/32 inches.

(While working on plywood, use a bit size of 1/4 inches.)

>Next thing to do is stick the PCB so that it stays firm. Take care so that the sacrificial layer is not damaged.

>Tip: Never work on the machine when it is turned on.

>Refer [this](http://www.shopbottools.com/ShopBotDocs/files/SBG%2000142%20User%20Guide%2020150317.pdf) since I can't provide more information

>The online tool available to use your design is [fabmodules](http://fabmodules.org/)
In order to do PCB milling using the CNC, we must provide the design in a format that can be read by the CNC machine.
This format is : <B>SBT File Format</B>

All you have to do after your design in png format is ready is , visit [fabmodules](http://fabmodules.org/)
Follow the steps given below.
![ec1](/images/ec1.png)

![ec2](/images/ec2.png)

![ec3](/images/ec3.png)

![ec4](/images/ec4.png)

![ec5](/images/ec5.png)
While setting the dimensions make sure it is in mm. 
Tip: Give negative value for bottom z dimension.

After you click save, the image in the required format is obtained.

>ShopBot 3 is the software used. This can be used to control the CNC 

![shopbot_software](/images/shopbot_software.jpg)






