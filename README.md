Engineering manual

Future Engineers WRO 2024

Panama, Capira District

Robotics club IPT Capira

BETAS Team

![Logo](https://github.com/ROBOTICAIPTC/BETAS/blob/main/other/Logo-BETAS.jpg)

Members
- Sol Urieta
- Jose Bernal
- Roderick Zamora


====

This repository contains the engineering manual for an autonomous vehicle model that will participate in the WRO Future Engineers competition in the 2024 season.

## Content

* `t-photos` contains 2 team photos (one official and one fun photo with all team members)

- Formal Photo
![formal](https://github.com/ROBOTICAIPTC/BETAS/blob/main/t-photos/formal.jpg)

From right to left, Roderick Zamora, Sol Urieta, José Bernal

- Funny Photo
![funny](https://github.com/ROBOTICAIPTC/BETAS/blob/main/t-photos/funny.jpg)

From rigth to left, Sol Urieta, Roderick Zamora, José Bernal

- W1 wheel settings
![W1](https://github.com/ROBOTICAIPTC/BETAS/blob/main/t-photos/working.jpg)

- Robot verification, and W2 programming
![W2](https://github.com/ROBOTICAIPTC/BETAS/blob/main/t-photos/working-1.jpg)

- Programming W3
![W3](https://github.com/ROBOTICAIPTC/BETAS/blob/main/t-photos/working-2.jpg)

* `v-photos` contains 6 photos of the vehicle (from each side, from above and below)
  
- Superior
![superior](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/superior.jpg)

- Superior Frontal
![superiorfrontal](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/sf.jpg)

- Superior Posterior
![superiorposterior](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/sp.jpg)

- Right diagonal side dd
![dd](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/dd.jpg)

- Right side d
![d](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/d.jpg)

- Left diagonal side
![di](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/di.jpg)

- left side i
![i](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/i.jpg)

- Assembling the base assembly-base
![Assembling the base assembly-base](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/armado-base.jpg)

- Setting up the base setting-base-2
![Setting up the base setting-base-2](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/armado-base-2.jpg)

- Assembling the base, lower part assembly-base-bottom
![Assembling the base, lower part assembly-base-bottom](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/armado-inferior.jpg)

- Traction system assembly
![traccion](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/traccion.jpg)

 - Steering system assembly
![direccion](https://github.com/ROBOTICAIPTC/BETAS/blob/main/v-photos/direccion.jpg)

* `video` Video contains the video.md file with the link to a driving demonstration video

- Open Challenge: 

https://youtu.be/9Tzw0ZnRUY0?si=UGhT4n0KG4pu0JjZ

- Random Challenge

![random](https://github.com/ROBOTICAIPTC/BETAS/blob/main/other/Wheelie.gif)


* `schemes` Schemes contains one or more schematic diagrams in JPEG, PNG or PDF format of the electromechanical components that illustrate all the elements (electronic components and engines) used in the vehicle and how they connect to each other.

![Diagram](https://github.com/ROBOTICAIPTC/BETAS/blob/main/schemes/Captura%20de%20pantalla%202024-07-24%20230337.png)
![Diagram](https://github.com/ROBOTICAIPTC/BETAS/blob/main/schemes/Captura%20de%20pantalla%202024-07-25%20085829.png)
![Diagram](https://github.com/ROBOTICAIPTC/BETAS/blob/main/schemes/Captura%20de%20pantalla%202024-07-25%20085837.png)

We are working with a LEGO Spike Prime kit, which It is generally in the range of 330-400$$ USD. It is advisable to check with official LEGO Education distributors or reputable online stores to get the most current and accurate price.

#### LEGO Spike Prime Hub | Technical data
•	Nominal Voltage: 7.4V

•	Battery Capacity: 2100 mAh (milliampere-hour), battery Rechargeable lithium ion

•	CPU: ARM Cortex-M4

•	Memory: 32 MB storage, 1 MB RAM

•	Connectivity: Bluetooth, USB

•	Ports: 6 input/output ports to connect motors and sensors

•	Screen: 5x5 LED matrix

•	Integrated Sensors: Gyroscope and accelerometer

##### Engines
•	Wide Angle Motor:

o	Main Feature: High torque for traction

o	Connection: Compatible with Hub ports

o	Functions: Speed and direction control


•	Angular Motor:

o Main Feature: Precision steering control

o	Connection: Compatible with Hub ports

o	Functions: Precise steering angle control

##### Sensors
•	Distance Sensor:

o	Technology: Ultrasound

o	Function: Distance measurement and obstacle detection

o	Range: Up to 200cm


•	Color Sensors:

o	Function: Color detection and line tracking

o	Positioning: Can be placed in different parts of the robot 
According to the need of the project


Software

•	Programming Environment: Block-based, Python compatible

•	Connectivity: Spike Prime app available for computers and tablets

•	Features: Intuitive interface for programming and controlling the robot, ability to save and share programs


Structure and Parts

Building Blocks: Various LEGO Technic pieces to assemble the robot structure

•	Connectors and Shafts: To ensure a robust and flexible construction

•	Instruction Manual: Step-by-step guide to assembling various robot models and projects Educational Considerations

•	Learning Objectives: Promote skills in STEM (Science, Technology, Engineering and Mathematics)

•	Educational Level: Designed for primary and secondary school students

•	Projects Included: Various predefined projects and activities to develop problem-solving, critical thinking, and collaboration skills


* `src` Src contains control software code for all components that were programmed to participate in the competition
  
The programming begins with the event when the program starts, it is added to the motor section to adjust speed by 80% of the wide angle motor and from this same section to turn on the motorcycle clockwise of the wide angle motor.L


From the events section it is added: distance sensor when it is less than 65cm, from the motors stop the wide angle motor, adjust the speed to 50% wide angle motor, the control section is added wait for 0.3 seconds. Add turning on the wide angle motor motor then wait 0.3 second add from the motor section run the wide angle motor clockwise for one rotation, wait 0.3 seconds, adjust wide angle motor speed to 100% run the wide angle motor clockwise counterclockwise for 45 degrees, wait 0.3 seconds and turn on wide angle motor

Models is for model files used by 3D printers, laser cutting machines and CNC machines to produce vehicle elements. If there is nothing to add to this location, the directory can be deleted.


* `models` Other is for other files that can be used to understand how to prepare the vehicle for competition. It may include documentation on how to connect to an SBC/SBM and upload files there, data sets, hardware specifications, communication protocol descriptions, etc. If there is nothing to add to this location, the directory can be deleted.

* `other` Important Considerations: Findings, Problems and Results While building and programming the robot, we encountered several difficulties that affected our results. We recognize that there were significant difficulties, but we have managed to learn valuable lessons from each obstacle encountered.

#### Findings and Problems:

We encountered several difficulties in which the control of the turn signals did not work as we expected and the robot’s gears dislodged. With effort and perseverance, we have managed to improve these areas considerably.

#### Findings and Problems:
- In programming, we faced difficulties with color sensors. Despite having initially developed programs that were effective, unfortunately we lost one of them due to an unexpected incident. However, we have managed to rebuild it and are making progress to optimize its operation on the track.

#### Recommendations:
1. Detailed Documentation: It is essential to keep records of each challenge encountered and the solutions implemented to guide future developments and adjustments.

2. Focus on Continuous Improvements: Each difficulty experienced should be seen as an opportunity to learn and perfect both the design and programming of the robot.

3. Clear and Effective Communication: When presenting the results, it is crucial to highlight how each challenge has been overcome and how these advances contribute to the advancement of the project as a whole.
   
4. Recognition of Achievements: Celebrating every achievement, no matter how small, strengthens team morale and fosters a positive and productive environment.

These steps help us be more effective as a team and also help us improve the robot.
