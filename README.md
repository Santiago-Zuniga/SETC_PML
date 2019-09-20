# SETC_PML
Spatially evolving turbidity current with perfectly matched layers, for NEK5000 v19
Beware that despite the new planar_avg routine is being used, the slices still assumes a box-type mesh

# What's working:
+ Mean calculation routines, both time and spanwise seem to be working. 
+ Hydrostatic pressure is computed using the new routines.
# TODO
+ Write i/o routines
+ Write perturbation routines
+ Write spanwise averaging (no time) routines
+ ~~Write userdat1,2,3, useric~~
+ Fix userdat1 
+ Re-Write interpolation routines for inflow flow
