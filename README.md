# RML_anim
Animations for the paper &lt;Simulation of reversible molecular mechanical logic gates and circuits>

Note: viewing these animations requires that you have VMD installed.
In order to view the trajectory files as animations within VMD, download the folder and navigate the present working directory in the VMD console to it. Type the command "source anim.tcl" and hit enter. You will be prompted to enter the name of the trajectory you wish to load. Below is a list of the trajectories in this folder and the systems they correspond to in the paper:

driver - The driver initialised to '1'. The trajectory depicts one full cycle of the driver.

doubleBit - The double-bit system with input bit initalised to '1' and storage bit initialised to '0'. The trajectory depicts the process by which the storage bit is overwritten by the input bit as described in section IV.

nandNeut00, nandNeut01, nandNeut11 - The NAND gate linked to a pair of drivers initialised to the states '00', '01' and '11'. The trajectory depicts the process described in section Va.

nandSwitch1100 - The NAND gate linked to a pair of switches initialised to the state '11' and driven to the states '00'. The trajectory depicts the process described in section Vb.
