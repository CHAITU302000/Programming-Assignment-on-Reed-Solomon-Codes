# Programming-Assignment-on-Reed-Solomon-Codes
Developed a System which requires to encode and recover binary message bits using Reed-Solomon Codes
1) Read the input text-file and convert it to a binary string.
2) Convert the binary string into a sequence of symbols over F8.
3) Divide the string of symbols into several chunks such that each chunk is of size k = 3 symbols.
4) Encode each chunk into a sequence of n = 7 symbols by using the above Reed-Solomon code.
5) Assuming that each codeword is represented as a row vector, stack the codewords one below the
other to form a matrix. With this arrangement, the i-th column of the matrix, for 1 ≤ i ≤ 7, can
be seen as the i-th server that stores the i-th component of all the codewords.
6) Generate a random binary erasure pattern e of length 7 with hamming weight 4, which is used to
represent the erasure pattern of the servers. For instance, if e = [1 1 1 1 0 0 0], then this implies
that the first 4 servers have failed, and as a result, the first 4 components of every codeword have
been erased.
7) Recover the text-file from the existing set of servers (columns)
