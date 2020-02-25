# Corewar
An implementation of the programming game “Core War” 
Algorithmic Project @ 42 Paris

## About
> Core War is a 1984 programming game created by D. G. Jones and A. K. Dewdney in which two or more battle programs 
> (called "warriors") compete for control of a virtual computer. 
> These battle programs are written in an abstract assembly language called Redcode.

## Project Structure

- Champion
- Assembler
- Debugger (Bonus)
- Virtual Machine
- Visualizer (Bonus)

## Installation
git clone https://github.com/MathieuJouffroy/Corewar.git && cd Corewar && make

## Usage 

### ASM
Usage: ./asm champion.s
    champion.s   — from assemble to bytecode
    
### VM (corewar)
Usage : ./corewar [-dump, -v [cycle_nb]] [[-n player_nb] champion1.cor] [[-n player_nb] champion2.cor] ...<br>
- dump <num> : Dump memory (32 octets per line) after <num> cycles and exit<br>
- v          : Run visualizer<br>
- n    <num> : Set <num> of the next player<br>
