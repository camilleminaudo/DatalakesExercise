# DatalakesExercise

You will find in this repository an example of the data collected recently in Lake Geneva with the autonomous profiler Thetis.

We have selected several variables, as indicated in filenames, all of them follow the same organization:

spatiotemporal matrices, columns correspond to profiles at a specific date indicated on first row (seconds since 01/01/1970 at 00:00:00)
all other rows correspond to different depths with a 10cm resolution, i.e. depth 0m on row 2, depth 0.10m on row3,...etc... until depth 50m on row 502.

Not assigned values are specified with the code "NA".

Due to technical reasons, matrices may not have the same number of columns and lines, i.e. not the same number of valid profiles.
