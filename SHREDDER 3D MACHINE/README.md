[![Autodesk: Fusion 360](https://img.shields.io/badge/Autodesk-Fusion360-orange)](https://www.autodesk.com/products/fusion-360/overview?term=1-YEAR)

3D PRINTED SHREDDER MACHINE
==========
This mechanism is my final project for the course "Printing and Modelling 3d".The usage of the mechanism is pretty simple:you can shred up certain things like paper,bananas,etc . I chose this mechanism for two reasons: the first one is that I wanted to choose something practical ,and everyone can agree that a shredder can be pretty useful. The second reason is a silly one : the shredder that was in the presenting video (which will be mentioned later) reminded me of an old shredder toy that I used to love when I was a kid , so I just had to create it, for the nostalgia.

Details of the mechanism:
------------------------------
First , I will list all of the components :

- Mainbody--it is obtained from a lower part and a upper part that are glued together
- Support frame
- Feeding port
- Shredder shaft (two of them)-one also acts as an connecting rod for the crank
- Crank 

As an extra detail , I also added:
- Trashbin,which will have all of the shredder discharges
- Being more of a children toy than an shredder that people can use ,I wanted it to be more kid-friendly. Seeing the opportunity ,I tried sculpting in Fusion 360 to create a penguin that can make the project look cuter and more kid-appealing. <br/>
**!This components are not needed for the mechanism to work and are just a few additions.**
<details>
  <summary><i>How it works:</i></summary>

---
This shredder does not use any electricity,nor a motor , so it is a perfect option for a toy.In order to use the shredder , you need to spin a crank that will make one of the pins to rotate ,also rotating the blades on that pin.On each pin ,you also have a gear that will make the other pin spin when you rotate the crank.Also,the blades are reversed ,because when you spin the crank ,one pin will rotate in one way and the other one in the opposite way.

</details>

Joints and motion study:
------------------------------
In the .f3d file of the mechanism there will be three joints:the first one is between the crank and the pin ,using revolute.The other ones will be also revolute between the pins and the lower body of the shredder.In order to make the mechanism work properly ,I created two motion links between the crank joint and the other two.That way ,the mechanism will work properly:when the crank moves,the pins will move too ,including the blades.You can see it in the motion study named (shredder_motion) in which I made the crank go opposite of what the revolute joint is supposed too(not a problem for the mechanism in real life,considering it is not needed to move one way or another)-that way the blades can actually shred things.There will be another motion study in which it will be shown how the mechanism works if the crank is rotated the other way around.

Important details
------------------------------
🚀 File types in this repository are .f3d, .stl, .png and .mp4 

🔌 **Programs used for making this mechanism:** Fusion 360 for designing andcreating the motion study.

📜 **The original design of this shredder machine is created by a prusaprinter named transformator2020 ,here is a link to his account:**
- **https://www.prusaprinters.org/social/85941-transformator2020/prints** 
- **I also took inspiration from one youtuber who made this mechanism ,named Eureka [video](https://www.youtube.com/watch?v=ltVqj0MW_hQ)**

!Final look of the project!
======
<img src="https://github.com/chivucatalin/Chivu-3DMP/blob/main/SHREDDER%203D%20MACHINE/RENDERS/position1.png?raw=true" width="800px" height="auto">
