# Gater8
An 8-bit homemade CPU using 7400-series logic chips

The Gater8 CPU was designed for undergraduate students who were taking CS 201 / CS 301 course at the time I was teaching these courses in the University of Regina as sessional lecturer back in 2016. The purpose of this project is to help students understand the principles of computer organization. The CPU together with the computer based on it (with RAM, ROM, and I/O interfaces) were designed by 7400 series gate chips.

Gater8 has 12-bit address bus, 8-bit data bus, and 11 instructions. It has a semi-harvard and semi-von neumann architecture. The design was completed and tested in [LogicWorks 5](https://www.designworkssolutions.com/logicworks-5-windows/). It has been assembling by real 7400 chips. 

## Source Files
There are two variants of Gater8 design, they are pretty much the same expect one has a [MOV instruction](./CPU(2016_04_02_MOV_Ver).PNG), and the other has an [OR instruction](./CPU(2016_04_03_OR_Ver).PNG). The *.cct files are corresponding source file designed in LogicWorks 5.

## The Logic Design Diagram

- The logic diagram is [Logic Diagram](./logic_diagram.pdf).
- The control log details are in [this table](./chips.pdf)
- A schametics design (OR instruction version) is shown below:
![schametics](./CPU(2016_04_03_OR_Ver).PNG)
