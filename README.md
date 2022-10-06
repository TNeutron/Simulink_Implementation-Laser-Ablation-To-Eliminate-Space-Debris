# Simulink Implementation: [Modeling Laser Ablation To Eliminate Space Debris in Simulink](https://github.com/TNeutron/Simulink_Implementation-Laser-Ablation-To-Eliminate-Space-Debris/new/master?readme=1)

This is a Simulink Implementation of a model designed by Sang H. Choi and Richard S. Pappa from the NASA Langley Research Center, which includes realistic parameters that are likely to exist in a real situation.

![image1](https://miro.medium.com/1*9fhW7bHYdvP2tjjOgz0Wew.png)

Based upon the input parameters mentioned below include the following:
1. Laser energy (J)
2. Laser wavelength (m)
3. Debris velocity (m/s)
4. Debris weight (kg)
5. Plasma ejection velocity (m/s)
6. Laser-debris collision angle (degrees)
 
 
This model can calculate and output the following parameters:
1. Transferred laser momentum (x)
2. Transferred laser momentum (y)
3. Post-collision debris momentum (x)
4. Post-collision debris momentum (y)
5. Post-collision debris velocity (diagonal, using Pythagorean's theorem)

To exemplify my simulation in use, we can use this model. This model was implemented following the article written by Chole Wang. 
I have added dashboard library features to easily change the input parameters and calcualte outputs on the go.


![Image](https://i.imgur.com/F2SaJ5K.png)
