# RTLDesign_Using_Verilog_with_SKY130Technology

![166084640-128e6351-1739-4b38-a3ce-76459da921b5](https://user-images.githubusercontent.com/62461290/183637579-9d1a058a-2f33-43e0-b737-49b13cde667d.png)

# Table of Contents

[1. Introduction](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/edit/main/README.md#Introduction) <br>

[2. DAY 1 - Introduction to Verilog RTL Design and Synthesis]() <br>
* [2.1 SKY130RTL D1SK1 - Introduction to open-source simulator iverilog]() <br>
  - [2.1.1 SKY130RTL D1SK1 L1 Introduction iverilog design and test bench]() <br>
* [2.2 SKY130RTL D1SK2 - Labs using iverilog  and gtkwave]() <br>
  - [2.2.1 SKY130RTL D1SK2 L1 Lab 1 Introduction to Lab]() <br>
  - [2.2.2 SKY130RTL D1SK2 L2 Lab 2 Introduction to iVerilog GTKWave part1]() <br>
  - [2.2.3 SKY130RTL D1SK2 L3 Lab 2 Introduction to iVerilog GTKWave part2]() <br>
* [2.3 SKY130RTL D1SK3 - Introduction to Yosys and Logic Synthesis]() <br>
  - [2.3.1 SKY130RTL D1SK3 L1 Introduction to Yosys]() <br>
  - [2.3.2 SKY130RTL D1SK3 L2 Introduction to logic synthesis part1]() <br>
  - [2.3.3 SKY130RTL D1SK3 L3 Introduction to logic synthesis part2]() <br>
* [2.4 SKY130RTL D1SK4 - Labs Using Yosys and SKY130 PDKs]() <br>
  - [2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux part1]() <br>
  - [2.4.2 SKY130RTL D1SK4 L2 lab3 Yosys 1 good mux part2]() <br>
  - [2.4.3 SKY130RTL D1SK4 L3 lab3 Yosys 1 good mux part3]() <br>

[3. DAY 2 - Timing libs, hierarchical vs flat synthesis and efficient flop coding styles]() <br>
* [3.1 SKY130RTL D2SK1 - Introduction to timing .libs]() <br>
  - [3.1.1 SKY130RTL D2SK1 L1 Lab4 Introduction to dot lib part1]() <br>
  - [3.1.2 SKY130RTL D2SK1 L2 Lab4 Introduction to dot lib part2]() <br>
  - [3.1.3 SKY130RTL D2SK1 L3 Lab4 Introduction to dot lib part3]() <br>
* [3.2 SKY130RTL D2SK2 - Hierarchical vs Flat Synthesis]() <br>
  - [3.2.1 SKY130RTL D2SK2 L1 Lab 5 Hierarchical vs Flat Synthesis part1]() <br>
  - [3.2.2 SKY130RTL D2SK2 L2 Lab 5 Hierarchical vs Flat Synthesis part2]() <br>
* [3.3 SKY130RTL D2SK3 - Various Flop Coding Styles and Optimization]() <br>
  - [3.3.1 SKY130RTL D2SK3 L1 Why Flops and Flop coding styles part1]() <br>
  - [3.3.2 SKY130RTL D2SK3 L2 Why Flops and Flop coding styles part2]() <br>
  - [3.3.3 SKY130RTL D2SK3 L3 lab Flop Synthesis Simulation part1]() <br>
  - [3.3.4 SKY130RTL D2SK3 L4 lab Flop Synthesis Simulation part2]() <br>
  - [3.3.5 SKY130RTL D2SK3 L5 Interesting Optimisations part1]() <br>
  - [3.3.6 SKY130RTL D2SK3 L6 Interesting Optimisations part2]() <br>

[4. DAY 3 - Combinational and Sequential Optimizations]() <br>
* [4.1 SKY130RTL D3SK1 - Introduction to Optimizations]() <br>
  - [4.1.1 SKY130RTL D3SK1 L1 Introduction Optimizations Part1]() <br>
  - [4.1.2 SKY130RTL D3SK2 L2 Introduction Optimizations Part2]() <br>
  - [4.1.3 SKY130RTL D3SK3 L3 Introduction Optimizations Part3]() <br>
* [4.2 SKY130RTL D3SK2 - Combinational Logic Optimizations]() <br>
  - [4.2.1 SKY130RTL D3SK2 L1 Lab 6 Combinational Logic Optimizations part1]() <br>
  - [4.2.2 SKY130RTL D3SK2 L2 Lab 6 Combinational Logic Optimizations part2]() <br>
* [4.2 SKY130RTL D3SK2 - Combinational Logic Optimizations]() <br>
  - [4.2.1 SKY130RTL D3SK2 L1 Lab 6 Combinational Logic Optimizations part1]() <br>
  - [4.2.2 SKY130RTL D3SK2 L2 Lab 6 Combinational Logic Optimizations part2]() <br>
* [2.4 SKY130RTL D1SK4 - Labs Using Yosys and SKY130 PDKs]() <br>
  - [2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux part1]() <br>
  - [2.4.2 SKY130RTL D1SK4 L2 lab3 Yosys 1 good mux part2]() <br>
  - [2.4.3 SKY130RTL D1SK4 L3 lab3 Yosys 1 good mux part3]() <br>

[3. DAY 2 - Timing libs, hierarchical vs flat synthesis and efficient flop coding styles]() <br>
* [3.1 SKY130RTL D2SK1 - Introduction to timing .libs]() <br>
  - [3.1.1 SKY130RTL D2SK1 L1 Lab4 Introduction to dot lib part1]() <br>
  - [3.1.2 SKY130RTL D2SK1 L2 Lab4 Introduction to dot lib part2]() <br>
  - [3.1.3 SKY130RTL D2SK1 L3 Lab4 Introduction to dot lib part3]() <br>
* [3.2 SKY130RTL D2SK2 - Hierarchical vs Flat Synthesis]() <br>
  - [3.2.1 SKY130RTL D2SK2 L1 Lab 5 Hierarchical vs Flat Synthesis part1]() <br>
  - [3.2.2 SKY130RTL D2SK2 L2 Lab 5 Hierarchical vs Flat Synthesis part2]() <br>
* [3.3 SKY130RTL D2SK3 - Various Flop Coding Styles and Optimization]() <br>
  - [3.3.1 SKY130RTL D2SK3 L1 Why Flops and Flop coding styles part1]() <br>
  - [3.3.2 SKY130RTL D2SK3 L2 Why Flops and Flop coding styles part2]() <br>
  - [3.3.3 SKY130RTL D2SK3 L3 lab Flop Synthesis Simulation part1]() <br>
  - [3.3.4 SKY130RTL D2SK3 L4 lab Flop Synthesis Simulation part2]() <br>
  - [3.3.5 SKY130RTL D2SK3 L5 Interesting Optimisations part1]() <br>
  - [3.3.6 SKY130RTL D2SK3 L6 Interesting Optimisations part2]() <br>

# Introduction
This is a submission of the cloud based 5-Day Workshop on RTL Design Using Verilog with SKY130 Technology. The tools used are iVerilog, GTKWave, Yosys and SKY130 Standard Cell Libraries.
- iVerilog is used to simulate the verilog code with the corresponding testbench. <br>
- Yosys is used to synthesize the verilog file and provide a netlist file. <br>
- SKY130 Standard Cell Library was used to infer the gates level netlist from the verilog modules. <br>
- GTKWave is used to view the simulation and synthesis waveform. <br>

The labs are being performed on a Ubuntu operating system with due installation of all the tools used.
