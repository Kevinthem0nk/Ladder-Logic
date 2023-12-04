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

## Overbuilt Occupancy Counter
This is from PLC Fiddle's Occupancy Counter Challenge that I created and then added simulation and error-checking examples. Redundancy is achieved by counting in two methods for example purposes.
- Click Entry Sensor once to add an occupant.
- Click Exit Sensor once to remove an occupant.
- Click Simulate once to enable the simulation. This will count up to 'SimTarg' occupants and then back down to 0.

[Link to the example](https://www.plcfiddle.com:/fiddles/b4c40fb9-eee6-4c24-b7e4-11a13a961828)

## P, PI, or PID Control Loop
### This program switches between control modes. PLC Fiddle is very limited and cycles slowly, so the actual function of the PID is not performing to my liking, at least...
- Set the target value (default 1018) with HMItarget.
- Set 1 of P_Enbl, PI_Enbl, or PID_Enbl to select which.
- Enable/Disable the PID with PIDenable.
- The Start Button works to Start and Stop. Single click for function.
- The Stop works as Stop & Reset. Single click for function.

[Link to the example](https://www.plcfiddle.com:/fiddles/6a0cfe6d-2950-4e18-b00f-34793b73b760)
