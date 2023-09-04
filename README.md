# Website in Progress...

#### Technical Skills: Python, Data Analytics, Arduino (in development)


## Education			        		
- B.S., Aeronautical & Astronautical Engineering, The University of Washington, Seattle Campus (_E.C.D. June 2026_)
- A.A., South Puget Sound Community College, Olympia, WA, Concentration: Engineering Physics (_June 2022_)

## Work Experience
**Configuration Aerodynamics Intern @ Boeing (_June - September 2022_)**
- Conducted data processing and analysis for a study evaluating the impact of an issue on 777-9 takeoff performance
- Other Thing

## Projects
### Arduino Telescope Modifications (IN PROGRESS)
[Telescope](assets/img/telescope)

[Arduino Kit](assets/img/arduino_kit)

  I recently bought this Bushnell Voyager Sky Tour 900mm x 4.5" Reflector Telescope at a garage sale for *$5*. That's the deal of a lifetime! But it's missing a couple of parts: the two lesser magnifying of the three eyepieces, the dial for fine vertical (altitude) adjustment, and the red dot finderscope... all items that help me aim the telescope. I could fix this with replacement parts, or I could engineer my own alignment system and add functionality that would otherwise be impossible!
Here's the plan:
- Hook up a $3 MPU6050 IMU to the exterior of the telescope, which has an accurate 3-axis accelerometer and gyroscope so I can read the telescope's current orientation.
- Write calibration script to convert current orientation into azimuth and altitude for the telescope's line of sight
  - Check while aiming telescope at an object and referencing Stellarium for true Az & Alt
- 
- 3D Print dial and Arduino attachment point
- lksdjflksdf

It will go through some design iterations to improve functionality:
- V1: Horizontal (azimuth) adjustment through analog (joystick) input
- V2: Both horizontal and vertical adjustment with joystick
- V3: Input altitude and azimuth of a celestial object and the arduino system will orient the telescope in that direction.

I thought this could make a super fun project that would allow me to apply my knowledge of Arduino circuits and coding, learn about telescopes, and upgrade mine for cheap! 


![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Freewing
[Publication](https://www.mdpi.com/1424-8220/22/11/4240)

Used **Matlab** to train over 100 machine learning models which estimated particulate matter concentrations based on a suite of over 300 biometric variables. We found biometric variables can be used to accurately estimate particulate matter concentrations at ultra-fine spatial scales with high fidelity (r2 = 0.91) and that smaller particles are better estimated than larger ones. Inferring environmental conditions solely from biometric measurements allows us to disentangle key interactions between the environment and the body.

![Bike Study](/assets/img/bike_study.jpeg)
