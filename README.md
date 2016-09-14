# dse-benchmarks

![alt tag](https://github.com/plug-and-share/dse-benchmarks/blob/master/designspace.png)

## Susan
The execution used the sample image provided in the benchmark applying the smoothing operation. It uses the pthread library and executes in 8 threads by default. This configuration was used in the monocore, dualcore and quadcore architectures.  

## String Search
The input uses a 1024 string pattern with length equal to 5, within 20 texts with average length equal to 609.7 characters. The search method used in the execution was the case-sensitive Boyer-Moore-Horspool. For each architecture, the number of the threads was equal the number of cores.

## Data
The metrics used of the benchmarks are in the .csv file. The columns represent the area, number of cycles and the power consumption, and the designspace.csv file mapping the architecture parameters of each design point.

## Results
The results of the execution of the method (AMOSA) are in the .pdf files. 
