# ABAQUS Codes for AM Process of Tantalum
This repository contants INP files and subroutine codes which are used for simulation of AM process in ABAQUS.


## Single layer and single track model with power of 600W and speed of 1000mm/s.
#### Thermal simulation
"MeltPool_1000mms-1_10mA.inp"  is the INP file.

"umatht_Ta_1000mms-1_10mA.for" is the UMATHT and DFLUX code.


## Multiple layers and multiple tracks model with power of 600W and speed of 1000mm/s.
#### Thermal simulation
"Multiple layers and multiple tracks_Thermal simulation_600W.inp"  is the INP file.

"umatht_Ta_2Layers1000mms_10mA-4mm.for" is the UMATHT and DFLUX code.

#### Mechanical simulation
"2Layers_1000mms-1_10mA_4mm_020mm_Stress_PA.inp" is the INP file.

"2Layers_1000mms-1_10mA_4mm_020mm_Stress_PA-Restart-1.inp" is the restart INP file for final cooling step.

"uepactivation_JJ_vol2.for" is the UEPACTIVATION code for prograssive element activation.

## BCC lattice structure
#### Thermal simulation
"Model-BCC_PerBC-1-1-5-PerBC.inp" is the INP file for the thermal simulation of BCC lattice structure.

"umatht_Ta_Path_360W_5e-4s_1-1-5_PerBC.for" is the UMATHT and DFLUX code for the thermal simulation of BCC lattice structure.

#### Mechanical simulation
"Model-BCC_PerBC-1-1-5-Stress-noNG-ZBC-PA.inp" is the INP file for the mechanical simulation of BCC lattice structure.

"uepactivation_JJ_vol2.for" is the UEPACTIVATION code for the mechanical simulation of BCC lattice structure.
