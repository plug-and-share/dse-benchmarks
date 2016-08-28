# dse-benchmarks

## Matrix Multiplication
This application uses a trivial matrix multiplication with complexity O(n3). As input it uses a square matrix with dimension equal to sixty. For the monocore architectures, four multiplications were executed sequentially. In the quadcore architectures, were used as well four multiplication, but they were distributed for each core.
## Susan
This application is a set of image processing operations available in benchmark suite known as ParMiBench. The execution used the sample image provided in the benchmark  applying the smoothing operation. It uses pthread library and executes in 8 threads by default. This configuration was used in the monocore, dualcore and quadcore architectures.  
## String Search
This application also used the benchmark suite available in ParMiBench. The input uses a string pattern with length equal to five, and [text number] text with average length equal to 573 characters. Search method used in the exection was the case-sensitive Boyer-Moore-Horspool. For each architecture, the number of the threads was equal to the number of cores.
