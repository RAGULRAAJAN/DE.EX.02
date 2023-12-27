# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.
## Procedure:
Create a New Project:
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA). 2. Create a New Design File:

Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language. 3. Write the Combinational Logic Code:

Open the newly created Verilog or VHDL file and write the code for your combinational logic. 4. Compile the Project:

To compile the project, click on "Processing" > "Start Compilation" in the menu. Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device. 5. Analyze and Fix Errors:*

If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window. Review and fix any issues in your code if necessary. View the RTL diagram.

*Verification:
Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF". Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All. Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform.
## Program:

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.


Developed by: RAGUL RAAJAN .T



RegisterNumber: 23007752 
# Code:
![Screenshot 2023-12-27 115522](https://github.com/RAGULRAAJAN/DE.EX.02/assets/147473144/f5d9c494-3d60-420c-b5ed-53c1faf632b6)


## RTL realization
![Screenshot 2023-12-27 115557](https://github.com/RAGULRAAJAN/DE.EX.02/assets/147473144/1add9a06-04f0-4e93-b943-883509263896)

## Truth Table:
![Screenshot 2023-12-27 115800](https://github.com/RAGULRAAJAN/DE.EX.02/assets/147473144/bcf42481-d30b-4f02-a7d9-9d4cffba6216)

## Output:
## Timing Diagram:

![Screenshot 2023-12-27 115816](https://github.com/RAGULRAAJAN/DE.EX.02/assets/147473144/35ed61ac-17dc-420b-a038-c3f28f104b9b)

## Result:
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
