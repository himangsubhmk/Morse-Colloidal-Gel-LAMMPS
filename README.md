The first script named in.gel-equilibration_nve-langevin is used for gel preparation from a random initial configurations. The script needs initial random configuration morse_input_phi0.2003.lmp and the pair potential file in.morsepaircoff and both of them should be kept in the same folder where it runs.

The interaction parameter e_0 is defined in the script as morse_well_depth which is set as 10 in this case. After running the langavin dynamics for 30000000 time step on get the gel configuration, for example in the folder the file gel_restart.30000000.data

execution:
./lmp_mpi -in in.gel-equilibration_nve-langevin

This will produce the file gel_restart.30000000.data
