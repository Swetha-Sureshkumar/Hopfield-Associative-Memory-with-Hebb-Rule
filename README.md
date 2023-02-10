# Hopfield-Associative-Memory-with-Hebb-Rule

## Project description 
This project is an implementation of program that builds and tests the Hopfield Associative Memory with the Hebb rule. 
**Note:** All parts of the program except for GUI must be written without using external libraries (in particular the NN-related libraries). 
## Requirements 
1. **INPUT** in the form of an external file or provided in an interactive way by the user. both possibilities (external txt file and by means of GUI) need to be programmed. 
2. Calculation of the Hopfield Associative Memory. 
3. Iterative testing of any input vector: the user provides a test vector and the system outputs the HAM vector; next the user may input another vector – receive the output, etc. 
4. The program must allow calculation (testing) the output for ANY input vector of appropriate size not only one of the base/stored vectors 
5. The program must be able to handle both UNIPOLAR and BIPOLAR vectors. 
**NOTE** that, sometimes you must iterate several times. You may end iterations ONLY in either one of the two following cases: 
6. In the current iteration the output vector is equal the input one → then you print this vector as the network’s response; OR 
7. you enter a cycle of length two → in which case you print an information about entering a cycle and output both alternating outputs.
