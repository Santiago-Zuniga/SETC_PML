# SETC_PML
Spatially evolving turbidity current with perfectly matched layers, for NEK5000 v19
Beware that despite the new planar_avg routine is being used, the slices still assumes a box-type mesh

## What's working:
+ Mean calculation routines, both time and spanwise seem to be working. 
+ Hydrostatic pressure is computed using the new routines.
+ i/o routines for means restarting
## TODO
+ Write perturbation routines
+ Write spanwise averaging (no time) routines and its i/o routines
+ Re-Write interpolation routines for inflow flow (maybe with the new interp routines? I wouldn't touch that atm)
## What's being tested:
+ Means restarting routines.
