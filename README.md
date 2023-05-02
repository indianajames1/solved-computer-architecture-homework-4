Download Link: https://assignmentchef.com/product/solved-computer-architecture-homework-4
<br>
Write and test a MIPS assembly language program that

1. Prompt the user for a machine code of a MIPS instruction, i.e. a 32-bit binary represented in hexadecimal. Obviously, the input must be a string of 8 hexadecimal digits (the prefix ‘Ox’ is not required.)

1.a If the input was an empty string exit the program.

2. Check for the validity of the input and print an error message if an invalid string was inputted (e.g. too long, too short, contain invalid characters, etc..). The error message should tell the user the cause of the error.

3. Check if the opcode of the instruction is one of the following:

a. Arithmetic and logical (i.e. the opcode is 0)

b. Data transfer (lw and sw only)

c. Branching and jumping (beq/bne and j only)

4. If the opcode was not one of those print out a message telling the user that the opcode was not recognized.

5. If the opcode was recognized print out the followings:

a.Instruction format.

b.The field name and the value of each field in the instruction in hexadecimal.

For example, if the input string was ‘8e300008’ the program should print

Instruction format: I

Opcode: 0x23

Rs: Ox 11 Rt: 0x 10 Imm: 0x0008

6. Go back to step 1.

Run the program and test the inputs for at least one valid instruction for each instruction category listed above, and a few invalid input strings.