# A11 – Motor Selection



## Introduction

The purpose of this week's assignment was to act as a continuation of the previous project by selecting a motor for the system we designed. We will be finishing the lead screw design by adding a coupler and a motor suitable for the work and the specifications of our system. In order to do this, we split the project into parts focusing on different elements of the design and allowed us to work on this more efficiently.


## Torque and speed calculations:

In order to find the proper motor for this project, we first had to define what made a proper motor numerically. In order to do this, we needed to calculate the torque and speed that would be required for the maximum efficiency while fitting within our specifications. Once we obtained those values, we could make the selection for the proper motor to add into our lead screw system. What we did to calculate these values was to take the result we got from the previous assignment and use the formulas that were taught in the lecture as well as the ones found in the handbook in order to translate into our needed values. We found that we needed at least 10.56 Nm of torque with a max speed of 23.62 RPM.




## Motor selection:


Now that we had found the speed and torque and which our motor will need to meet, we were then able to select the appropriate motor. We elected to use the Nema 23 Stepper motor due to its usable torque and power and its 15 to 1 gear ratio with a planetary gearbox. 


<img width="497" height="643" alt="image" src="https://github.com/user-attachments/assets/42a2e66f-649d-4c25-9d66-0824a0a0335e" />



<img width="530" height="377" alt="images" src="https://github.com/user-attachments/assets/4af56129-4c15-47cc-843c-17519d240e7a" />



## Coupler design:


The next part we had to design was the coupler that would attach the motor to the lead screw. One of the stated requirements said that we had to select a four hole pattern to secure the mount as well as maintain precise alignment with the lead screw to prevent binding or eccentric loading. Another design parameter we needed to meet was that it has to be easily accessible for maintenance and to have minimal deflection. We ended up settling on using a vibrate dampening flexible shaft coupler in order to accommodate the requirements of the project. 


<img width="496" height="682" alt="image" src="https://github.com/user-attachments/assets/c0bb252c-18f5-422e-9944-9ae028e80ac3" />


## Frame design

The next portion of the design had to be the frame itself that would allow the motor to be mounted in order to overall make the system stable and precise. The frame would consist of four standoff columns that would connect to the motor itself which would create a system where the frame would sustain two kN of force and would divide the load up without creating excessive deflection. The ends were also threaded in order to allow easy accessibility and disconnection for the purposes of maintenance or adjustments that might have to be made later down the product life cycle. Additionally it would have brackets to connect the base to the standoffs allowing a stable system.


<img width="495" height="648" alt="image" src="https://github.com/user-attachments/assets/090a01d5-cb09-4391-8a85-8754006b9179" />


<img width="492" height="637" alt="image" src="https://github.com/user-attachments/assets/2e96f0eb-fa9a-428c-9a5b-1c7b9adfad7e" />



## Parametric Modeling

Parametric Table

The next part of the project was to take all of the design parameters and dimensions and to put it into a cad file. We did this by combining what we had already done with A10 and adding on the motor and the coupling system in order to create the final model.


<img width="682" height="626" alt="Screenshot 2026-11-11 191715" src="https://github.com/user-attachments/assets/6121d677-5e9a-48e6-bebc-68c161b90e73" />
Noahs Screenshots, of assembly and pieces


<img width="706" height="637" alt="Screenshot 2026-11-18 200459" src="https://github.com/user-attachments/assets/47ff2fd5-00c8-4d70-85e9-29137eca2374" />
<img width="598" height="612" alt="Screenshot 2026-11-18 200304" src="https://github.com/user-attachments/assets/3bae6afe-9014-461c-a98d-520bfbb8587d" />
<img width="712" height="637" alt="Screenshot 2026-11-18 200249" src="https://github.com/user-attachments/assets/ef1e944a-910d-4715-971d-d3102c399fc5" />
<img width="595" height="527" alt="Screenshot 2026-11-18 200235" src="https://github.com/user-attachments/assets/3dc9d036-1025-4f43-b9e0-8b330112ec55" />
<img width="645" height="674" alt="Screenshot 2026-11-18 200217" src="https://github.com/user-attachments/assets/76fd585e-c540-4953-a476-9d3512b0344e" />
<img width="587" height="546" alt="Screenshot 2026-11-18 184116" src="https://github.com/user-attachments/assets/25b5846a-3c1d-4302-9fab-5448cb80026c" />


After we made the cad files of the final assembly, we had to do an FEA on multiple parts of the assembly in order to test the parameters in which the assignment outlined


<img width="749" height="481" alt="Screenshot 2026-11-18 210904" src="https://github.com/user-attachments/assets/0c3cb924-bfb3-47c8-92d8-0087480c370b" />
<img width="781" height="502" alt="Screenshot 2026-11-18 210730" src="https://github.com/user-attachments/assets/884d337e-811d-4397-8bee-95a0fda77a18" />
<img width="773" height="466" alt="Screenshot 2026-11-18 210552" src="https://github.com/user-attachments/assets/af2bbcb8-08ed-40a4-a725-4d80ee04a197" />

Struggles

Yapping

FEA

<img width="2494" height="1398" alt="0" src="https://github.com/user-attachments/assets/d9751d23-6b2a-400c-92a9-9d41d28ac379" />

<img width="1507" height="1137" alt="0" src="https://github.com/user-attachments/assets/d50f992b-b2f4-49e0-823b-bd0299216f19" />

<img width="2556" height="1381" alt="0" src="https://github.com/user-attachments/assets/52ba38e1-5866-45e4-bc46-914d03f4a178" />

<img width="2376" height="1398" alt="0" src="https://github.com/user-attachments/assets/531e701b-5dc5-4c59-8856-5d04df8b183c" />


## Design Floating Bearing Mount:



## Overall cost 

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| :---: | :---: | :--- | :---: | :---: | :--- |
| 1 | 2 | 1018 Carbon Steel Acme Lead Screw | $17.04 | $34.08 | [McMaster 99030A992](https://www.mcmaster.com/99030A992) |
| 2 | 2 | 932 Bearing Bronze Acme Flange Nut | $111.78 | $223.56 | [McMaster 95120A592](https://www.mcmaster.com/95120A592) |
| 3 | 6 | T-Slotted Framing Extrusion (2 ft) | $31.02 | $186.12 | [McMaster 3136N734](https://www.mcmaster.com/3136N734) |
| 4 | 1 | T-Slotted Framing Extrusion (18 in) | $40.67 | $40.67 | [McMaster 3136N736](https://www.mcmaster.com/3136N736) |
| 5 | 1 | T-Slotted Framing Extrusion (18 in) | $21.54 | $21.54 | [McMaster 3136N735](https://www.mcmaster.com/3136N735) |
| 6 | 8 | T-Slotted Framing Corner Bracket / Gusset | $10.30 | $82.40 | [McMaster 5537T942](https://www.mcmaster.com/5537T942) |
| 7 | 2 | 863 Iron-Copper Sleeve Bearing | $2.59 | $5.18 | [McMaster 2938T39](https://www.mcmaster.com/2938T39) |
| 8 | 2 | Clamping Shaft Collar | $18.38 | $36.76 | [McMaster 6698K11](https://www.mcmaster.com/6698K11) |
| 9 | 2 | Medium-Strength Steel Hex Head Screw | $3.09 | $6.18 | [McMaster 92865A318](https://www.mcmaster.com/92865A318) |
| 10 | 2 (1 Pack) | Black-Oxide Alloy Steel Socket Head Cap Screw | $8.35 | $8.35 | [McMaster 90044A187](https://www.mcmaster.com/90044A187) |
| 11 | 2 (1 Pack) | Steel Dowel Pin | $14.76 | $14.76 | [McMaster 90426A370](https://www.mcmaster.com/90426A370) |
| 12 | 2 | Vibration-Damping Precision Flexible Shaft Coupling, Clamping Hub, 53 mm Long, 41.3 mm OD, for Round Shaft | $54.67 | $109.34 | [McMaster 9845T54-9845T429](https://www.mcmaster.com/9845T54-9845T429/) |
| 13 | 2 | Durometer 92A Spider for 1" OD and 25 mm OD Vibration-Damping Precision Flexible Shaft Coupling | $19.05 | $38.10 | [McMaster 9845T15](https://www.mcmaster.com/9845T15/) |
| 14 | 2 | Vibration-Damping Precision Flexible Shaft Coupling, Clamping Hub, 1-13/32" Long, 1" OD, for Round Shaft | $29.07 | $58.14 | [McMaster 9845T2-9845T203](https://www.mcmaster.com/9845T2-9845T203/) |
| 15 | 2 | T-Slotted Framing Silver Corner Bracket, 1.63" Long, 40 mm Double/Quad Rail | $12.50 | $25.00 | [McMaster 5537T442](https://www.mcmaster.com/5537T442/) |
| 16 | 2 | NEMA 23 Bipolar Stepper Motor, L=56 mm, with 15:1 Planetary Gearbox (23HS22-2804S-PG15) | $54.79 | $109.58 | [StepperOnline 23HS22-2804S-PG15](https://www.omc-stepperonline.com/nema-23-stepper-motor-bipolar-l-56mm-w-gear-ratio-15-1-planetary-gearbox-23hs22-2804s-pg15) |
| | | | **Total Cost** | **$999.76** | |



| Person | Hours | Cost/Hour | Total Cost |
| :--- | :---: | :---: | :---: |
| Jack | 10 | $35 | $350 |
| Noah | 9 | $35 | $315 |
| Evan | 8 | $35 | $280 |
| **Total Cost** | | | **$945** |


## Lessons Learned

Throughout both parts of the assignments being a 10 and a11 we learned a lot of different lessons. For starters, this was a huge undertaking in terms of workload being the most amount of work contributed into any of the assignments for this class by a large portion. The detail in which every part of the assignment went into truly immersed us into the engineering world and showed how overwhelming it could be. One of the biggest problems we came into was trying to make everything come together. Trying to combine our math with our modeling with our outputted ideas created long inefficient methods of going from our math to our design. Like a similar problem we had last time, a lot of our designing circled around primarily mcmaster car parts and finding the right parts that would work in our design without falling outside the parameters proved to be difficult. For our cost, we struggle to be able to accurately note how much time it took for us to complete as well as being able to go through every single of the numerous parts that were used in the assemblies of this project. Although we struggle through all these problems, our very Swift communication allowed us to quickly respond to the problems we were facing and would allow rapid development of a solution. Overall, this assignment really taught us how to work better as a team by playing to each other's strengths in order to help us get this project done in a timely manner and how we can problem solve when we face unforeseen issues.


## Drawings (2157 Student section)

<img width="722" height="540" alt="Screenshot 2026-11-11 191615" src="https://github.com/user-attachments/assets/bea2ab03-4156-47c4-b2b3-5c3bd681b035" />
<img width="809" height="625" alt="Screenshot 2026-11-18 203221" src="https://github.com/user-attachments/assets/bab65753-8fac-4456-818b-3d0c7974e0fd" />
<img width="757" height="591" alt="Screenshot 2026-11-18 212847" src="https://github.com/user-attachments/assets/23920a7a-4ac5-47b2-b561-b354144d17a2" />
<img width="710" height="553" alt="Screenshot 2026-11-18 212346" src="https://github.com/user-attachments/assets/afac1075-70c1-4afe-9299-e2c590d8f6cd" />

## Links to CAD Files and Drawings


[Assembly CAD file](https://drive.google.com/file/d/1qH8I4IP3YvXpdvFuLIL-cY8mEvIoVjaR/view?usp=sharing)


[Assembly CAD Drawing 1](https://drive.google.com/file/d/1xnHED8RcC8T2MWHMoQizKQxOc4QxKRW5/view?usp=sharing)

[Assembly CAD Drawing 2](https://drive.google.com/file/d/17J8_2hlSnTyc0gD4vO4K1x0PgJYTuQqV/view?usp=sharing)
