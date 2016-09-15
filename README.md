# dse-benchmarks

![alt tag](https://github.com/plug-and-share/dse-benchmarks/blob/master/designspace.png)

## Susan
The execution used the sample image provided in the benchmark applying the smoothing operation. It uses the pthread library and executes in 8 threads by default. This configuration was used in the monocore, dualcore and quadcore architectures.  

## String Search
The input uses a 1024 string pattern with length equal to 5, within 20 texts with average length equal to 609.7 characters. The search method used in the execution was the case-sensitive Boyer-Moore-Horspool. For each architecture, the number of the threads was equal the number of cores.

## Data
The metrics used in the benchmarks are in the .csv file. The columns represent the area, number of cycles and the power consumption, and the designspace.csv file mapping the architecture parameters of each design point.

## Results
The results of the execution of the method (AMOSA) are summarized in the .pdf files. The values of each performance parameters of each execution are in the benchmarks' folders.

susan@1             |  susan@2             |  susan@4
:-------------------------:|:-------------------------:|:-------------------------:|
![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/stringsearch%401.png "stringsearch@1")  |  ![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/stringsearch%402.png "stringsearch@2") | ![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/stringsearch%404.png "stringsearch@4") 

stringsearch@1             |  stringsearch@2             |  stringsearch@4
:-------------------------:|:-------------------------:|:-------------------------:|
![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/susan%401.png "susan@1")  |  ![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/susan%402.png "susan@2") | ![alt text](https://github.com/plug-and-share/dse-benchmarks/blob/master/images/susan%404.png "susan@4")

