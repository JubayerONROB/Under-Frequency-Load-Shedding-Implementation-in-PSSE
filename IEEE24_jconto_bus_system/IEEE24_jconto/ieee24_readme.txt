IEEE24 case = Power System + Dynamic data
24 Bus Power Flow Test Case

Original dyre were tuned to eliminate suspect conditions.

Adjust paths in the idv files to suit your configuration.  
Use of relative paths are recommended.

Set-up for PSSe v.33:
[When running from the PSSe GUI, comment the 'stop' command by the end of the divs]
1- run MAKECNVSNP.idv from within PSSe:
   It loads the .sav case "IEEE24_v33.sav" and
   it creates a converted *.cnv file using the "conl.idv" and
   a snap *.snp file, using the "ieee24.dyr" file
2- run RUNFLAT.PY from within PSSe:
   It performs a no-disturbance test, creating an *.out file
   with channels (monitored vars) defined in "channels.idv"
3- run GETDEVS.IDV from within PSSPLT, the plotting tool in PSSe
   It output to a file the max deviations for selected channels
All steps are logged.

All the above steps are executed in sequence by running:
Open a dos windows and run
  ieee24_flat.bat [rename the *.tab file to *.bat]

It should works in v.34 as well.
 