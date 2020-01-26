# Mini-Processor-Simulator

Carson Gedeus, COP3402

Opera-on of the spimcore
For your convenience, here is how you could do it in UNIX environment. First compile:

$ gcc -o spimcore spimcore.c project.c

Aber compilaBon, to use MySPIM, you would type the following command in UNIX:
$ ./spimcore <filename>.asc

The command prompt
cmd:
should appear. spimcore works like a simple debugger with the following commands:

r - Dump registers contents
m - Dump memory contents (in Hexadecimal format)
s[n] - Step n instructions (simulate the next n instruction). If n is not typed, 1 is assumed
c - Continue (carry on the simulation until the program halts (with illegal instruction))
H - Check if the program has halted
d - ads1 ads2 Hexadecimal dump from address ads1 to ads2
I - Inquire memory size
P - Print the input file
g - Display all control signals
X, X, q, Q - Quit