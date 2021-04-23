# RMSD
Implementation of the c-RMSD and d-RMSD algorithms

Given are 80 conformations of a specific molecule in file \80 conformations.txt" on eclass: Documents/Assignments with n = 369 atoms on the backbone (hence in correspondence). The file starts with 2 lines containing 80 and n. The rest of the file uses tabs to define 3 columns containnig n triplets x y z of each conformation hence 2 + 80n rows:
  
80
369
2.816 -11.005 10.087
4.43  -10.545 10.011
...
  
Implement c-RMSD and d-RMSD in Matlab, Octave, Maple or other system offering linear algebra (SVD); submit your code. If your system provides either of these functions, it is OK to just use it.  
  
1. Use c-RMSD to compute the optimal translation and rotation minimizing c-RMSD between the first 2 conformations.  
2. Compute the c-RMSD distances between all pairs of conformations. Compute the mean and median c-RMSD distance and draw a histogram of all distances in 10 classes.  
3. Repeat (2) for d-RMSD using all k = distances within each conformation, or a random subset of k = 3n distances.  
