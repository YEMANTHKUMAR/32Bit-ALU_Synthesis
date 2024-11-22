# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-19 at 2 44 49 PM](https://github.com/user-attachments/assets/c506adb8-3114-4e4e-b8ed-f3bb2bcea791)

#### Area report:
![Screenshot (151)](https://github.com/user-attachments/assets/882348aa-5b21-41bf-8ce3-20b0b89d8297)

#### Power Report:
![Screenshot (150)](https://github.com/user-attachments/assets/f33d1cca-837e-47da-bc91-0ed1bf2abf5b)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
