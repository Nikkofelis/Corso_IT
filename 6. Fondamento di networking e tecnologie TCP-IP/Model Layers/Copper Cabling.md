Data is transmitted on copper cables as electrical pulses. However, the farther the signal travels, the more it deteriorates. This is referred to as signal **attenuation**.

The timing and voltage values of the electrical pulses are also susceptible to interference from two sources:

- **Electromagnetic interference (EMI) or radio frequency interference (RFI)**: EMI and RFI signals can distort and corrupt the data signals being carried by copper media. Potential sources of EMI and RFI include radio waves and electromagnetic devices.
- **Crosstalk**: Crosstalk is a disturbance caused by the electric or magnetic fields of a signal on one wire to the signal in an adjacent wire.

## Types of Cabling

### Unshielded twisted-pair (UTP)

UTP cabling is the most common networking media. UTP cabling, terminated with RJ-45 connectors.

Types: 

- **Ethernet Straight-through**: The most common type of networking cable. It is used to interconnect two devices of different families (MDI and MDIx). It has the same standard in both ends (both T568A or T568B).
- **Ethernet Crossover**: A cable used to interconnect devices of the same family. However, crossover cables are now considered legacy as NICs use medium-dependent interface crossover (auto-MDIX) to automatically detect the cable type and make the internal connection. It has a different standard on each end (T568A on one end and T568B on the other).

### Shielded twisted-pair (STP)

STP cables combine the techniques of shielding to counter EMI and RFI, and wire twisting to counter crosstalk.
Compared to UTP cable, STP cable is significantly more expensive and difficult to install.

### Coaxial cable

There are two conductors that share the same axis.
