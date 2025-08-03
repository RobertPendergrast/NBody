# N Body Simulation Computational Accelerator

Howdy! Here's my final project for CSEE 4840 Embedded System Design Spring 2025
Groupmates: Issac Trost, Kris Nikolov, Moises Mata, Adib Khondoker, and Me!

In this project we implemented the classic physics problem of the N-Body simulations on an FPGA. We built a computational accelerator that achieved over 100x speedup in computation times with 100% accuracy. 

## Repo Map:
- Hardware: This is where all the Verilog lives, incuding our leapfrog integration implementation, as well as all of the Quartus IP blocks. The VGA display hardware is also located here.
- Software: This is where we store all of our C code - namely the linux drivers and user space application.


## VGA Display
<img width="402" height="356" alt="Screenshot 2025-08-02 at 10 50 13 PM" src="https://github.com/user-attachments/assets/b0ba74c0-e4ea-46c1-8599-38c782490330" />
