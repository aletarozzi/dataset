The following dataset consider the downlink communication between a base station (BS) and various receivers. 


It is structured as (d, PL, category), where d [m] represents the 3D distance between the transmitter and receiver, PL [dBm] is the path loss obtained on the receiver side, and category indicates the line-of-sight (LoS) or non-LoS (NLoS) condition between the BS and receiver.  In this context, various dataset are provided for different transmitter height htx=[2,10]m from the ground and for various receivers. Receivers are considered to be automated guided vehicles (AGVs), uniformely distributed in the facility, or machine nodes (MNs), which are located on top and along the edges of the machines. In particular, category=1 is assigned to cases of LoS and category=0 to NLoS conditions. 
Different datasets are provided for various machines densities (MD), with MD =0.08, 0.24, 0.36, defined as the ratio between the area covered by the machines and the total area of the facility. 
The following dataset was generated through the simulation of an industrial environment at various frequencies, including 3.5, 60, and 300 GHz, utilising the 3DScat ray-tracing tool, developed at the University of Bologna. Specifically, the path loss at 300 GHz takes into consideration also additional attenuations due to molecular absorbtion.





