## MPI
MPI (Message Passing Interface) is a standardized and portable framework designed to enable 
communication between processes in a distributed or parallel computing environment. 
## Open MPI:
Open MPI is an open-source, high-performance implementation of the Message Passing Interface (MPI) standard. 

### Execution
#### C
To execute it here is the commands:
```
mpicc hw.c -o hello-world
mpirun --np 4 ./hello-world 
```

#### Python
To execute it here is the commands:
```
mpirun --np 4 python3 mpi_py.py
```
>[!Warning]
>If there is an issue running the code use ***oversubscribe*** in mpirun command:
>in C:
>```
>mpirun --oversubscribe --np 4 ./hello-world
>```  
