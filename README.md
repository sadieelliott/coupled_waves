# coupled_waves

This code reads in the RBSP filterbank data, takes the fft of each filterbank bin and finds peaks in the fft using a defined window size and standard deviation 

The input parameters for the script are the following:
Time range (usually entire days)
Spacecraft (either rbspa or rbspb)
Type of filterbank data (peak or average)
Bin number (each bin is associated with a different frequency)
Standard deviation 
Window (how many data points to use for the running average)

This script is intended to be run using the 'run batch' tool in Autoplot to generate pngs and data files with peak dections 
