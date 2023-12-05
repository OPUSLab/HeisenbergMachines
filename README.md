# Heisenberg machines with programmable spin-circuits (SPICE codes) 

This *GitHub repository* provides the code used in "**Heisenberg machines with programmable spin-circuits**" for emulating the classical Heisenberg model using spintronics. Simulation files are provided for an example of a 2-LBM system. For more details and source codes, also visit: https://nanohub.org/groups/spintronics

See the link for the arXiv paper: https://arxiv.org/abs/2312.01477.pdf


# Simulation Files
HSPICE Files:
 - Main.sp: Main file used to simulate the 2-LBM system by calling the sub circuits (LLG,NM,FM_NM).
 - LLG.sp: Landau-Lifshitz-Gilbert (LLG) Module
 - NM.sp: Normal Metal Module
 - FM_NM.sp: Interface Module (between a Ferromagnet and a Normal Metal).

   
## How to run the simulation
<div align="justify">
The codes are written using the standard circuit simulator HSPICE, to run the simulation you only need to run the <b>Main.sp</b> file in the <code>HSPICE</code> directory. The simulation results are saved in <b>Main.printtr0</b> in columns format, with the current parameters, the output file would be around 2 GB.
</div>

