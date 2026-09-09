# A3 – [Topic]

## Objective

The objectives for this assignment are to design a bar and then through a series of analysis find axial deflection through parametric modeling and other things such as finite element analysis. The purpose of this assignment is to help us understand how structural designs are made and how testing these certain use cases are worked through. Also introduced us to properly dimensioning parameters inside of CAD and learning how to comprehend data given by analysis.

## Part 1 - Designing the Beam

In order to start this assignment, it was first important for me to outline the things that I will need to be calculating and the values that are already given to me. The reason I did this was in order to understand what it is the assignment itself is asking for just beyond the surface level. The easiest and most straightforward way of doing this is to write down my knowns and unknowns. Once I had written down my knowns and unknowns, I decided to determine my diameter and my applied force that was necessary for the scope of the assignment. For my force I decided to go with 300 lbf as it was the bottom of the range given which would allow for me to give some leeway in the calculations from the software side just in case this would overwork my personal laptop. For the choice that I made on my diameter I went with 0.25 in because working with a quarter is very easy to remember and will be a clean number for my length calculations. After dissecting the instructions, it was unclear whether the bar was supposed to be a square or a circle as they were mentions of both height times width and circular cross section area and so the choice that I a circular bar has it seems like the more correct option plus seemed more logical of a choice for understanding such an analysis from a beginner standpoint. But before I could do any of the cad work for this I had to first do all of my hand calculations. I started first with my cross sectional area with my given diameter and then moved on to my length. The elements that I needed to find, such as Young's modulus, came from a link given to us by the professor that led to a Matlab material property data chart.


<img width="3845" height="1884" alt="1000004177" src="https://github.com/user-attachments/assets/c09f8867-a14c-441d-8fac-aa2b43b4be6f" />

Now that I had done all of my hand calculations I was now able to transfer all of this data to SolidWorks. I did that by opening the equations tab and selecting manage equations and then filling out my information. I did that by creating global variables and then entering values for the variables before creating an equation that would find my overall length which coincided with my hand calculations. After I had finished, I decided to click okay and move on to the design element.

<img width="926" height="422" alt="Screenshot 2026-09-09 161908" src="https://github.com/user-attachments/assets/a086b1bd-d22b-4027-bf1e-635f7faa6e2e" />

The first thing I had to do with the actual design was create a circle with a 0.25 diameter. but instead of adding the value 0.25 as a raw number, I use the global variables function to assign the diameter as this would allow me to modify my diameter later without having to modify the sketch itself but rather the global variables tab allowing for this to be a more dynamic analysis cad file.

<img width="1522" height="810" alt="Screenshot 2026-09-09 162910" src="https://github.com/user-attachments/assets/c0cd5d4e-fe49-4d93-9bea-3d6db780f08a" />

The next step of course is to take this 2D drawing and step it up into a 3D Extrusion which simply was done through the extrude function and the length of the Extrusion was once again set by the mobile variables but this time set to the length equation. as stated before, this will now allow me to change any variable at any given time and it will automatically update the cad file.

<img width="1517" height="727" alt="Screenshot 2026-09-09 163029" src="https://github.com/user-attachments/assets/632ec49c-dc0a-4235-af69-fe06837a32c9" />

## Material

For the material applied on this bar, I had to create a custom material in SolidWorks using a data sheet giving our aluminum alloy specifications in order to ensure the calculations will be parallel to the hand calculations I had done earlier.

<img width="942" height="770" alt="Screenshot 2026-09-09 164403" src="https://github.com/user-attachments/assets/0fa0f36e-6d14-4c0f-99a0-2ed22ad3a578" />


## Part 2 - FEA

Now that both the hand calculations and the cad were completed, I can now enter the FEA analysis stage. The first thing that I had to do was fix one of the edges using the fixture function and then apply a force that goes away from the beam itself specifically in the right direction as it was a necessity to get correct for the bounds of this assignment. It was at this point that I entered in my force for this analysis which of course is 300lbf as mentioned before And then did all the other things necessary making sure it worked to then run my simulation.

For the purposes of this specific assignment I ran a Von-Mises Stress graph and a displacement graph.

<img width="1178" height="672" alt="Screenshot 2026-09-09 170155" src="https://github.com/user-attachments/assets/eac6c581-ea7b-44b4-818d-c000f018630d" />

The purpose of using a Von-mises FEA helps any given engineer the capabilities to find the ductility of any given material to see how it will deform under certain loads. This can help an engineer realize whether it will remain in the elastic deformation zone or whether it will exceed into the plastic deformation zone. However, my purposes for this analysis requires me to compare the simulated data to that of what I hand calculated and to compare the values.

<img width="1161" height="680" alt="Screenshot 2026-09-09 170219" src="https://github.com/user-attachments/assets/1769294c-e9c2-486b-9db7-712c4bf36d65" />

The usage of a displacement FEA primarily allows for an engineer to see the overall deflection from any given object, In this case a beam, when a load is applied. One of the bounds of this project as specified in my earlier writings was 0.009 in was my max deflection allowed. After converting my found displacement and comparing it to my given boundary, I came in just under 0.009 in.

It was at this point that I then needed to continue on with my hand calculations but now using the data found in my FEA to find my actual stress and my safety factor whilst juxtaposing the found data.



## Part 3 - Design Reflection


A) As mentioned before, my axial deflection came within the bounds of this project. I then did a comparison from my parametric hand calculation to my FEA data. The difference that I found for this project came out to be about 7.47%, which seems really high compared to what I was expecting. However there are a couple of things that could have resulted in this. The first thing being my lack of experience using SolidWorks as this was my very first time using the software and even more than that it was my first time using any type of force simulation system. This could have led to a plethora of issues that could have caused some of my discrepancies as well as the fact that the mesh density or the material properties that I interacted with could have also directly resulted in this level of error. and even though the discrepancy is as much as it is, I am far more likely to trust my hand calculations as they are backed with exact data given to me and were calculated with formulas that are the industry standard.

<img width="2844" height="960" alt="1000004181" src="https://github.com/user-attachments/assets/1c95285f-5229-4fff-9116-5d5868958a4a" />

B) 

<img width="2731" height="1647" alt="1000004182" src="https://github.com/user-attachments/assets/4cd32b47-9e3c-4641-8a09-7f1b2416a131" />

## Part 4 - Lessons Learned

Some of the lessons that I learned from this assignment primarily come down to how important it is to understand software. Since I was so new to SolidWorks I struggled a lot with understanding how to do simple tasks that I would do in other equivalent cad software such as Creo or Onshape. Another lesson that I certainly learned was the importance of precision in something like an FEA because even the smallest discrepancies in any value can ultimately make drastic changes to the amount of required work for designing something like a structure. Perhaps the biggest lesson that I had to learn through this assignment is how important it is to read through instructions. Right from the get-go I had to spend a long time analyzing the instructions to figure out whether my bar had to be circular or square, which led to me wasting a bunch of time when I could have been doing calculations. This all of course could have been solved by me simply reading the instructions correctly the first time and not dwelling on small details that aren't necessarily important. In total, this project took me approximately 3 hours.

## 2157 Students Only

After being tasked to modify the design parameters that we were given, I decided to keep things relatively simple. Since I had made my diameter 0.25in I decided to bump that up to 0.75in and change my force from 300lbf to 400lbf. The reason I chose those values was because I wanted to see a substantial difference between my first iteration and my second iteration. And since my new values I had selected were larger by a considerable factor, my calculations reflected that.

<img width="2752" height="1258" alt="1000004183" src="https://github.com/user-attachments/assets/a8d70b25-ec7d-4934-9e95-bff4f1aceacf" />

## CAD File

Check out [CAD](https://drive.google.com/file/d/1yUNAKTKqtENBTMUDxyVB3w1q5fRr68ok/view?usp=sharing) for my CAD file.
