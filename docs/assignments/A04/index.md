# A4 – Motor Mount

## Objective

My objective for this assignment was to design a motor mount in order to fit a specific make and model with a given set of values. These values that were provided were an applied force, a max deflection and the choice of what material we could use between ABS, PLA and PETG.This design was intended to mount to a wall and we are supposed to obtain two sets of directions one being obtained through stress calculations and the other through deflection through the usage of beam calculations. All of the specs for the motor used can be found in the following link.

[Motor](https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100)


IMG OF MOTOR

Before I could start designing the mount, I had to first understand what it was that we knew and what we did not know including the dimensions of the motor, the specific design requirements, and all data I would need for the first stages of the design process.

IMG OF KNOWNS/UNKNOWNS AND DIMENSIONS


## Material

For the next part of this design process, I had to decide which material I was going to use. I ended up choosing pla due to its common usage and my personal experience with it from 3D printing in the past. It was then that I had to get all of the necessary data that I needed about PLA.

IMG of material specification


## Feature 1:


The Next Step was to design feature one and the best way to start this process was to figure out what future one was defined as and then listing my knowns and unknowns. A step that I struggled with was assembling all of the information I needed in my knowns and unknowns without leaving out any valuable information that would lead me stranded in the middle of my calculations. Furthermore, I needed to gather all of the formulas I would need in order to find the specifications for my motor mount design. It is important to point out that because I'm dealing with so many different variables and values, I color coded some of my needed values in order to be able to keep track with them in my calculations. 

 IMG of feature one knowns and unknowns

After that, I now had to do the calculations of the maximum stress that would be used throughout the designing process and would allow me to make a functioning product. In order to do this I had to draw a free body diagram and use Statics in order to find the moment about point A.

 IMG of Max stress calculation.

Then the next objective was to calculate my thicknesses that would be required through stress and then through the beam calculations to find the overall deflection and having to pick the highest number for my design. four feature one, the value that was given from the stress calculations was considerably higher at 6.866 mm and so that was the value that I chose for my design. After reflecting, I believe my number was higher than it should have been however I believe this is within the specifications and if anything is an overbuilt design that would allow for even higher stresses later on.

 IMG of stress and deflection calculation


## Feature 2:

The steps I took next was repeating the process for feature two and I followed the same process of laying out my knowns and unknowns with all of my values and drawing quick diagrams to show what it is that I am looking for. I did color code some of the values with highlighters but I ran out of highlighter colors so only some of them are highlighted. The difference from feature two is now that my value of Maximum stress is now known and will be directly used in the design of feature too as it carried over in the overall design. Some of the values of the length and the height were sourced from the specifications of the motor as found on its description found within the link.

 I am G of feature 2 knowns and unknowns

The Next Step was to build a free body diagram for feature two using the values that I just assembled and to solve for the moment in order to find the value of M that will be used later in different calculations. I also labeled the legend to describe when I'm drawing the section of the bolt holes in my free body diagram. and in order to speed up the process. I then immediately did my stress and deflection calculations using all of the data I had found previously or calculated in earlier parts of the project.The values that I found was that once again my stress calculations yielded the higher value of thickness required at 2.017 mm and so that would be the value that I would use in my final design.

 I am G of feature two fbd 


## Motor Mount Design Examples:


[Example 1](https://precisionminidrives.com/product/775-dc-gear-motor-mounting-bracket-motor-support?srsltid=AfmBOopDAGQu6ZGF1moe9sg8FswtrIbcBz8fo9UzMAghPeHabTPO0Obzm_w)

[Example 2](https://www.adafruit.com/product/3768?gad_source=1&gad_campaignid=23986111167&gbraid=0AAAAADx9JvRRgqn9DklutgonvpDBwpN4l&gclid=CjwKCAjw_KjVBhAHEiwAnC0N9E5ewSFEmnOf72RYJtDUHxiMl5VA1omtXfcb4TMmtFLofkw_OeN2xRoCUjkQAvD_BwE)


## Isometric Drawing:

I then decided I had enough info to create a basic idea of my design so I hand drew my design that was inspired by the real world examples while using my previously calculated values onto my isometric drawing in order to have a “blueprint” to go off of in my cad file.

 image of hand isometric drawing


## Designing the Motor Mount in CAD:

The first step that I chose to go with was setting up parametric equations. as dealing with decimal values that are repeated throughout a design, things can fall through the cracks of accidentally typing the wrong value and it breaking the overall design and compromising the capabilities of the product. In order to prevent this, I use parametric equations within SolidWorks to assign values to my variables in order to make sure that every time I input a dimension, it was the correct value. 


img of parametric equ

To start with my cad file, I first started with drawing the base shape which is a rectangle with the values of 22mm x 27mm which would be the overall size of feature 2 and thought it would allow me to design feature one onto the base sketch.However, I had quickly realized that that would not work because it would affect my overall dimensions. so I quickly resolve this by setting my values to have the dimension being 22 mm x 36 mm as shown in the photos below.


img of both base shape in cad


Now that I had created the correct base shape, I extruded it to the thickness of T1 which was the exact specification as shown in my isometric drawing and would still allow me to add on feature one with no geometric issues.

img of base shape extrude


Next, I created the sketch and Extrusion of feature 2 following a similar process but this time it was faster due to having the correct values the first time. The next step at this point was to add the holes that needed to be created for the bolts, the motor shaft, and part of the motor's body in order to properly hold  the motor in place.This process then brought me to my final CAD design with all of the dimensions and whole set correctly, I was able to now view my final design.


IMG of final cad screenshots


## For 2157 Students Only

OBJ of this

SCREENSHOT of Drawing


## CAD and CAD drawing files:

[CAD file prt](https://drive.google.com/file/d/1vM9VJzkDtmBzuUNNXA8B0ROEej74tE4E/view?usp=sharing)

[Cad Drawing PDF](https://drive.google.com/file/d/1zYtGpBHpB_I4HC7vPlGN7qB_vPW_ufTi/view?usp=sharing)

## Lessons Learned



## Time Spent

This assignment took me about 5 hours
