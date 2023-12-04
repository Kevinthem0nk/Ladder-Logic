# Ladder Logic Examples Using PLC Fiddle

Explore a collection of Ladder Logic programs designed to showcase my proficiency. While these examples are relatively straightforward, with more time and effort, I can certainly produce more advanced and intricate programs. I am also proficient in other common PLC languages like Function Block Diagram and Structured Text, although creating easy examples in these languages is more challenging. Additionally, I am proficient in the Arduino IDE.

***PLC Fiddle is in no way comparable to full PLC Development Studios; there are some limitations.***

## Simple Example of a Staged Process
An Indexing motor turns a theoretical part into 5 stations that rotate with one active station at a time.
- Click Start or Stop to begin or end the process, respectively.
- You can change the timings by modifying:
  - Index time = IndexTimeTrig.PRE
  - Simulated operation length = OpTime.PRE

[Link to the example](https://www.plcfiddle.com:/fiddles/16401d77-b6ef-4840-9e73-e00bb098b8b4)

## Another Staged Process With Staged Sub-Operations to Each Operation.
This is similar to above buto stages 4 Sub-Operations under each Operation.
- Click the Start Button to Start or Stop the Loop.
- Click the Stop Button to Stop and Reset.

[Link to the example](https://www.plcfiddle.com:/fiddles/0c5aff6e-6d96-4caa-83e0-9984f686ebc9)

## Overbuilt Occupancy Counter
This is from PLC Fiddle's Occupancy Counter Challenge that I created and then added simulation and error-checking examples. Redundancy is achieved by counting in two methods for example purposes. It loads with the simulations started and will count up to the 
- Simulated max occupants = 'SimTarg'.
- Click Simulate once to stop or start the simulation. 
- Click Entry Sensor once to add an occupant.
- Click Exit Sensor once to remove an occupant.


[Link to the example](https://www.plcfiddle.com:/fiddles/b4c40fb9-eee6-4c24-b7e4-11a13a961828)

## P, PI, or PID Control Loop
### This program switches between control modes. PLC Fiddle is very limited and cycles slowly, so the actual function of the PID is not performing to my liking, at least...
- Set the target value (default 1018) with HMItarget.
- Set 1 of P_Enbl, PI_Enbl, or PID_Enbl to select which.
- Change the PID values with Kp, Ki, and Kd.
- Enable/Disable the PID with PIDenable.
- Click the Start Button to Start or Stop.
- Click the Stop Button to Stop & Reset.

[Link to the example](https://www.plcfiddle.com:/fiddles/6a0cfe6d-2950-4e18-b00f-34793b73b760)
