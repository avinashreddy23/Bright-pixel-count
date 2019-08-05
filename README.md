# Bright-pixel-count
MPI, opencv, numpy,scipy

Authors @ --- Avinash Reddy Yenumula --- Disney Davis koala --- Lokesh Reddy Gundla --- @

**********************************
Bright Spots Detection Using MPI
**********************************

In this project we have counted the number of bright pixels using python for MPI and openCV. In this folder we have two python program files, one uses collective communication 
and other file uses point to point communication.

Prerequisite Libraries
*OpenMPI/MPI4py
*OpenCV
*NumPy
*SciPy

1) Collective Broadcast - This process will compute number of bright spots for any given 
Image using collective communication.


Command to run the code
-------------------------------------
mpirun -n 10 python CollectiveBSC.py
-------------------------------------

2) Point to point Broadcast - This process will compute number of bright spots for any given image using point to point communication.

Command to run the code
---------------------------------------
mpirun -n 10 python PointToPointBSC.py
---------------------------------------
