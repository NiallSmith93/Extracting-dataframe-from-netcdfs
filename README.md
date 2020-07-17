# Extracting-dataframe-from-netcdfs
This notebook contains an adaptable script which takes individual netcdf files from a given direction and produces individual tabular data files (csv) with the flattened information.
The files used in this exercise only contained dimensions lat, lon, var and not time.
It also concatenates all of the individual files (timestep-scenario combinations) into a single dataframe for the variable (in this case precipitation).
Finally, there is some basic QA on the outputted dataframe.
