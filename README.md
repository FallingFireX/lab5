# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name

## Lab Summary
In this lab, we took two truth tables and were asked to implement them as a minterm and maxterm respecivelly. We then had to write our own top.v, mapping each truth table output to a switch on the board. We then put our written minterm and maxterm codes, put into files circuit_a.v and circuit_b.v, along with the contraint and our written top.v, to successfully make an LED switch array, with the output of B being dependent on the output of A.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file is the file that creates the structural foundation for the verilog project. It connects all lower level modules together, and the simulation, synthesis, and bitstream are run through it. 

### 2 - Explain the function of the Constraints file.

the Constraints file is used to tell the synthesis and implementation tools how your logical design should map onto the physical hardware. The contrsaints file, as the name suggests, sets the parameters of the build, ensuring reasonable electrical requirements, clock speeds, and maps the code to a physical output on the board. 

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?

It would have been generally more efficient to flip them. Aka, Minterm on Circuit A and Max term on Circuit B. However,the original arrangement worked and saying they are incorrect would be inaccurate; moreso that flipping them may have been more efficient. 
