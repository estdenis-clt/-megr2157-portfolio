# A8 – Gear Box Design


## Objective


The objective for this assignment was to create a gearbox with two Spur Gears and two shafts, one for input and one for output. We were given a set of parameters including a gear ratio of 24:9 as well as a numerous collection of values. The objective was to create this in CAD and as a 2157 student we had to generate drawings of said CAD.


## Design of the shafts


<img width="862" height="398" alt="image" src="https://github.com/user-attachments/assets/84df2257-3f84-425c-b495-e6bf2349cc83" />

In order to start, we had to calculate and determine if the shaft diameters would withstand the forces and stresses resulting from the normal function of the gearbox we were building.Before I could do any of this, I first had to write down my knowns and unknowns we found this by consulting our machinery handbook which mentioned that the allowable shear yield strength should not exceed 4,000 PSI for power transmitting shafts. It also said that shorter shafts should not exceed 8,500 psi. Additionally, the shafts that we were creating had to be pressed into the gears in order to ensure a tight fit under normal circumstances. 


<img width="915" height="446" alt="image" src="https://github.com/user-attachments/assets/9a5ad713-e283-4d3f-9f00-aedbaee645f3" />


Now that we had all the needed information, I could then move to doing the calculations required to determine my answers.This would be done both symbolically and then done numerically in order to verify the proper usage of variables and values.


<img width="771" height="362" alt="image" src="https://github.com/user-attachments/assets/165ebdeb-9f3d-4476-a758-e8dc1195c5e7" />


<img width="772" height="180" alt="image" src="https://github.com/user-attachments/assets/18029ca4-1879-487f-ad14-f21073f673fb" />


Now that I had done that, I verified that the diameters were within spec by double checking with extra math circling back to the power output these diameters would be put under.


<img width="817" height="516" alt="image" src="https://github.com/user-attachments/assets/31bc9e61-df23-471f-9ddf-738c2eb60436" />


## Design of Journal bearing


<img width="981" height="656" alt="image" src="https://github.com/user-attachments/assets/9091f6ef-a45f-4586-b4e8-45161e366574" />


Since I had now verified that both diameters were more than sufficient for the purposes of our project, The Next Step was designing the journal bearings. Some of the parts that we had to figure on our own was the length of these bearings and for the sake of Overkill and safety, I went with 0.25 in. and now that I had the values I needed, I had to determine the velocity, pressure, and PV to better find the material that I would select for my bearing. as it was in the last case, this system is a press fit and so I will design accordingly.


<img width="848" height="545" alt="image" src="https://github.com/user-attachments/assets/da7faa51-b5fa-42f2-b8c8-30441f40f9f5" />


<img width="786" height="651" alt="image" src="https://github.com/user-attachments/assets/0d59d87f-a480-45a5-93eb-e7e5a45628a3" />



Based on all of the values I had calculated, I decided to go with porous bronze due to the fact that it well exceeds the minimum material and this would allow for long duty cycles with low wear.  In addition, it is relatively inexpensive when it comes to metals and is extremely common to buy from any place such as McMaster-Carr. 


## Sketch of the gearbox


At this point, I have all of my values and I needed to create an initial gearbox design. I decided to do this with a hand drawn of a box with a substantial hole milled out of it giving a space for gears, the input and output shaft as well as space for a heavy duty cover that has six bolts in order to ensure that any lubrication that may be inside will not seep out during operation as well as ensuring a tight seal.


<img width="630" height="377" alt="image" src="https://github.com/user-attachments/assets/a5d4d9b4-94fa-4529-a97a-1666ef6ca412" />



## CAD design


It was at this point that I now had everything I needed to do to translate my idea into an actual design. The best way to do this is through creating a cad design in solidworks. I started by creating all of the pieces I needed separately and then combining them all in an assembly at the end. Luckily for the purpose of this project, I could import a lot of the pieces I needed as STL files straight from McMaster-Carr in order to vastly speed up this process. All of the values that I elected to use were either given in the problem statement or were calculated throughout the extent of this project as seen in the previous sections. 


Images of all the different CAD pieces


In order to precisely ensure that all of my values are exactly how I calculated them, I used a set of parameters which can be seen in the following image. Additionally, this makes it better when changing this design because I can just change the global variables and it will make it far faster to scale or scale this project. 


Image of parameter table



## Gearbox housing


Because I started with the shafts and bearings, I'm not able to move on to the actual gearbox housing in order to secure all the pieces. I started with a regular rectangular prism and then made a large Center cut that went the majority of the way through, added holes in the back for the shafts and added in the holes for the bolts.

Image of the gearbox housing


In order to properly seal this gearbox, allowing it to be one solid housing, I created a simple plate that was a quarter inch thick with an accompanying six holes for the bolts that I had added.


Image of gearbox cover. 


## Final assembly


Now that I had created all the parts and downloaded all of the gears that I will need, I then combined everything into the final assembly and made sure everything fit properly. I had to make a few adjustments with the placement of the holes for the output shaft but for the most part it was good to go from the first iteration.


image of final assembly


image of open Final assembly


image of transparent assembly


##  Lessons Learned


