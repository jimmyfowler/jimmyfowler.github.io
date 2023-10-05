# About Me
Hello!

![Portrait](img/portrait_circle_small.png)

My name is James Fowler, but I go by Jimmy. I'm a student at the University of Washington studying Aeronautical & Astronautical Engineering. I have always loved space and initially planned to study astrophysics. But after seeing the hands-on, tangible contributions engineers can make towards space exploration, I made the switch. Though cosmology still has a special place in my heart, I want to be a part of the mission to explore our solar system, attain lunar permanence, set foot on Mars, and see what kinds of resources we can find on asteroids and icy moons to improve our lives on & off planet Earth.

I love coding, CADing, Arduino-ing, and am currently looking for opportunities to apply those to space exploration! 

# Portfolio

#### Technical Skills: Python, Data Analytics, Arduino, CAD

### >> [What I'm Workin on Now](#aimduino-august-2023---present) << click it!

## Education			        		
- B.S., Aeronautical & Astronautical Engineering, The University of Washington, Seattle Campus (_E.C.D. June 2026_)
- A.A., South Puget Sound Community College, Olympia, WA, Concentration: Engineering Physics (_June 2022_)

## Work Experience
**Configuration Aerodynamics Intern @ Boeing (_June 2022 - September 2022_)**
- Conducted data processing and analysis with Python for a study evaluating the impact of an issue on 777-9 takeoff performance
- Found the predictive accuracy of the simulation tool through an iterative, scripted (Python) process
  - Gave a technical presentation on the accuracy of the tool and how it should be used

**Web Developer @ The Academy of Lacey (_March 2022 - Present_)**
- Train new employees on tool setup and work procedures
- Collaborate with a team of developers to manage over 100 websites owned by Washington State agencies 
- Utilize Linux command line, HTML, CSS, Javascript, and Git repositories


## Projects
### **AIMduino (_August 2023 - Present_)**
![Telescope](img/Telescope.png)

I recently bought this Bushnell Voyager Sky Tour 900mm x 4.5" Reflector Telescope at a garage sale for *$5* (what a steal!), but it's missing a couple of parts: the two lesser magnifying of the three eyepieces, the dial for fine vertical (altitude) adjustment, the handset meant to guide you with audio, and the finderscope... all items that help me aim the telescope at my celestial target. I could fix this with $100+ in replacement parts, or I could engineer my own alignment system and add functionality that would otherwise be impossible!
I'm calling it *AIMduino* (working title)... Here's the plan:
- Hook up a $3 MPU6050 IMU to the exterior of the telescope, which has an accurate 3-axis accelerometer and gyroscope so I can read the telescope's current orientation.
- Write calibration script to convert current orientation into azimuth and altitude for the telescope's line of sight
  - Use Stellarium while aiming the telescope at the moon (easy to find) to compare to true Az & Alt, iterate calibration script as needed
- 3D Print rotator hardware and Arduino circuit attachment point
  - Use UW's maker spaces for 3D printing equipment, and mechanical engineering friends for design assistance
- Make a double stepper motor circuit (one for each axis)
  - Rotate horizontally until hitting target Azimuth, then rotate vertically until hitting target Altitude. 

It will go through some design iterations with check-in points:
- V1: Manual orientation/aiming while monitoring Az & Alt outputs
- V2: Horizontal rotation achieved through single stepper motor circuit, controlled with a switch. 
- V3: Input Azimuth to rotate horizontally
- V4: Input Az & Alt of a celestial object and the AIMduino will orient the telescope automatically

I thought this could make a super fun project that would allow me to apply my Arduino and coding knowledge, learn more about telescopes, and upgrade mine for cheap!

Come back later to see updates on this project.

### **Learning Arduino (_June 2023 - Present_)**
![Arduino Kit](img/arduino.jpg)

Over the Summer, I completed six Arduino projects led by a starter kit book. The goal was to learn circuit design and coding with a variety of instruments and solidify my passion for Arduino.

### **CADing Perseverance**
At the end of my course on CAD & Visual Communication, we were prompted to model an original assembly of our choice. It was open-ended, but we had to include everything we learned in the class. I chose to model NASA's Mars Perseverance Rover. Even though I kept to a relatively low level of detail, this project was an incredible undertaking, especially while handling other finals.

What I wanted was something that looked mildly realistic, and had some realistic mechanical motion.

![Rover Render](img/rover_render.jpg)

I utilized a plethora of mates between each of the 18 parts, and followed best practices while modeling each indiviudal part, and while putting them all together in the assembly.

Here's the project assignment description for more details on requirements. Below that is a .zip with my assembly file and all part files and drawings. Feel free to check it out for yourself!

[Final Project Spring 2023.pdf](https://github.com/jimmyfowler/jimmyfowler.github.io/files/12814128/Final.Project.Spring.2023.pdf)

[Fowler_J_FINAL_Rover.zip](https://github.com/jimmyfowler/jimmyfowler.github.io/files/12814307/Fowler_J_FINAL_Rover.zip)


### **Building an RV-12 (_May 2023 - Present_) (Husky Flying Club)**
I am currently leading a team of 12 engineers to machine and assemble aircraft parts. I Conduct & coordinate team meetings and allocate work to other student engineers on the project. I'm also planning & writing operations & legal documents with an experienced aerospace lawyer.

### **Freewing (_December 2022 - April 2023_) (Husky Flying Club)**
During my Freshman year with the Husky Flying Club, I built a freewing canard, radio-controlled aircraft with a ten-foot wingspan costing $3500 in parts. I helped organize our engineers into subteams based on interests and experience and then participated in weekly build meetings to construct the aircraft. I also wrote 8 pages of legal documents in order to safely and legally test-fly our plane once it was built.





