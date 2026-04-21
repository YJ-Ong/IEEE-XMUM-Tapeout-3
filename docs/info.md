## How it works

AND, NAND and OR gates are connected to input a and b.

16 flip flops are used to divide the clock speed with 2 outputs, one at the 12th flop and one at the 16th.

## How to test

Set the inputs and check the outputs match with the expected results:
| input IN0 IN1 IN2 | output OUT0 | output OUT4 |
|-------------------|-------------|-------------|
|0 0 0	            |1           |0            |
|0 0 1	            |1           |0            |
|0 1 0	            |1           |0            |
|0 1 1	            |0           |1            |
|1 0 0	            |1           |0            |
|1 0 1	            |0           |1            |
|1 1 1	            |0           |1            |
Set the clock to 0kHz.
