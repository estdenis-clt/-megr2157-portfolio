# A2 – Truss Stress Analysis

## Objective

For this project, the objective stated that I must create a truss to be able to withstand forces with a couple parameters and safety factors including a pin and a roller system. The assignments dimensions are as follows.

<img width="317" height="215" alt="problemdiagram" src="https://github.com/user-attachments/assets/b6ef5126-2e50-4105-873e-f6a4db25039d" />

The length of a is 0.4 m, the length of B is 0.3 m, a is a pin and point B is a roller. The Chosen value for p in this project was 25kN. The beams of this structure are to be made with a 500 Steel. Additionally, we had to create free body diagrams for each of the joints and pins, we had to calculate the required cross-sectional area for all trust elements with a given safety factor and we had to do the calculations behind everything related to this project as well as a cad model. along with the cad model, we had to calculate the weight of the trust and compare it to the cad weight predictions given to us by the program. and the final thing we had to do was to document the entire process and how we did this. 


## 2. Truss Structure Design

#a)

img of final design

**i.**

When first developing this truss I first had to think about the statics behind the project. The beginning thought is how one has to create a truss that works with both a pin and a roller. With A being entirely locked in place through the usage of a pin, it was important to realize how the forces of X and Y were going to be calculated when creating this truss. 

img of beginning truss

I began my truss by simply connecting a line from the pin at A to the roller at B. This allowed me to connect both ends of the diagram while thinking about how I'm going to approach the rest of the truss. For the sake of simplicity and straightforwardness I connected a line from point B to point C and then I connected point A to point d. I then connected Point C and D which gave me a trapezoidal shape. It was at this point that I had to conceptualize what the most efficient method would be for creating a truss that would be able to withstand the forces of pee that are going in two different directions on the points of C and D. for this design, I took inspiration from truss designs that could be found in bridges all around the world and decided that the best method was to divide the trapezoid into three triangles. The way that I did this was by creating the first triangle by having two beams come down from the center point between points A and B and have them split into two beams one going to see and one going to do. This created the first triangle allowing for the loads put on the lower bar engaged by the upper beam and for the forces coming from the X Direction be held by those supporting beams. It was at this point that the structure was completed. This is because all of the different parts of the trusses created a three triangle setup that connected all four points and taking into account the different forces coming from the supports and from the applied forces at p. the reasoning behind this design was to essentially keep things easy as it made symmetry in the design in both the left and right side. This is because if there were any other loads or forces that would be applied to this truss outside of the agreed upon limits of the assignment, my truss would be able to safely be able to work within its safety factor in terms of holding said forces.


**ii.**

img of external fbd

It was at this point that I decided to solve external forces for the truss. It was at this point that I did the moment about point B because that was able to give me By. To finish solving for the external forces I solved for the forces in the y direction this would give me the forces of Ay. 

img of internal fbds

It was at this point that I could start using the method of joints in order to solve all of my internal forces. In order to solve for all of my internal forces on each member, I first started on pin B. the first thing that I did was solved for the sum of forces in the y direction which gave me the force of the member BC and then I sell for forces in the X Direction which gave me the force of the member BE. I then repeated that process for Pins A, C and finally pin D in order to find the forces in all of my members. 

img symbol FBD

I did this first symbolically and then came back and did it numerically after I verified the algebra was correct. although it is important to point out I did struggle with figuring out the ratios of lengths in order to properly get the geometry set up for the math.

img math from fbd

#b)

img of cross sectional math

After doing all of this, it was now time to solve for the cross-sectional area. and admittedly, I had no idea what I was doing so after consulting a few books and a few friends on how to solve this, I was able to get to work. It was at this point that I learned that my cross-sectional area needs to be done at the point in which there is the most applied forces. The max force my truss was experiencing was 20.03 kN which was experienced on the members CE and DE.

**i.**

img of unknowns for this

**ii.**

img of cross section symbol

It was at this point that I was able to now move on into finding my cross-sectional area by using the equation that allows for the minimum cross-sectional area. This primarily used the safety factor times the maximum force over the stress. After plugging in these numbers I came back to a minimum cross-sectional area of 0.343 in.

**iii.**

img of cross section math

**iv.**

img of truss weight

 After that, I then needed to calculate the total weight of the truss.Then came one of my biggest issues being the calculation of all the lengths of the beams. Although this does not seem like a complicated task I seem to have made it as it took me a long time to properly find a length that made sense. It was at this point I could now calculate the weight of the truss. so using the density of the materials and by calculating the volume I was able to calculate a total mass of 5.76 kg. 


## 3. Pin Calculations

#a)

**i.**

img of unknowns and knowns

**ii.**

img of pin FBD with the largest reaction load.

**iii.**

img of Symbolically solve for minimum cross-sectional area.

In order to connect this truss to the points of the assignment, there needs to be pins designed in order to keep it in place and to be able to hold the forces and the load of the truss. In order to do that you have to calculate the cross-sectional area and the overall length. So I looked for this cross-sectional area which had to take into account the total Shear Force that the pins would experience and then multiply it by a safety factor over the maximum share in order to find the cross-sectional area. 


**iv.**

img of Numerically solve for the cross-sectional area

My final cross sectional area that I was able to calculate came out to 0.106 in and in order to meet the standard while keeping in mind manufacturing, I bumped up that size to 0.11 in as that would bring it to 3/8 which is an extremely common hole size and not a problem when the entire truss is designed in metric. One of the problems I would find myself struggling with was converting between Imperial and Metric when designing certain elements but I was able to solve that after a lot of double checking and testing.

**v.**

img of the approximate combined weight of the pins.

Now that I had solved for the weight of the truss I now needed to get the weight of all five pins that I was going to use in my design. I did this by taking the cross sectional area and multiplying it by a length. At the time I wasn't sure of what length my pants should be so I just put in one inch as an arbitrary number just so I could get my data and move forward in the continuation process. After calculating my volume and multiplying it by the density of the given material I was able to find a total weight of all the pins to be Just under 75 g. At the time that number seemed extremely low from the idea of the pins but after doing the math it was because the necessary size of the pins was far lower than expected.



## 4. CAD

In order to properly understand how my truss will look and react, it is extremely important that I'm able to visualize it in cad. It was at this point that I booted up Creo with the intention of making my truss. This created quite a few hurdles as my cad skills were a bit rusty and there was a lot of precision required in the design of this truss. I started first by creating the main beam from point A to point B then from there I was able to go from point B and C and from there I followed the process in which I created my truss on paper and translated it to my 3D model in cad. Although that process sounds simple, I ended up switching programs a couple of times to try to help me get a better representation of my 3D model and so eventually coming back to Creo I was able to finally get the proper model. In order to make effective use of my time and to properly follow the rubric we were given, I decided to make my truss all in one piece. Now there are multiple advantages to this just going beyond the cad process and the primary one is that one solid piece of plate will not suffer from the same type of weaknesses that a welded collection of beams would create. because there are no welds or joints that can be weak as they're not one piece, this plate is able to stay in that. This is not however making it entirely immune to these issues but it can help reduce the amount of air that could stem from poor manufacturing or poor quality control. I then swiftly was able to add the proper sized hole for the pins and was able to have my entire truss in one piece. 


img of final cad

Now that I had created my truss in CAD including the holes for the pins I was able to now calculate the simulated weight given the proper material properties. As Credo does not contain a 500 steel as an option, I had to go and create a custom material. After researching all of the necessary properties of a 500 steel primarily focusing on Grade B as that is the industry standard for creating trusses or structural members I was able to have Creo create a final weight. The final weight it came up with was 5.53 kg which is about 0.2 kg less than what I had calculated which would make sense because my calculations did not take into account the holes made for each of the pins. 


img of weight


## 5. Lessons learned

One of the most important things I learned throughout this project was definitely making effective use of my time. I spend a lot of my time double guessing my answers or designs because I thought it wasn't good enough or it could be better. I really had to focus on accomplishing the task without nitpicking every part of my design which if I had done this from the beginning would have reduced my time spent vastly. This project has certainly reminded me of the importance of civil engineering and has further reassured me that my choices of being a mechanical engineer were correct. This assignment was not exactly fun for me but it was a really good learning experience into how real world situations would need the application of the skills that I've been learning since my freshman year of high school. and also while doing research for this project on the different calculations and factors I needed to keep in mind while designing my truss, I came to find out that I'm just scratching the surface of truss design and that this by all accounts is easy compared to what civil engineers have to deal with.

This project holistically was an extremely thorough assignment in which every single part of this assignment required an intense amount of focus and math. In total this project took me about 9 hours to complete. As I mentioned before, my nitpickiness definitely added to the length of my assignment but also my mishaps with CAD programs really set me back at a point where I needed to maximize the time I have. Documentation was also another element that did lead to the Engineering industry as a whole truly requiring very specific information and data because if any information is left out or is wrong or neglected, it can cause detrimental problems that can endanger the lives of others. It is for this reason that I wrote more than I thought I had to in every section so that any reader here could not only understand what goes into such a project but to also understand the necessary items on a metaphorical checklist that need to be marked before one can say that they have successfully designed a truss. Another major issue that I ran into and I noticed that 80 to 90% of other people I talked to had experienced was the very small but very important details in the instructions. The biggest problem I noticed when talking to a large swath of students also accomplishing the same project was that the forces of P that were being applied to the truss we're going in opposite directions however the arrow for the force being applied on to point C was not very well visible and so many assumed that the forces of P were both going down. This of course entirely changes the calculations needed as without the symmetry of pee it entirely changes what the minimum requirements are and ultimately how the truss needs to look. This was a widespread problem that went past me and set me back at least an hour if not more and has caused lengthy delays for every student that participated in this project. 



## 2157 Students Only

I used claude...

img of claude prompt

#Part 1.

**1.**

**2.**

**3.**

**4.**


#Part 2.

**1.**

**2.**

**3.**

## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

**Link to CAD**

