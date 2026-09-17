# A4 – Motor Mount

## Objective

My objective for this assignment was to design a motor mount in order to fit a specific make and model with a given set of values. These values that were provided were an applied force, a max deflection and the choice of what material we could use between ABS, PLA and PETG.This design was intended to mount to a wall and we are supposed to obtain two sets of directions one being obtained through stress calculations and the other through deflection through the usage of beam calculations. All of the specs for the motor used can be found in the following link.

[Motor](https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100)

<img width="160" height="160" alt="MOTOR PHOTO" src="https://github.com/user-attachments/assets/d364f6f6-247f-40d8-ab30-44574718be57" />


<img width="1625" height="505" alt="unnamed" src="https://github.com/user-attachments/assets/dcf87e10-0a1d-400d-a318-f4ce0ef09dfa" />


<img width="123" height="99" alt="download" src="https://github.com/user-attachments/assets/33a350f9-c9b9-481c-ad6f-6bf10b58824d" />


<img width="194" height="151" alt="download" src="https://github.com/user-attachments/assets/ace7b216-6f27-4898-8228-6a6f2fad4950" />


Before I could start designing the mount, I had to first understand what it was that we knew and what we did not know including the dimensions of the motor, the specific design requirements, and all data I would need for the first stages of the design process.


<img width="873" height="572" alt="image" src="https://github.com/user-attachments/assets/1e781668-6e1c-409d-b1e7-b2c5ae34c57e" />



## Material

For the next part of this design process, I had to decide which material I was going to use. I ended up choosing pla due to its common usage and my personal experience with it from 3D printing in the past. It was then that I had to get all of the necessary data that I needed about PLA.

<img width="702" height="347" alt="image" src="https://github.com/user-attachments/assets/152fa736-3136-4af4-99b0-09994ac13ad1" />



## Feature 1:


The next step was to design feature one and the best way to start this process was to figure out what future one was defined as and then listing my knowns and unknowns. A step that I struggled with was assembling all of the information I needed in my knowns and unknowns without leaving out any valuable information that would lead me stranded in the middle of my calculations. Furthermore, I needed to gather all of the formulas I would need in order to find the specifications for my motor mount design. It is important to point out that because I'm dealing with so many different variables and values, I color coded some of my needed values in order to be able to keep track with them in my calculations. 


<img width="883" height="527" alt="image" src="https://github.com/user-attachments/assets/557fe5db-ed5e-4149-a642-924efef528c6" />


After that, I now had to do the calculations of the maximum stress that would be used throughout the designing process and would allow me to make a functioning product. In order to do this I had to draw a free body diagram and use statics in order to find the moment about point A.


<img width="888" height="502" alt="image" src="https://github.com/user-attachments/assets/467260c3-7f6c-48b8-8fd1-92cfeb21634b" />



Then the next objective was to calculate my thicknesses that would be required through stress and then through the beam calculations to find the overall deflection and having to pick the highest number for my design. four feature one, the value that was given from the stress calculations was considerably higher at 6.866 mm and so that was the value that I chose for my design. After reflecting, I believe my number was higher than it should have been however I believe this is within the specifications and if anything is an overbuilt design that would allow for even higher stresses later on.


<img width="780" height="658" alt="image" src="https://github.com/user-attachments/assets/03d47040-19a8-4409-a326-dda6105afbe9" />


## Feature 2:

The steps I took next was repeating the process for feature two and I followed the same process of laying out my knowns and unknowns with all of my values and drawing quick diagrams to show what it is that I am looking for. I did color code some of the values with highlighters but I ran out of highlighter colors so only some of them are highlighted. The difference from feature two is now that my value of maximum stress is now known and will be directly used in the design of feature too as it carried over in the overall design. Some of the values of the length and the height were sourced from the specifications of the motor as found on its description found within the link.


 <img width="746" height="612" alt="image" src="https://github.com/user-attachments/assets/c8530f6f-69fe-4bef-aab2-7b6c75fde264" />



The following step was to build a free body diagram for feature two using the values that I just assembled and to solve for the moment in order to find the value of M that will be used later in different calculations. I also labeled the legend to describe when I'm drawing the section of the bolt holes in my free body diagram. and in order to speed up the process. I then immediately did my stress and deflection calculations using all of the data I had found previously or calculated in earlier parts of the project.The values that I found was that once again my stress calculations yielded the higher value of thickness required at 2.017 mm and so that would be the value that I would use in my final design.

 
<img width="772" height="607" alt="image" src="https://github.com/user-attachments/assets/6c5a318a-1258-4c31-9bb6-f513cea9dc6a" />


## Motor Mount Design Examples:


[Example 1](https://precisionminidrives.com/product/775-dc-gear-motor-mounting-bracket-motor-support?srsltid=AfmBOopDAGQu6ZGF1moe9sg8FswtrIbcBz8fo9UzMAghPeHabTPO0Obzm_w)

[Example 2](https://www.adafruit.com/product/3768?gad_source=1&gad_campaignid=23986111167&gbraid=0AAAAADx9JvRRgqn9DklutgonvpDBwpN4l&gclid=CjwKCAjw_KjVBhAHEiwAnC0N9E5ewSFEmnOf72RYJtDUHxiMl5VA1omtXfcb4TMmtFLofkw_OeN2xRoCUjkQAvD_BwE)


## Isometric Drawing:

I then decided I had enough info to create a basic idea of my design so I hand drew my design that was inspired by the real world examples while using my previously calculated values onto my isometric drawing in order to have a “blueprint” to go off of in my cad file.


<img width="745" height="613" alt="image" src="https://github.com/user-attachments/assets/c47d04d6-b87a-4b01-b507-f5bd7472a85b" />


## Designing the Motor Mount in CAD:

The first step that I chose to go with was setting up parametric equations to help the process go smoother. As I would be dealing with decimal values that are repeated throughout a design, things can fall through the cracks of accidentally typing the wrong value and it breaking the overall design and compromising the capabilities of the product. In order to prevent this, I use parametric equations within SolidWorks to assign values to my variables in order to make sure that every time I input a dimension, it was the correct value. 


<img width="927" height="428" alt="Screenshot 2026-09-16 195830" src="https://github.com/user-attachments/assets/69c11696-81b9-4105-84c6-484721d021e9" />



To start with my cad file, I first started with drawing the base shape which is a rectangle with the values of 22mm x 27mm which would be the overall size of feature 2 and thought it would allow me to design feature one onto the base sketch.However, I had quickly realized that that would not work because it would affect my overall dimensions. so I quickly resolve this by setting my values to have the dimension being 22 mm x 36 mm as shown in the photos below.


<img width="1745" height="605" alt="Screenshot 2026-09-16 170729" src="https://github.com/user-attachments/assets/5dcd0192-d436-4625-a7c2-91b51ee5c60f" />


<img width="470" height="598" alt="Screenshot 2026-09-16 195933" src="https://github.com/user-attachments/assets/416bf79b-a116-4c90-aea8-0064e6465178" />


Now that I had created the correct base shape, I extruded it to the thickness of T2 which was the exact specification as shown in my isometric drawing and would still allow me to add on feature one with no geometric issues.


<img width="1782" height="717" alt="Screenshot 2026-09-16 170617" src="https://github.com/user-attachments/assets/899590f4-e657-43de-9dc8-9b1e09922def" />


Next, I created the sketch and Extrusion of feature 2 following a similar process but this time it was faster due to having the correct values the first time. The next step at this point was to add the holes that needed to be created for the bolts, the motor shaft, and part of the motor's body in order to properly hold  the motor in place.This process then brought me to my final CAD design with all of the dimensions and whole set correctly, I was able to now view my final design.


<img width="1907" height="807" alt="Screenshot 2026-09-16 172847" src="https://github.com/user-attachments/assets/f7afcb7c-d7ef-4a18-b066-1f42057ecf3d" />


<img width="712" height="526" alt="Screenshot 2026-09-16 172944" src="https://github.com/user-attachments/assets/d7af401e-e701-4594-aa0f-563e75d8b54c" />


## For 2157 Students Only


As I am in MEGR 2157, we had an extra portion of this project we had to do. The extra portion we had to do was to create a drawing from our CAD part with dimensions and a third angle projection. I was also very careful to make sure that all hidden lines were shown so that anyone looking at this CAD drawing could understand how this part could be made and how it was designed. 


<img width="1022" height="723" alt="Screenshot 2026-09-16 175131" src="https://github.com/user-attachments/assets/36157e1c-3d82-489f-b127-e18413c212f9" />


## CAD and CAD drawing files:

[CAD file prt](https://drive.google.com/file/d/1vM9VJzkDtmBzuUNNXA8B0ROEej74tE4E/view?usp=sharing)

[Cad Drawing PDF](https://drive.google.com/file/d/1zYtGpBHpB_I4HC7vPlGN7qB_vPW_ufTi/view?usp=sharing)

## Lessons Learned

Throughout this project, I learned many lessons that will help me be a better engineer. Perhaps the biggest lesson I learned was how to use the formulas we were taught through Theory and how to actually apply them in real world scenarios. This project really opened my eyes as to the purpose of why we are learning how to calculate all the given values and data without being told to. This project also taught me that engineering projects aren't always going to have very specific instructions on how to do things and that usually instructions will require some interpretation and some use of free will. The instructions that were given for this assignment did not encapsulate every single part and process that needed to be done in order to get from start to finish. Although some of the other assignments in the class have been like this, I found that this one had the most leeway and openness towards solving the given problem statement. Another very important lesson that I learned was that doing the math right the first time makes life a lot easier. I had originally done some math but mixed some of the variables around in the formula and then ended up getting entirely wrong numbers. I left out this math in my portfolio as it ended up turning into a confusing mess that ended up just restarting on. This leads me into my most helpful lesson that I learned, which was properly organizing and color-coding some of my variables. There were times where I was conflating multiple letters together and made my mistakes as mentioned and in order to get around that, I started highlighting certain variables I had a tendency to mess up so I could clearly track where these values were going.Another very important thing that I learned was the application of solid mechanics. As I am currently taking this class at the time of making this portfolio, it is extremely helpful to see how the things we're doing in that class can be applied in industry. This has been helpful because now it allows me to truly understand what it is that each of the questions are asking me for and allows me to better visualize the objective. 


## Time Spent

This assignment took me about 5 hours
