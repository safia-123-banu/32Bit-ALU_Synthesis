## Ex No: 05  Implementation-of-32Bit-ALU-Synthesis-using-Cadence-EDA-Tools

### Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

### Tool Required:

- Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)
- Synthesis: Genus
  
### Procedure:

#### Step 1: Getting Started

- Synthesis requires three files as follows,
    + Liberty Files (.lib)
    + Verilog/VHDL Files (.v or .vhdl or .vhd)

#### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

- The Available technology nodes are 180nm ,90nm and 45nm.
- In the terminal, initialise the tools with the following commands if a new terminal is being
used.

    + csh
    + source /cadence/install/cshrc
    + The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.
    + Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

<br>
<br>
<br>
<br>
<br>
<br>

#### Synthesis RTL Schematic :

![Screenshot (42)](https://github.com/user-attachments/assets/de9d2cfa-6d57-4063-b82d-7d4988bf7d09)

<br>

#### Area report:

![Screenshot (36)](https://github.com/user-attachments/assets/e77cbeab-65ef-4184-861d-38577c45bfb7)

<br>
<br>
<br>
<br>
<br>
<br>

#### Power Report:

![Screenshot (37)](https://github.com/user-attachments/assets/1bc605a6-acc7-4893-bb19-3255ae833937)

<br>
<br>

### Result: 
The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
