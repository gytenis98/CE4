CE4
===

#PART A
The task was to write a program that stores $9 value in location $B0, $8 in $C4 and $B in $CB. 
I accomplished that by using oommands LDAI and STA. 

#PART B
The task was to write a program that retrieves a value from location $B0, doubles it, and subtracts 4. 
I accomplished that by using commands LDAD, ADDD, ADDI and OUT. I used "loop" to avoid program to crash.

#PART C
The task was to write a program that reads output ports value and then shows value less by one in output port 1. 
Subtracts 1 more and shows in the output port 2. Subtracts 1 more and shows in output port 3. After that subtracts one 
more and shows in port 1 again and process is continued in an infinite loop.
To accomplish this process I used commands IN, OUT, ADDI and JMP.

#Error log
At first I had difficulties to understand how the system works, but after get EI from Capt Silva i got it and it was not
that hard anymore.
