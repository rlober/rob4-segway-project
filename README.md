# Segway Project Overview

### Major Objectives

*Principle objectives*

- budget < 500 euros
- form factor: 15-20 x 25-30 x 10-15 cm
- Raspberry Pi for control
- Controllers written in Matlab
- Rechargeable battery

*Optional objectives*

- Communication with computer (radio/wifi/bluetooth)
- Modular attachments to convert to unicycle or add a camera.

### Milestones

- End of April: Full design conception.
- End of May: All parts ordered/delivered and construction started.
- End of June: Construction complete and working communication with Matlab. Ideally working controller as well.

- Begining of September: Working prototype. Full API and hardware (electronic and mechanical) documentation. Report summarizing work.

# Proposed decomposition of Work

## Dynamic feasability study

- Feasibility study: What kind of motors will be needed to accurately control the segway given the dynamics of the robot?
- Choose motors which are available with the agreed upon suppliers
- Determine supporting electronics (power supply, motor control, ...)
- Design chassis to support electronics
- Calculate dynamics for the desired design and confirm choice of motors.

## Raspberry Pi & Matlab
- Test communication and cross compilation with Matlab.
- Controlling a motor, getting data from encoders...


## Simulation of segway in Matlab
- Continuous time
- Discrete time
- Visual simulation (in gazebo would be a plus)
- Controller synthesis
