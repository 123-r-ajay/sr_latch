# project: implementing the SR_LATCH LAYOUT.

Design , simulate and layout  an SR latch using NMOS (nchannel MOSFET) and PMOS (p-channel MOSFET) transistors in the
180nm technology using Cadence software.
# 1. Introduction:
The objective of this lab experiment was to design and simulate an SR latch using NMOS (nchannel MOSFET) and PMOS (p-channel MOSFET) transistors in the 180nm technology using Cadence software. The SR latch is a fundamental circuit used in digital electronics to store and retain one bit of information. It consists of two cross-coupled inverters that latch the inputs and maintain their state until a specific input combination triggers a state change. The Cadence tool provided a platform to design and simulate the SR latch, allowing for analysis of its behavior and performance.

# 2. Design and Methodology :
The SR latch was designed using the Cadence Virtuoso schematic editor and simulated using the Spectre circuit simulator. The following steps were followed for the design and simulation:

# 2.1. Schematic :
The SR latch schematic was created by connecting two cross-coupled inverters, each consisting of an NMOS and a PMOS transistor. The inputs S (Set) and R (Reset) were connected to the gates of the respective transistors, and the outputs Q and Q̅ were taken from the drains of the NMOS and PMOS transistors, respectively. The NMOS and PMOS transistors were implemented using 180nm CMOS technolog

# 2.2. Layout Design:
After the schematic design, a layout was generated using the Cadence Virtuoso Layout Editor. The layout was created by placing and routing the NMOS and PMOS transistors according to the design rules and guidelines for the 180nm technology.

# 2.3. Design Rule Check (DRC) :
A Design Rule Check (DRC) was performed to verify that the layout adhered to the design rules of the 180nm technology. The DRC ensured that there were no violations related to minimum spacing, minimum width, and other layout constraints.

# 2.4. Layout vs. Schematic (LVS) :
Check A Layout vs. Schematic (LVS) check was conducted to ensure the layout matched the original schematic design. The LVS check compared the connectivity and characteristics of the schematic and layout, verifying their consistency.

# 2.5 Layout vs. Schematic (run quantus) :
Launch the Cadence Design Environment and open your design project.

Prepare your design files, including the layout database (GDSII) and the extracted netlist.

Set up the Quantus configuration, specifying the appropriate technology library, design rules, and other parameters.

Run the Quantus tool, which will perform electrical rule checking and design rule checking on your design.

Review the results and resolve any violations or issues identified by Quantus.

Repeat the process as necessary, making any necessary design modifications and re-running Quantus until the design passes all checks.

Run quantus run successfully.

Go to file and open creat the config and give the av_extracted.

# 2.6. CONFIG (layout)Simulation :
The SR latch was simulated using the Spectre circuit simulator. The simulation setup included defining the input stimulus, specifying the desired operating conditions, and setting the analysis parameters. The inputs S and R were driven by voltage sources to provide different input combinations, while the output Q and Q̅ were observed during the simulation.

# 3. Results and Analysis:
The SR latch was simulated for various input combinations to observe its behavior. The simulation results demonstrated the expected behavior of the latch based on the truth table of an SR latch. When S=0 and R=0, the latch maintained its previous state. When S=0 and R=1, the latch was reset, and the output Q was set to 0. Similarly, when S=1 and R=0, the latch was set, and the output Q was set to 1. Finally, when S=1 and R=1, an indeterminate state or metastable state was observed.

# 4. Conclusion :
The design and simulation of an SR latch using NMOS and PMOS transistors in the 180nm technology with Cadence were successfullY
