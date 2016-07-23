# Simulator and Assembler
###Introduction
This project is for my C program improved curriculum design in HUST.
The project is divided to two parts: assembler and simulator.
The assembler is designed to convert the assemble source code to execution code which can be executed by simulator.
The simulator can execute the program dealt by assemble.
To obtain the detailed request, refer to "AssignmentBook.doc".
#####Test And Use
######Compile assembler:
gcc -o sas assembler.c
######Compile simulator:
gcc -o ssim simulator.c
######Execution:
(Example)
./sas add_1-100 add_100.dat
./ssim add_100.dat
