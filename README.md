Download link :https://programming.engineering/product/hw2process_states-interrupt_haandling/


# hw2-Process_States-Interrupt_Haandling
hw2:Process_States-Interrupt_Haandling
Your program (if requested) must compile with gcc and execute on snowball.cs.gsu.edu! Please see https://cscit.cs.gsu.edu/sp/guide/snowball for more details. You may use any IDE/ text editors you prefer, but the source code (.c file) must be submitted via iCollege.

The following steps in interrupt handling are out of place. Correctly arrange them in the order in which they are carried out to handle the interruption of a running user process by assigning a number from 1 through 9 to indicate the precedence order for the following steps (9 points):

For example, 1 would indicate the first step in the process, 2 would indicate the second in the process and so on.

Explain why there is no direct transition from the state “waiting” to the “running” state. (3 points)

a) Write a C program to Implement a system of three processes which read and write numbers to a file. Each of the three processes P1, P2, and P3 must obtain an integer from the file (these instructions must be executed 200 times). The file only holds one integer at any given time. Given a file F, containing a single integer N, each process must perform the following steps (25 points):

1. Fork two processes

For 200 times:

Open F

Read the integer N from the file

Close F

Output N and the process’ PID (On the screen)

Increment N by 1

Open F

Write N to F (overwriting the current value in F)

Close F

Briefly describe why the processes P1, P2, and P3 obtain/read duplicates of numbers (why does a particular integer x appear in the output of more than one process)? (3 points)

Suggest a solution (you do not need to implement it) to guarantee that no duplicate numbers are ever obtained by the processes. In other words, each time the file is read by any process, that process reads a distinct integer. (2 points)

Please use pseudocode or C instructions to describe your solution. Any standard function used must use the correct prototype.

NOTE: Programs must compile and execute on the Snowball Server. Submit all .c code files along with the word document or pdf with your answers to questions 1 & 2 onto iCollege.
