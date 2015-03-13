compiling:
mpicc -o execName sourceFile.c

ie: mpicc -o ej1 ejercicio1.c

executing:
mpiexec -np numProc execName

where:
-numProc is the number of procesor you want to run the program, in order to maximize the paralelist you should use 
as many procesor as your computer can run, ie i7 procesor that have 4 cores and 2 thread per core u can maximize the speed
of the program using -np 8
