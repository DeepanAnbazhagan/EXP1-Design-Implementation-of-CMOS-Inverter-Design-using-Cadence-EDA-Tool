## Ex No: 01     Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools   

## Aim:
To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

## Tools Required:
•	Personal Computer
•	Cadence Virtuoso Software

## S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window.
2.	Type the following commands as follows and press enter.
	•	csh
  •	source /cadence/install/cshrc
  •	virtuoso

## Procedure for Schematic simulation using Cadence

1.	Now two windows must open
	i) virtuoso/command interpreter window
  ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


## i)	Procedure for Creating New Library.
•	File –New – Library
•	Name: Give name for ur library Ex: VLSILAB_EXP_1
•	Enable Attach to an existing technology library, Click OK
•	Attach the library to the technology library gpdk045.Click OK

## ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)
•	File-New-Cell view
•	Setup the new file form
•	Library: Select the one you created.
•	Cell: Give the experiment name Ex: Inverter ViewSchematic
•	Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
•	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
•	Click on browse. This opens the library browser
•	Now select the appropriate library for components like 
•	Gpdk45 ------------------------nmos1v, pmos1v
•	Create Input and Output pins
•	Make the connections by using fixed narrow wire key
•	Click Check and Save button
![Screenshot (103)](https://github.com/user-attachments/assets/7871eb7f-1d81-4718-bafd-75245c9dd8ba)



 
## iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 
•	Create – Cell view – From Cell view
•	The cell view from cell view window appears
•	Check Lib Name, Cell Name, From View name must be schematic Press ok
•	Now Symbol generation form appears. Click Ok If No changes required
•	A new window with with default symbol is created.
•	Edit the symbol if you want to give actual symbol shape else continue.
•	Execute Create-Cell view-from cell view
•	Library Name and Cell Name must be same which you have used for schematic. Press OK
•	Check for the position of pin side.Prss OK
•	Edit for the shape by Create-Shape-Choose required options to edit.

![Screenshot (104)](https://github.com/user-attachments/assets/5a23df05-28e9-4112-80ff-78f269a44f5e)



## iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view
•	Setup the new file form
•	Library: Select the one you created.
•	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
•	View: Schematic
•	Type: Schematic press OK
•	Follow the step 3(ii) d to make the required connections
![Screenshot (105)](https://github.com/user-attachments/assets/4e59e5c8-6ddd-4ed0-b9f4-017d8661529c)



 
## Analog simulation by SPECTRE.
•	In test cell view window
•	Launch – ADE L(Analog Design Environment)
•	Execute Setup—Simulation/directory/Host A new window opens
•	Set the simulation window to spectre and click ok
•	Execute Analysis – Choose. A window opens.
•	Select the type and set the specifications and press OK
•	Execute Output s—to be plotted – Select on Schematic
•	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
•	Execute Simulation -- Net list and Run
![Screenshot (106)](https://github.com/user-attachments/assets/ebb8c230-54a5-4c31-a702-75ca2bf2d316)


## For Transient Analysis Settings and Output
 
 
 ![Screenshot (109)](https://github.com/user-attachments/assets/f7bb4ac3-193f-4cc8-b44c-e71caac7a98c)


 ![Screenshot (98)](https://github.com/user-attachments/assets/a6a66a87-c4fb-4a87-82b9-774ebe7b18ab)


## For DC Analysis Settings and Output
![Screenshot (108)](https://github.com/user-attachments/assets/b3ae75ee-8359-4e94-8cfa-681da48be740)


![Screenshot (107)](https://github.com/user-attachments/assets/9d9d73e3-b9a8-4755-86c7-2cd13a8122b6)


 




 

## Results:
1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











