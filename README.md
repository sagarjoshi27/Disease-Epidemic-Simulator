# Disease-Epidemic-Simulator-using-SFML-and-C++
This was a group software development project. 

A Disease Epidemic Simulator has been developed using C++ and SFML in Visual Studio. 
The program uses the SIR model which is a mathematical model used for simulating epidemics with great accuracy. 
The program graphically represents the UK’s residents using a different colored pixel for individuals with a different relation to the disease such as infected, immune etc.
The program simulates a disease epidemic with accuracy and represent the infection visually to the user. 

There are three types in this picture:
* Susceptible - Default Colour
* Infected - Red Colour
* Recovered - Bright Green Colour

![](images/Picture1.jpg)

**The GUI**
* Start button to begin the simulation
* Stop button to stop the program
* Pause button to pause the simulation
* Some statistics for the simulation
* An element to alter the speed of the program
* Two input boxes to change probability of spread and recovery time. 

![](images/Picture5.png)


**Problems in the program**

The speed of the program was a critical problem since the simulation is doing thousands of calculations every frame so was quite slow. To overcome this we used an image buffer instead of directly updating the screen. 

