# cuda_sort
CUDA Implementation of Merge Sort

Further optimizations need to be considered as two kernels are currently
called to sort and merge the blocks. No Dynamic Parallelism used as
current GPU does not support Compute Capability 3.5 and above.
