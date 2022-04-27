# RTL design using Verilog with SKY130 Technology
![](assets/Verilog_flyer.png)

# Overview
This is a 5-day workshop from VSD-IAT on RTL design and synthesis using open source silicon toolchains involving iVerilog, GTKWave, Yosys and Sky130 PDKs.  
This report is written as a part of final submission to summarize the 5-day journey through the workshop.

# Day 1 - Introduction to Verilog RTL design and Synthesis
## Introduction to open source simulator iVerilog
Simulation: RTL design is checked for adherence to its specification using simulation. This helps finding and fixing bugs in the RTL design in the early statges of design development. iVerilog gives the framework to achieve this.
iVerilog in short to [Icarus Verilog](http://iverilog.icarus.com/) is an open source toolchain for simulation and synthesis. Although it is used only for simulation due to the potential advantages Yosys brings as a synthesis tool (*more details later*).  

RTL design: Register Transfer Level (RTL) is representation of a digital circuit at an abstract level. This abstract realization of a specification is achieved using HDLs like Verilog, VHDL etc. Before the invention of RTL, digital engineers used to specify their desgins as schematic entry which could be tedious and error prone. RTL desgin behavior could be specified as a text in Verilog HDL.  
