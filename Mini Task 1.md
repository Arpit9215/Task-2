# Task-2
## Problem Statement
The problem statement is to make a smart spectacles for the auditorily impaired person that alert the person by glowing the LED at a particular area on the glass of spectacles in stimuli to sound coming from the paricular direction.
## Ideation and Planning
1) We have to make a smart spectacles that have many small microphones embedded in the frame of the spectacles to determine the direction of the sound.
2) Then we can use sensors like ultrasonic sensor and determine the distance of the source of sound by emitting a singnal by sensor in the direction of the sound.
3) Then we can code the microcontroller like Arduino or ESP32 according to the data of distance.
4) We can use LED RGB for the purpose to display different lights for differnet distance values, for example , red for close ditance , blue for moderate distance and green for far distance . 
5) This will not only tell the direction from where the sound is coming but also help the auditorily impaired persons with the extra data of distance of the source.
## Components
### 1) MEMS Microphone
a) We install a number of microphones in the frame of the spectacles .

b) We can code these microphones and can determine which microphone records the maximum intensity ,hence that is the direction of the sound.
### 2) Arduino
a) It is a microcontroller to govern the operation in the system , act as a commander of the circuit .

b) It activates the ultrasonic sensor in the direction of sound and later glows the LED according to direction and distance of sound 
### 3) Ultrasonic sensor 
a) It is a sensor used to determine the distance of the object .

b) In our project we can also find the distance of the sound source , hence indicate this message by glowing red (near) , blue (moderate) , green ( far) lights hence giving the auditorily impaired persons a extra information of distance of the sound source 
### 4) LED RGB 
a) It is a LED having three different colours red ,blue and green .

b) In our project , We can use this 3 different colours for showing the presence of the sound also helps us to give a extra information of diatance determined by utrasonic sensor.
## Prototyping 
Once We have a plan and components ready we start with assembling the components and desiging a PCB for the circuit .Also try to seacrch for alternatives , for exmaple , ultrasonic sensor is quite big , so we can try to find or made a new sensor that is more compactable than ultrasoinc sensor . Also we have to make the prototype with least expenditure as much as possible 
## Manufacturing 
Once We are done with prototype we can go to next step of testing it in a extreme conditions to check its strength , durability . Also we can take the reviews of general public (target audience - auditorily impaired persons) and we can alter some changes or any improvement needed in the design according to tests and public review . After all this we can finaaly come up with our final product - SMART SPECTACLES .
