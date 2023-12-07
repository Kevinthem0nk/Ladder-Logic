# Ladder Logic Examples Using PLC Fiddle

Explore a collection of Ladder Logic programs designed to showcase my proficiency. While these examples are relatively straightforward, with more time and effort, I can certainly produce more advanced and intricate programs. I am also proficient in other common PLC languages like Function Block Diagram and Structured Text, although creating easy examples in these languages is more challenging. Additionally, I am proficient in the Arduino IDE.

***PLC Fiddle is in no way comparable to full PLC Development Studios; there are some limitations.***

***You may need to Zoom out in your browser for everything to fit.***

## Simple Example of a Staged Process
An Indexing motor turns a theoretical part into 5 stations that rotate with one active station at a time.
- Click Start or Stop to begin or end the process, respectively.
- You can change the timings by modifying:
  - Index time = IndexTimeTrig.PRE
  - Simulated operation length = OpTime.PRE


[Link to the example](https://www.plcfiddle.com:/fiddles/16401d77-b6ef-4840-9e73-e00bb098b8b4)

![image](https://github.com/Kevinthem0nk/Ladder-Logic/assets/83764173/3e8c7316-dde5-4c75-8fe0-19de272fe26a)


## Another Staged Process With Staged Sub-Operations to Each Operation.
This is similar to above but stages 4 Sub-Operations under each Operation using counters.
- Sub-operationg timer speed = stTmr.PRE
- Click the Start Button to Start or Stop the loop.
- Click the Stop Button to Stop and Reset.


[Link to the example](https://www.plcfiddle.com:/fiddles/f39047f9-c037-49ec-9c8a-b87027f8b2b3)

![image](https://github.com/Kevinthem0nk/Ladder-Logic/assets/83764173/a7d13185-17fd-4697-9f10-fc0ebb938b4c)


## Overbuilt Occupancy Counter
This is from PLC Fiddle's Occupancy Counter Challenge that I created and then added simulation and error-checking examples. Redundancy is achieved by counting in two methods for example purposes. It loads with the simulations started and will count up to the 
- Simulated max occupants = 'SimTarg'.
- Click Simulate once to stop or start the simulation. 
- Click Entry Sensor once to add an occupant.
- Click Exit Sensor once to remove an occupant.


[Link to the example](https://www.plcfiddle.com:/fiddles/b4c40fb9-eee6-4c24-b7e4-11a13a961828)

![image](https://github.com/Kevinthem0nk/Ladder-Logic/assets/83764173/ad979e19-a1fa-4c17-a6f1-500f570600f7)



## P, PI, or PID Control Loop
### This program switches between control modes. PLC Fiddle is very limited and cycles slowly, so the actual function of the PID is not performing to my liking, at least...
- Set the target value (default 1018) with HMItarget.
- Set 1 of P_Enbl, PI_Enbl, or PID_Enbl to select which.
- Change the PID values with Kp, Ki, and Kd.
- Enable/Disable the PID with PIDenable.
- Click the Start Button to Start or Stop the loop.
- Click the Stop Button to Stop & Reset.

[Link to the example](https://www.plcfiddle.com:/fiddles/6a0cfe6d-2950-4e18-b00f-34793b73b760)

![image](https://github.com/Kevinthem0nk/Ladder-Logic/assets/83764173/0a01162e-ba87-464d-9f33-8b78ada6a939)



## 5 Function Momentary Button.
### Single button control for 5 different commands.
- Clicking "Button" On and Off is a single click and function #1.
- Double and Triple click make up functions #2 and #3.
- Click and hold between 2-5 seconds is function #4.
- A 5 second hold triggers function #5.

[Link to the example](https://www.plcfiddle.com:/fiddles/e7822ae8-de38-464a-ac2f-cab7bd962ead)

![image](https://github.com/Kevinthem0nk/Ladder-Logic/assets/83764173/561ffbed-f59b-4413-b867-66a1e8504d3a)
