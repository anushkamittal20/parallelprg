# parallelprg
Covers all programs and description for each program for parallel programming lab internals

Mergesort execution
```
gcc -fopenmp -o obj mergesort.c
./obj
```
pi
```
gcc -fopenmp -o obj pi.c -lm
export OMP_NUM_THREADS=1 
./obj
```
iterations
```
gcc -fopenmp -o obj iter.c
export OMP_NUM_THREADS=2
./obj
```
