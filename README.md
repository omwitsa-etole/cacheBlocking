# cacheBlocking
A  matrix multiplication program using cache blocking


A matrix multiplication programm implemented with the C programming language 

To run the simulator build the source file Matmul.c using either gcc, or your preffered compiler. This will create a working programm that is run with two command line arguments, 1. The source of the first matrix file 2. The source to the second matrix file. Some test files have been provided in the tests directory.

A sample run would be:
	> ./matMul tests/matrix_a_32x32.txt tests/matrix_a_32x32.txt

This will run the Multiplication of the matrix in tests/matrix_a_32x32.txt and tests/matrix_a_32x32.txt

This programm implements cacheblocking to improve working where large matrix multiplications may be needed in a small memory enviroment.

Enjoy...

