<img width="1040" height="665" alt="Screenshot 2026-10-21 170348" src="https://github.com/user-attachments/assets/4b0bc6bd-6747-4a2a-a43b-4e91ddd81ded" />
<img width="1137" height="677" alt="Screenshot 2026-10-21 170342" src="https://github.com/user-attachments/assets/827b5983-6d72-47b2-b947-2b776cd7b73d" />
<img width="1147" height="673" alt="Screenshot 2026-10-21 170335" src="https://github.com/user-attachments/assets/c175574a-2b60-4c22-b0de-371bccf3742a" />
<img width="832" height="595" alt="Screenshot 2026-10-21 170331" src="https://github.com/user-attachments/assets/a5b1a77a-687a-4e8a-b72f-c934e2e8ac9f" />
<img width="1081" height="642" alt="Screenshot 2026-10-21 170403" src="https://github.com/user-attachments/assets/8aa99671-ac5a-41a6-bdf3-b6e9ffb1f97f" />
# A7: FEA on Bracket

## Objective

The objective of this assignment was to use the process of FEA in order to analyze and improve upon our design of a bracket we had made previously.We were supposed to do this process repeatedly with finer and finer parameters in order to get a better sense of where the failure points and improvements could be made on our piece.


## Initial Design

In order to start this project, I had to utilize the part I made in SolidWorks in the previous assignment that could be found in my portfolio being in section A6. The first thing that I had to do was specify a material as I did not do that last time and I selected A36 steel due to its popularity and its overall characteristics and strength.


<img width="1466" height="862" alt="Screenshot 2026-10-21 161102" src="https://github.com/user-attachments/assets/9d28e45f-4087-4480-82b3-c71570c6d625" />

## Starting Design:


The first design I went through in FEA was the very first design that I had made last time using my sets of parameters.I then had to set the specifications of the simulation study up.


<img width="292" height="350" alt="Screenshot 2026-10-21 162019" src="https://github.com/user-attachments/assets/07571c8f-65ce-492c-9625-dd7668a1d8c1" />


The next thing I had to do was apply a force to the shaft where the link would eventually end up going. I did this by applying a force load to the shaft and specifying the direction and magnitude of said force. I did struggle at first with figuring out how to get the forces to go in the direction I need them but after messing around in solid works for a good 15 minutes I was able to figure it out. 


<img width="506" height="628" alt="Screenshot 2026-10-21 162028" src="https://github.com/user-attachments/assets/365a906e-43d9-4828-8911-30b4da99c741" />


The next part that had to be done was adding a mesh to the cad in order to get a more precise FEA on the bracket. I can change course or find this message and for the purposes of the project I will have to make it finer and finer over to get a more precise look at the data.


<img width="495" height="635" alt="Screenshot 2026-10-21 162546" src="https://github.com/user-attachments/assets/b9c87be8-e32a-4b3e-9299-f40c702fa347" />


## The Workflow

Now that I had done the initial setup for study, the objective was now to run the simulation multiple times. The way that I did this was running my first study with a moderately course mesh and then running the simulation two more times each with a finer and finer mesh. I then recorded down all of the values and a table along with the accompanying screenshots.


<img width="1145" height="693" alt="Screenshot 2026-10-21 164240" src="https://github.com/user-attachments/assets/da0a0caa-27ad-422d-8ce3-c6b5d09041dd" />


<img width="1127" height="665" alt="Screenshot 2026-10-21 164227" src="https://github.com/user-attachments/assets/43a126d8-734d-4854-a66c-daa21b9cb0c9" />


<img width="1196" height="680" alt="Screenshot 2026-10-21 162807" src="https://github.com/user-attachments/assets/dc0d10c2-fb85-4f27-8a14-ec58ec192493" />


<img width="1171" height="722" alt="Screenshot 2026-10-21 164253" src="https://github.com/user-attachments/assets/25af420e-7171-4dab-ba0a-abb571e48db4" />


<img width="785" height="167" alt="image" src="https://github.com/user-attachments/assets/6899a156-cf5b-4a34-a43d-4ffb05780444" />


## Design 2


The shaft is bending too much because it is not supported well enough. I will add two trust members in order to help spread the load on the back wall up through the upper feature. Additionally, I added an extra bit of material below the floor in order to help reduce the chances of the floor buckling as there's more load on this feature.


<img width="657" height="687" alt="Screenshot 2026-10-21 165834" src="https://github.com/user-attachments/assets/65e4f0ec-5d60-4e6b-9a41-36e5824c03c2" />

And I will now repeat the process of the simulations for this design.

<img width="961" height="668" alt="Screenshot 2026-10-21 170103" src="https://github.com/user-attachments/assets/c26d0b10-e99f-4086-af9c-d576534ed47d" />


<img width="988" height="667" alt="Screenshot 2026-10-21 170051" src="https://github.com/user-attachments/assets/cf3a0a04-6498-4bed-b7d2-229c03691fca" />


<img width="992" height="665" alt="Screenshot 2026-10-21 170045" src="https://github.com/user-attachments/assets/c62972f0-ea26-4eec-a5d4-17a046ace6a0" />


<img width="971" height="648" alt="Screenshot 2026-10-21 170118" src="https://github.com/user-attachments/assets/b908c440-b656-433d-927e-1f5df856903c" />


<img width="517" height="655" alt="Screenshot 2026-10-21 165821" src="https://github.com/user-attachments/assets/3d6df180-679d-4055-85d7-d95b11c6d581" />


<img width="790" height="167" alt="image" src="https://github.com/user-attachments/assets/01336f1c-1190-41fe-b3bd-c14f5315fce1" />


<img width="1081" height="642" alt="Screenshot 2026-10-21 170403" src="https://github.com/user-attachments/assets/a979b0a0-a760-4bcc-9a3a-adb9d245144a" />


<img width="1040" height="665" alt="Screenshot 2026-10-21 170348" src="https://github.com/user-attachments/assets/361cf049-186b-4885-b4d8-4c0b65a285d0" />


<img width="1137" height="677" alt="Screenshot 2026-10-21 170342" src="https://github.com/user-attachments/assets/9644b342-9228-4ea1-928b-734df750cd60" />


<img width="1147" height="673" alt="Screenshot 2026-10-21 170335" src="https://github.com/user-attachments/assets/5ea92f54-47c7-4682-948f-a9648dcdac0c" />


<img width="832" height="595" alt="Screenshot 2026-10-21 170331" src="https://github.com/user-attachments/assets/de6a60f0-73dd-4a31-81b2-460b022772e7" />


<img width="1120" height="607" alt="Screenshot 2026-10-21 170703" src="https://github.com/user-attachments/assets/de28f65b-c183-44eb-9efa-9954657c6a5a" />


<img width="1113" height="641" alt="Screenshot 2026-10-21 170656" src="https://github.com/user-attachments/assets/aefc366b-104e-4be0-8992-6a85e845c9ae" />


<img width="1157" height="647" alt="Screenshot 2026-10-21 170647" src="https://github.com/user-attachments/assets/959da267-7ef4-4643-9698-b03d0ae51d4e" />


<img width="485" height="572" alt="Screenshot 2026-10-21 170631" src="https://github.com/user-attachments/assets/60e3a8a3-b91e-4cfd-bc78-94a107b799de" />


<img width="1088" height="652" alt="Screenshot 2026-10-21 170717" src="https://github.com/user-attachments/assets/4be19e82-d26c-4262-a72f-d3bcf1700a5b" />


<img width="787" height="166" alt="image" src="https://github.com/user-attachments/assets/cab04c16-d1e7-42b1-be12-3743faaea669" />

## Design 3


After reviewing the second design feat, I realized that it needed more support perpendicular to the axis in order to be able to have the load split to reduce the amount of bending on the shaft. I did this by adding a wall that was snugly between the two new trusses and having it go down to the shaft in order to create a strong connection.


<img width="457" height="507" alt="Screenshot 2026-10-21 170947" src="https://github.com/user-attachments/assets/a3ca83e9-151e-4f5e-a656-eba6c604ba04" />


Now that I have created my third and final design, I am now going to run it with the same process of three simulations with a gradually more precise mesh.


<img width="491" height="517" alt="Screenshot 2026-10-21 171058" src="https://github.com/user-attachments/assets/da154725-0497-443f-b92d-f514b39b223a" />


<img width="1170" height="646" alt="Screenshot 2026-10-21 171559" src="https://github.com/user-attachments/assets/278857b3-57ca-4027-916a-e3f0eb14470d" />


<img width="1065" height="563" alt="Screenshot 2026-10-21 171547" src="https://github.com/user-attachments/assets/4f21c06b-2ff0-44b6-bf35-305cfc28a69c" />


<img width="1105" height="657" alt="Screenshot 2026-10-21 171540" src="https://github.com/user-attachments/assets/3fdc37b9-4bf2-4838-88fa-b55c2569895a" />


<img width="526" height="497" alt="Screenshot 2026-10-21 171526" src="https://github.com/user-attachments/assets/23569db8-2fd4-4587-87f8-0b48dd255039" />


<img width="1087" height="612" alt="Screenshot 2026-10-21 171206" src="https://github.com/user-attachments/assets/85150e01-daf8-4b99-b779-c2b22310e6cd" />


<img width="1152" height="623" alt="Screenshot 2026-10-21 171154" src="https://github.com/user-attachments/assets/d13f15eb-3ad9-4985-bb98-28e02af4f573" />


<img width="1180" height="592" alt="Screenshot 2026-10-21 171122" src="https://github.com/user-attachments/assets/a2c62258-8806-4aeb-9ffb-b2163a184e0d" />


<img width="1116" height="608" alt="Screenshot 2026-10-21 171114" src="https://github.com/user-attachments/assets/94d787a8-2bf9-4510-a571-ed2e96c027d9" />


<img width="491" height="517" alt="Screenshot 2026-10-21 171058" src="https://github.com/user-attachments/assets/15c21466-7ad1-48fc-af70-005e3c311d1a" />


<img width="1188" height="606" alt="Screenshot 2026-10-21 171846" src="https://github.com/user-attachments/assets/0d3625c3-4b46-4e90-93f7-89bf60e55f0e" />


<img width="1148" height="621" alt="Screenshot 2026-10-21 171839" src="https://github.com/user-attachments/assets/8971a288-69fa-40f2-bc7e-5c27244723a1" />


<img width="1150" height="606" alt="Screenshot 2026-10-21 171823" src="https://github.com/user-attachments/assets/175d9e78-0146-4a41-88d6-9a722ad55b06" />


<img width="1128" height="632" alt="Screenshot 2026-10-21 171818" src="https://github.com/user-attachments/assets/8c776bfc-b5cd-4d43-bba1-0a376f681371" />


<img width="550" height="547" alt="Screenshot 2026-10-21 171757" src="https://github.com/user-attachments/assets/45300a1d-9027-4bbe-8eea-7ed233f36ccb" />


<img width="792" height="173" alt="image" src="https://github.com/user-attachments/assets/8b695040-a742-45f8-a5e1-9b7a3b42e848" />


## Reflections

After three sets of design and ideas, I have come to the conclusion that although my design is better there is plenty of room to improve. The biggest problem that I was experiencing was that thin walls at the top started to buckle with more and more force. Luckily within the circumstances of this project that buckling would end up interfering with the part that would be attached although it would create some interference fit issues. The simplest way to resolve this problem would be adding additional wall space and we're going to make it thicker and stronger in order to spread the load out with more material and improve the overall strength of that feature. Additionally, a lot of very low stress area was shown on the part which means that there is place for optimization such as reduction in material by drilling out holes. These holes could be like weathering an intricate hex pattern or an oval-shaped through hole that would allow lighter weight and less material in the product.


## 2157 Section


As I am a 2157 student, we were additionally tasked to perform an FEA on the link that accompanies the bracket from the previous project. So as I did last time, I'm going to continue to do this same process of creating a finer and finer simulation on this CAD piece.


<img width="881" height="487" alt="Screenshot 2026-10-21 192754" src="https://github.com/user-attachments/assets/4f1815ca-8c53-45a2-9361-3bdb8ebad9b9" />


<img width="1208" height="605" alt="Screenshot 2026-10-21 193209" src="https://github.com/user-attachments/assets/600b3a47-b747-4f32-93f1-774dc74f9148" />


<img width="1222" height="627" alt="Screenshot 2026-10-21 193203" src="https://github.com/user-attachments/assets/226ca869-8433-4805-9bbf-4f3cfdb741de" />


<img width="1232" height="696" alt="Screenshot 2026-10-21 193159" src="https://github.com/user-attachments/assets/5e3b2157-70ed-4311-a0b4-9f7f04a0b6e2" />


<img width="961" height="480" alt="Screenshot 2026-10-21 193147" src="https://github.com/user-attachments/assets/69134af5-57b4-415b-a661-9bf5a7d963d1" />


<img width="1917" height="726" alt="Screenshot 2026-10-21 192941" src="https://github.com/user-attachments/assets/28b2354c-82da-4408-8863-24117b7f8486" />


<img width="1211" height="628" alt="Screenshot 2026-10-21 193219" src="https://github.com/user-attachments/assets/2e72a23b-00dc-4997-9054-1e23f333d2d1" />


<img width="1117" height="577" alt="Screenshot 2026-10-21 193758" src="https://github.com/user-attachments/assets/6110a701-ad5d-4dc1-9344-9a4c81e1f479" />


<img width="1120" height="587" alt="Screenshot 2026-10-21 193754" src="https://github.com/user-attachments/assets/bdbb4cd0-d39d-4e50-b24c-acf2dbae1c32" />


<img width="1167" height="681" alt="Screenshot 2026-10-21 193748" src="https://github.com/user-attachments/assets/649da2ed-0e21-4475-b273-4498b727ef41" />


<img width="608" height="492" alt="Screenshot 2026-10-21 193741" src="https://github.com/user-attachments/assets/a4119ed0-6c6a-4936-93b5-41f6747b1068" />


<img width="1232" height="512" alt="Screenshot 2026-10-21 193543" src="https://github.com/user-attachments/assets/4e685d8a-dcd9-4e0e-8e99-ef74a1fdeb29" />


<img width="1103" height="555" alt="Screenshot 2026-10-21 193539" src="https://github.com/user-attachments/assets/a872459e-0386-4fe8-95b9-92d32258199a" />


<img width="1183" height="668" alt="Screenshot 2026-10-21 193535" src="https://github.com/user-attachments/assets/7dc007e2-0aef-428c-ac73-e490296fddd3" />


<img width="795" height="467" alt="Screenshot 2026-10-21 193525" src="https://github.com/user-attachments/assets/11491eb3-5aac-4f5f-814e-bc6f670e81bb" />


<img width="1132" height="575" alt="Screenshot 2026-10-21 193808" src="https://github.com/user-attachments/assets/46b10a7f-1a5a-467d-bc12-b747a3cbc754" />


<img width="790" height="170" alt="Screenshot 2026-10-21 194052" src="https://github.com/user-attachments/assets/230d1066-8f46-4c30-8f0c-12507db4e549" />


## Link Reflection

After looking over the simulations for the link,It was highly expected that a piece of material taking that much force in such a small object would obviously deform it but I was left confused as to what could be improved on this because it did not suffer as much deformation as I expected it to do. This may have to do with the way it was designed with radiuses and its length to thickness ratio but nonetheless, it did surprisingly well. I think that a suitable upgrade to it  would be obviously thickening it as well as having the bracket support the link more effectively so less load is distributed on the link preventing catastrophic levels of deformation. 



## Communicate

[Bracket CAD file PRT](https://drive.google.com/file/d/1cxXJ0WOyvw5H4WOSh8-LoeXcfFTnBokY/view?usp=sharing)


[Link CAD file PRT](https://drive.google.com/file/d/1LOUmwl15q-MRAINotFSUhtDYvbtJo5Et/view?usp=sharing)
