# Parallel programs
Covers all programs and description for each program for parallel programming lab internals


## Executions


mergesort 
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
fibonacci 
```
gcc -fopenmp -o obj fib.c
./obj
```
prime
```
gcc -fopenmp -o obj prime.c
./obj
```
vector addition
```
gcc -fopenmp -o obj vec.c
./obj
```
sum of 100 numbers
```
gcc -fopenmp -o obj sum.c
./obj
```