 NAME: imthiyas ahamed 
 
 REG NO: 21222490108
 
 IMPLEMENTATION OF JKFLIPFLOP 

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**
1.Launch Quartus on your computer and create a new project:
Go to File → New Project Wizard.

Specify the project name, directory, and top-level entity name (e.g., JK_FlipFlop).

Create the JK Flip-Flop Circuit and implement the JK Flip-Flop by writing VHDL/Verilog code.
Go to File → New → Select Verilog File.

Compile the Project
Click on Processing → Start Compilation.

Fix any syntax or schematic errors if present.

Simulate the Circuit:
Go to Tools → University Program VWF.

Define the inputs for J, K, and CLK in the waveform editor.

Run the simulation and observe the waveforms.

Verify the Results.
Compare the simulated results with the truth table for a JK Flip-Flop.


### PROGRAM:

![Screenshot 2024-12-12 104822](https://github.com/user-attachments/assets/ef4849e7-0b60-4ff3-a964-f77a714f44ad)

### RTL LOGIC FOR FLIPFLOPS:
![Screenshot 2024-12-12 103256](https://github.com/user-attachments/assets/0be35d9a-d85e-49a6-b734-7e8e7b5832ba)

### TIMING DIGRAMS FOR FLIP FLOPS:
![Screenshot 2024-12-12 104758](https://github.com/user-attachments/assets/6938f8e1-dbd5-4230-8ac3-660155e6a476)

### RESULTS:
Designed and verified the implimentation of JK flipflop circuit and truthtable in quartus ii using verilog programming successfully.
