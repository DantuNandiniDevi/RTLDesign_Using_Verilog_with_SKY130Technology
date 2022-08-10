# RTLDesign_Using_Verilog_with_SKY130Technology

![166084640-128e6351-1739-4b38-a3ce-76459da921b5](https://user-images.githubusercontent.com/62461290/183637579-9d1a058a-2f33-43e0-b737-49b13cde667d.png)

# Table of Contents

[1. Introduction](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/edit/main/README.md#1-Introduction) <br>

[2. DAY 1 - Introduction to Verilog RTL Design and Synthesis](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#2-day-1---introduction-to-verilog-rtl-design-and-synthesis) <br>
* [2.1 SKY130RTL D1SK1 - Introduction to open-source simulator iverilog](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#21-sky130rtl-d1sk1---introduction-to-open-source-simulator-iverilog) <br>
  - [2.1.1 SKY130RTL D1SK1 L1 Introduction iverilog design and test bench](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#211-sky130rtl-d1sk1-l1-introduction-iverilog-design-and-test-bench) <br>
* [2.2 SKY130RTL D1SK2 - Labs using iverilog  and gtkwave](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#22-sky130rtl-d1sk2---labs-using-iverilog--and-gtkwave) <br>
  - [2.2.1 SKY130RTL D1SK2 L1 Lab 1 Introduction to Lab](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#221-sky130rtl-d1sk2-l1-lab-1-introduction-to-lab) <br>
  - [2.2.2 SKY130RTL D1SK2 L2 Lab 2 Introduction to iVerilog GTKWave part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#222-sky130rtl-d1sk2-l2-lab-2-introduction-to-iverilog-gtkwave-part1) <br>
  - [2.2.3 SKY130RTL D1SK2 L3 Lab 2 Introduction to iVerilog GTKWave part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#223-sky130rtl-d1sk2-l3-lab-2-introduction-to-iverilog-gtkwave-part2) <br>
* [2.3 SKY130RTL D1SK3 - Introduction to Yosys and Logic Synthesis](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#23-sky130rtl-d1sk3---introduction-to-yosys-and-logic-synthesis) <br>
  - [2.3.1 SKY130RTL D1SK3 L1 Introduction to Yosys](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#231-sky130rtl-d1sk3-l1-introduction-to-yosys) <br>
  - [2.3.2 SKY130RTL D1SK3 L2 Introduction to logic synthesis part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#232-sky130rtl-d1sk3-l2-introduction-to-logic-synthesis-part1) <br>
  - [2.3.3 SKY130RTL D1SK3 L3 Introduction to logic synthesis part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#233-sky130rtl-d1sk3-l3-introduction-to-logic-synthesis-part2) <br>
* [2.4 SKY130RTL D1SK4 - Labs Using Yosys and SKY130 PDKs](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#24-sky130rtl-d1sk4---labs-using-yosys-and-sky130-pdks) <br>
  - [2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#241-sky130rtl-d1sk4-l1-lab3-yosys-1-good-mux) <br>

[3. DAY 2 - Timing libs, hierarchical vs flat synthesis and efficient flop coding styles](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#3-day-2---timing-libs-hierarchical-vs-flat-synthesis-and-efficient-flop-coding-styles) <br>
* [3.1 SKY130RTL D2SK1 - Introduction to timing .libs](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#31-sky130rtl-d2sk1---introduction-to-timing-dot-libs) <br>
  - [3.1.1 SKY130RTL D2SK1 L1 Lab4 Introduction to dot lib part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#311-sky130rtl-d2sk1-l1-lab4-introduction-to-dot-lib-part1) <br>
  - [3.1.2 SKY130RTL D2SK1 L2 Lab4 Introduction to dot lib part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#312-sky130rtl-d2sk1-l2-lab4-introduction-to-dot-lib-part2) <br>
  - [3.1.3 SKY130RTL D2SK1 L3 Lab4 Introduction to dot lib part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#313-sky130rtl-d2sk1-l3-lab4-introduction-to-dot-lib-part3) <br>
* [3.2 SKY130RTL D2SK2 - Hierarchical vs Flat Synthesis]() <br>
  - [3.2.1 SKY130RTL D2SK2 L1 Lab 5 Hierarchical vs Flat Synthesis part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#32-sky130rtl-d2sk2---hierarchical-vs-flat-synthesis) <br>
  - [3.2.2 SKY130RTL D2SK2 L2 Lab 5 Hierarchical vs Flat Synthesis part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#322-sky130rtl-d2sk2-l2-lab-5-hierarchical-vs-flat-synthesis-part2) <br>
* [3.3 SKY130RTL D2SK3 - Various Flop Coding Styles and Optimization](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#33-sky130rtl-d2sk3---various-flop-coding-styles-and-optimization) <br>
  - [3.3.1 SKY130RTL D2SK3 L1 Why Flops and Flop coding styles part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#331-sky130rtl-d2sk3-l1-why-flops-and-flop-coding-styles-part1) <br>
  - [3.3.2 SKY130RTL D2SK3 L2 Why Flops and Flop coding styles part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#332-sky130rtl-d2sk3-l2-why-flops-and-flop-coding-styles-part2) <br>
  - [3.3.3 SKY130RTL D2SK3 L3 lab Flop Synthesis Simulation part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#333-sky130rtl-d2sk3-l3-lab-flop-synthesis-simulation-part1) <br>
  - [3.3.4 SKY130RTL D2SK3 L4 lab Flop Synthesis Simulation part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#334-sky130rtl-d2sk3-l4-lab-flop-synthesis-simulation-part2) <br>
  - [3.3.5 SKY130RTL D2SK3 L5 Interesting Optimisations part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#335-sky130rtl-d2sk3-l5-interesting-optimisations-part1) <br>
  - [3.3.6 SKY130RTL D2SK3 L6 Interesting Optimisations part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#336-sky130rtl-d2sk3-l6-interesting-optimisations-part2) <br>

[4. DAY 3 - Combinational and Sequential Optimizations](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#4-day-3---combinational-and-sequential-optimizations) <br>
* [4.1 SKY130RTL D3SK1 - Introduction to Optimizations](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#41-sky130rtl-d3sk1---introduction-to-optimizations) <br>
  - [4.1.1 SKY130RTL D3SK1 L1 Introduction Optimizations Part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#411-sky130rtl-d3sk1-l1-introduction-optimizations-part1) <br>
  - [4.1.2 SKY130RTL D3SK2 L2 Introduction Optimizations Part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#412-sky130rtl-d3sk2-l2-introduction-optimizations-part2) <br>
  - [4.1.3 SKY130RTL D3SK3 L3 Introduction Optimizations Part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#413-sky130rtl-d3sk3-l3-introduction-optimizations-part3) <br>
* [4.2 SKY130RTL D3SK2 - Combinational Logic Optimizations](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#42-sky130rtl-d3sk2---combinational-logic-optimizations) <br>
  - [4.2.1 SKY130RTL D3SK2 L1 Lab 6 Combinational Logic Optimizations part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#421-sky130rtl-d3sk2-l1-lab-6-combinational-logic-optimizations-part1) <br>
  - [4.2.2 SKY130RTL D3SK2 L2 Lab 6 Combinational Logic Optimizations part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#422-sky130rtl-d3sk2-l2-lab-6-combinational-logic-optimizations-part2) <br>
* [4.3 SKY130RTL D3SK3 - Sequential Logic Optimizations](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#43-sky130rtl-d3sk3---sequential-logic-optimizations) <br>
  - [4.3.1 SKY130RTL D3SK3 L1 Lab 7 Sequential Logic Optimizations part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#431-sky130rtl-d3sk3-l1-lab-7-sequential-logic-optimizations-part1) <br>
  - [4.3.2 SKY130RTL D3SK3 L2 Lab 7 Sequential Logic Optimizations part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#432-sky130rtl-d3sk3-l2-lab-7-sequential-logic-optimizations-part2) <br>
  - [4.3.3 SKY130RTL D3SK3 L3 Lab 7 Sequential Logic Optimizations part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#433-sky130rtl-d3sk3-l3-lab-7-sequential-logic-optimizations-part3) <br>
* [4.4 SKY130RTL D3SK3 - Sequential Logic Optimizations for unused outputs](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#44-sky130rtl-d3sk3---sequential-logic-optimizations-for-unused-outputs) <br>
  - [4.4.1 SKY130RTL D3SK4 L1 Sequential Logic Optimizations for unused outputs part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#441-sky130rtl-d3sk4-l1-sequential-logic-optimizations-for-unused-outputs-part1) <br>
  - [4.4.2 SKY130RTL D3SK4 L2 Sequential Logic Optimizations for unused outputs part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#442-sky130rtl-d3sk4-l2-sequential-logic-optimizations-for-unused-outputs-part2) <br>


[5. DAY 4 - GLS, Blocking VS Non-blocking and Synthesis-Simulation mismatch](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#5-day-4---gls-blocking-vs-non-blocking-and-synthesis-simulation-mismatch) <br>
* [5.1 SKY130RTL D4SK1 - GLS, Synthesis-Simulation mismatch and Blocking/Non-blocking Statements](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#51-sky130rtl-d4sk1---gls-synthesis-simulation-mismatch-and-blockingnon-blocking-statements) <br>
  - [5.1.1 SKY130RTL D4SK1 L1 GLS Concepts and Flow Using iVerilog](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#511-sky130rtl-d4sk1-l1-gls-concepts-and-flow-using-iverilog) <br>
  - [5.1.2 SKY130RTL D4SK1 L2 Synthesis and Simulation Mismatch](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#512-sky130rtl-d4sk1-l2-synthesis-and-simulation-mismatch) <br>
  - [5.1.3 SKY130RTL D4SK1 L3 Blocking and Non-Blocking Statements in Verilog](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#513-sky130rtl-d4sk1-l3-blocking-and-non-blocking-statements-in-verilog) <br>
  - [5.1.4 SKY130RTL D4SK1 L4 Caveats with Blocking Statements](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#514-sky130rtl-d4sk1-l4-caveats-with-blocking-statements) <br>
* [5.2 SKY130RTL D4SK2 - Labs on GLS and Synthesis-Simulation Mismatch](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#52-sky130rtl-d4sk2---labs-on-gls-and-synthesis-simulation-mismatch) <br>
  - [5.2.1 SKY130RTL D4SK2 L1 Lab GLS and Synthesis-Simulation Mismatch part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#52-sky130rtl-d4sk2---labs-on-gls-and-synthesis-simulation-mismatch) <br>
  - [5.2.2 SKY130RTL D4SK2 L2 Lab GLS and Synthesis-Simulation Mismatch part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#522-sky130rtl-d4sk2-l2-lab-gls-and-synthesis-simulation-mismatch-part2) <br>
* [5.3 SKY130RTL D4SK3 - Labs on Synthesis-Simulation mismatch for blocking statements](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#53-sky130rtl-d4sk3---labs-on-synthesis-simulation-mismatch-for-blocking-statements) <br>
  - [5.3.1 SKY130RTL D4SK3 L1 Lab Synthesis-Simulation mismatch for blocking statements part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#531-sky130rtl-d4sk3-l1-lab-synthesis-simulation-mismatch-for-blocking-statements-part1) <br>
  - [5.3.2 SKY130RTL D4SK3 L2 Lab Synthesis-Simulation mismatch for blocking statements part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#532-sky130rtl-d4sk3-l2-lab-synthesis-simulation-mismatch-for-blocking-statements-part2) <br>
  
[6. DAY 5 - If, case, for loop and for generate ](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#6-day-5---if-case-for-loop-and-for-generate) <br>
* [6.1 SKY130RTL D5SK1 - If Case constructs](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#61-sky130rtl-d5sk1---if-case-constructs) <br>
  - [6.1.1 SKY130RTL D5SK1 L1 If Case Constructs part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#611-sky130rtl-d5sk1-l1-if-case-constructs-part1) <br>
  - [6.1.2 SKY130RTL D5SK1 L2 If Case Constructs part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#612-sky130rtl-d5sk1-l2-if-case-constructs-part2) <br>
  - [6.1.3 SKY130RTL D5SK1 L3 If Case Constructs part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#613-sky130rtl-d5sk1-l3-if-case-constructs-part3) <br>
* [6.2 SKY130RTL D5SK2 - Labs on "Incomplete If Case"](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#62-sky130rtl-d5sk2---labs-on-incomplete-if-case) <br>
  - [6.2.1 SKY130RTL D5SK2 L1 Lab Incomplete If part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#621-sky130rtl-d5sk2-l1-lab-incomplete-if-part1) <br>
  - [6.2.2 SKY130RTL D5SK2 L2 Lab Incomplete If part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#622-sky130rtl-d5sk2-l2-lab-incomplete-if-part2) <br>
* [6.3 SKY130RTL D5SK3 - Labs on "Incomplete and Overlapping Case"](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#63-sky130rtl-d5sk3---labs-on-incomplete-and-overlapping-case) <br>
  - [6.3.1 SKY130RTL D5SK3 L1 Lab Incomplete and Overlapping Case part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#631-sky130rtl-d5sk3-l1-lab-incomplete-and-overlapping-case-part1) <br>
  - [6.3.2 SKY130RTL D5SK3 L2 Lab Incomplete and Overlapping Case part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#632-sky130rtl-d5sk3-l2-lab-incomplete-and-overlapping-case-part2) <br>
  - [6.3.3 SKY130RTL D5SK3 L3 Lab Incomplete and Overlapping Case part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#633-sky130rtl-d5sk3-l3-lab-incomplete-and-overlapping-case-part3) <br>
  - [6.3.4 SKY130RTL D5SK3 L4 Lab Incomplete and Overlapping Case part4](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#634-sky130rtl-d5sk3-l4-lab-incomplete-and-overlapping-case-part4) <br>
* [6.4 SKY130RTL D5SK4 - For Loop and For Generate](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#64-sky130rtl-d5sk4---for-loop-and-for-generate) <br>
  - [6.4.1 SKY130RTL D5SK4 L1 For Loop and For Generate part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#641-sky130rtl-d5sk4-l1-for-loop-and-for-generate-part1) <br>
  - [6.4.2 SKY130RTL D5SK4 L2 For Loop and For Generate part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#642-sky130rtl-d5sk4-l2-for-loop-and-for-generate-part2) <br>
  - [6.4.3 SKY130RTL D5SK4 L3 For Loop and For Generate part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#643-sky130rtl-d5sk4-l3-for-loop-and-for-generate-part3) <br>
* [6.5 SKY130RTL D5SK5 - Labs on "For loop" and "For Generate"](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#65-sky130rtl-d5sk5---labs-on-for-loop-and-for-generate) <br>
  - [6.5.1 SKY130RTL D5SK5 L1 Lab For and For Generate part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#651-sky130rtl-d5sk5-l1-lab-for-and-for-generate-part1) <br>
  - [6.5.2 SKY130RTL D5SK5 L2 Lab For and For Generate part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#652-sky130rtl-d5sk5-l2-lab-for-and-for-generate-part2) <br>
  - [6.5.3 SKY130RTL D5SK5 L3 Lab For and For Generate part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#653-sky130rtl-d5sk5-l3-lab-for-and-for-generate-part3) <br>
  - [6.5.4 SKY130RTL D5SK5 L4 Lab For and For Generate part4](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#654-sky130rtl-d5sk5-l4-lab-for-and-for-generate-part4) <br>
 


# 1. Introduction
This is a submission of the cloud based 5-Day Workshop on RTL Design Using Verilog with SKY130 Technology. The tools used are iVerilog, GTKWave, Yosys and SKY130 Standard Cell Libraries.
- iVerilog is used to simulate the verilog code with the corresponding testbench. <br>
- Yosys is used to synthesize the verilog file and provide a netlist file. <br>
- SKY130 Standard Cell Library was used to infer the gates level netlist from the verilog modules. <br>
- GTKWave is used to view the simulation and synthesis waveform. <br>

The labs are being performed on a Ubuntu operating system with due installation of all the tools used.

RTL(Register Transfer Language) is a coding style used to code sequential and combinational circuits in HDL like Verilog or VHDL. RTL codes are further simulated to check the behaviour and sythesised to do a physical layout and produce a chip. The flow followed for this development cycle is called a ASIC(Application Specific Integrated Circuit) design flow. 
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183838617-507472a5-f22c-4936-a3f9-066ad5c48d3b.jpg"> <br>
ASIC Design Flow Samir Palnitkar
</p>

# 2. Day 1 - Introduction to Verilog RTL Design and Synthesis
## 2.1 SKY130RTL D1SK1 - Introduction to open-source simulator iverilog
### 2.1.1 SKY130RTL D1SK1 L1 Introduction iverilog design and test bench
<b> Simulator: </b> It is a tool used to check if it adheres to the designed specs by simualting the code. <br>
<br>
<b> Design: </b> It is the actual verilog code or set of verilog codes which has the intended functionality to meet with the required functionality/speciifications. Design file contains one or more input/output ports.<br>
<br>
<b> TestBench: </b> It is the setup to apply stimulus to the design to check its functionality. Testbench doesnot contain any input/output ports. <br>
<br>
<b> How does a Simulator Works ? </b> <br>
- Simulator looks for change on the input signal to produce a output signal.<br>
- Upon change in the input signal the output signal is evaluated. i.e, If there is no change in input the output will not be evaluated.<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183845210-c3b9712f-c56f-4d62-98d4-34d22ad78f10.png"> <br>
General Simulation Flow
</p>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183845405-c8a1de5c-f949-4962-9952-6bf8e68c164f.png"> <br>
iVerilog Based Simulation Flow
</p>


## 2.2 SKY130RTL D1SK2 - Labs using iverilog  and gtkwave
### 2.2.1 SKY130RTL D1SK2 L1 Lab 1 Introduction to Lab
Navigate to the directory you want the files to be stored and type the following command to get the required files.
```
$ git clone https://github.com/kunalg123/sky130RTLDesignAndSynthesisWorkshop.git
$ cd sky130RTLDesignAndSynthesisWorkshop
```
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183880350-08096f4e-5598-4e5c-a9b6-06826bd13085.png"> <br>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183880387-c142c1e1-ae45-4a53-96df-b4ecbc6e84db.png"> <br>
List of all the files used in this workshop
</p>



### 2.2.2 SKY130RTL D1SK2 L2 Lab 2 Introduction to iVerilog GTKWave part1
In this lab we simulated a 2:1 multiplexer.<br>
Navigate to the verilog_files folder

```
$ iverilog good_mux.v tb_good_mux.v
$ ./a.out
$ gtkwave tb_good_mux.vcd
```
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183884367-cc4f41c6-cf87-4397-b785-5cad106d232b.png"> <br>
Waveform of the 2:1 multiplexer Simulation
</p>

It can be clearly seen from waveform when select is <I> 0 </I> y is following <I> i0 </I> and when select is <I> 1 </I> y is following <I> i1 </I> <br>

### 2.2.3 SKY130RTL D1SK2 L3 Lab 2 Introduction to iVerilog GTKWave part2
```
Design File of 2:1 MUX

module good_mux (input i0 , input i1 , input sel , output reg y);
always @ (*)
begin
	if(sel)
		y <= i1;
	else 
		y <= i0;
end
endmodule
```

```
Testbench of 2:1 MUX

`timescale 1ns / 1ps
module tb_good_mux;
	reg i0,i1,sel; // Inputs
	wire y;  // Outputs
	good_mux uut (.sel(sel),.i0(i0),.i1(i1),.y(y)); // Instantiate the Unit Under Test (UUT)
	initial begin
	$dumpfile("tb_good_mux.vcd");
	$dumpvars(0,tb_good_mux);
	// Initialize Inputs
	sel = 0;
	i0 = 0;
	i1 = 0;
	#300 $finish;
	end
always #75 sel = ~sel;
always #10 i0 = ~i0;
always #55 i1 = ~i1;
endmodule
```
<br>
uut(unit under test) : It is the normal convention to name the top level module called in testbench as an uut. <br>

## 2.3 SKY130RTL D1SK3 - Introduction to Yosys and Logic Synthesis
### 2.3.1 SKY130RTL D1SK3 L1 Introduction to Yosys

- Synthesizer is a tool used for converting the RTL to Netlist. <br>
- Yosys is the synthesizer used in this course.

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183900424-3847b18b-362f-403c-a932-94ae04f9d846.png"> <br>
Yosys Synthesis Setup
</p>

The same testbench that is used for the simulation can be used for the synthesized netlist as well. The output waveform of both Synthesis and Simulation have to match. <br>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183900461-350aa07f-ed24-41fc-8478-4ef49b2b8d73.png"> <br>
Verification of Synthesized Netlist
</p>

### 2.3.2 SKY130RTL D1SK3 L2 Introduction to logic synthesis part1
<b> Synthesis: </b> <br>
- The RTL design is converted into gates and the connections are made between gates. <br>
- This is given out as a file called netlist. <br>

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183910992-4910d098-f175-484f-8dcc-20a989d41967.png"> <br>
</p>

<b> .lib </b>
- It contains all different kind of logic modules. like AND, OR, NOR etc.<br>
- It contains different variants of the same gate as well. like 2i/p, 3i/p, 4i/p, slow, fast, medium gates etc.<br>

There are different kind of gates avaiable to take in account the performance parameters like Delay, Area, Power into consideration. <br>
- If we choose speed we trade off area and power likewise if we choose area we trade off delay. Hence we have to choose them either based on the design constrains or find a sweet spot between all of them.

### 2.3.3 SKY130RTL D1SK3 L3 Introduction to logic synthesis part2

- Load in a digital logic circuit is a capacitor. <br>
- Fater the charging and discharging of capacitance the lesser is the delay. <br>
- To charge/Discharge the capacitor fast, we need transistors capable of sourcing more current. <br>
- Wider transistors -> low delay -> More Power and Area. <br>
- Narrow transitor -> More delay -> Less Area and Power. <br>

<b> Selection of Cells </b> <br>
- Need to guide the synthesizer to select the flavour of cells that is optimum for the implementation of logic circuits. <br>
- More use of fast cells can be bad interms of power and area. <br>
- More use of slow cells can lead to a sluggish circuit. <br>
- The guidence offered to the synthesizer is called constraints <br>

## 2.4 SKY130RTL D1SK4 - Labs Using Yosys and SKY130 PDKs
### 2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux
Run the Following command in the terminal path where the respective files are saved.

```
$ yosys
$ read_liberty -lib /home/nandu/ASIC/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
$ read_verilog good_mux.v
$ synth -top good_mux
$ abc -liberty /home/nandu/ASIC/sky130RTLDesignAndSynthesisWorkshop/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
$ show
$ write_verilog -noattr good_mux_netlist.v
```
![Screenshot 2022-08-10 185824](https://user-images.githubusercontent.com/62461290/183915651-27b843a9-a4d4-465e-a367-021ea778e72e.png)
![Screenshot 2022-08-10 185805](https://user-images.githubusercontent.com/62461290/183915678-d039ba7e-ed50-457b-a8d1-c55e04b5ea6e.png)
![Screenshot 2022-08-10 185748](https://user-images.githubusercontent.com/62461290/183915719-bfeef00a-902f-4399-b3ed-4c6eb7789deb.png)
![Screenshot 2022-08-10 185716](https://user-images.githubusercontent.com/62461290/183915736-9062716e-656c-482b-aba0-3e9850e61b86.png)
![Screenshot 2022-08-10 185843](https://user-images.githubusercontent.com/62461290/183915748-6bcce7b9-74ff-4091-87f3-e613a021a76e.png)
![Screenshot 2022-08-10 190142](https://user-images.githubusercontent.com/62461290/183915783-6c390ea5-f1fd-4972-b1f2-84033ebc1642.png)

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183915828-b6df3261-9923-4903-8a28-a7502b58988d.png"> <br>
Gate level model Generated
</p>


```
Netlist File Generated

/* Generated by Yosys 0.20+1 (git sha1 60a787fa500, clang  -fPIC -Os) */
module good_mux(i0, i1, sel, y);
  wire _0_;
  wire _1_;
  wire _2_;
  wire _3_;
  input i0;
  wire i0;
  input i1;
  wire i1;
  input sel;
  wire sel;
  output y;
  wire y;
  sky130_fd_sc_hd__mux2_1 _4_ ( .A0(_0_), .A1(_1_), .S(_2_), .X(_3_)  );
  assign _0_ = i0;
  assign _1_ = i1;
  assign _2_ = sel;
  assign y = _3_;
endmodule
```

# NOTE
Here on the commands being used have a similar format.

1. Simulation in iVerilog
```
iverilog designfilename.v testbench.v
```

2. To run the file
```
./a.out
```

3. To plot waveforms
```
gtkwave dumpfilefilename.vcd
```

4. To invoke Yosys
```
yosys
```

5. To read liberty file
```
read_liberty -lib library_file_path
```

6. To read the verilog file
```
read_verilog designfilename.v
```

7. To synthesize the top level module
```
synth -top module_name
```

8. To read the standard cell libraries
```
abc -liberty library_file_path
```

9. To show the synthesis diagram
```
show
```

10. To generate the netlist file
```
write_verilog -noattr netlistfilename.v
```

11. To create a flat synthesis
```
flatten
```


# 3. DAY 2 - Timing libs, hierarchical vs flat synthesis and efficient flop coding styles
## 3.1 SKY130RTL D2SK1 - Introduction to timing dot libs
### 3.1.1 SKY130RTL D2SK1 L1 Lab4 Introduction to dot lib 
PVT (Process Voltage Temperature) determines the silicon working

tt in the file name means typical
025C in the file indicates temperature
1v80 in the file name indicates operating voltage

.lib will contain leakage power for every input combination possible

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183923690-972e6de6-9e75-4eb1-b3ef-f9f1c44683f2.png"> <br>
</p>

.lib contains the delay, area occupied and much more information for each cell.

## 3.2 SKY130RTL D2SK2 - Hierarchical vs Flat Synthesis

```
Code for Multiple Modules

module sub_module2 (input a, input b, output y);
	assign y = a | b;
endmodule

module sub_module1 (input a, input b, output y);
	assign y = a&b;
endmodule

module multiple_modules (input a, input b, input c , output y);
	wire net1;
	sub_module1 u1(.a(a),.b(b),.y(net1));  //net1 = a&b
	sub_module2 u2(.a(net1),.b(c),.y(y));  //y = net1|c ,ie y = a&b + c;
endmodule
```

When multiple submodules are combined to form a single top level module. Two types of Synthesis is possible.

<b> 1. Hierarchical Synthesis: </b> <br>
In hierarchical synthesis the submodules are preserved and shown while seeing the synthesis diagram. <br>

In the figure below we can see 2 submodules namely sub_module1 and sub_module2. Hence the hierarchy is preserved.

<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183948156-a69076be-e0a8-4759-817c-62140054e6cd.png"> <br>
Hierarchical Synthesis
</p>

<b> 2. Flat Synthesis: </b> <br>
In flat synthesis the submodules are removed and normal gates are implemented.<br>

In the figure below we can see only gates there are no submodules preserved.
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183948326-6b304745-6ca6-4769-b3bb-28c300459007.png"> <br>
Flat Synthesis
</p>

## 3.3 SKY130RTL D2SK3 - Various Flop Coding Styles and Optimization
### 3.3.1 SKY130RTL D2SK3 L1 Why Flops and Flop coding styles
- Flops are used to reduce glitching and stabilize the circuits. <br>

The various coding styles of flops are: <br>
1. Flop with Synchronous Reset : It resets the flop with respect to condition of the clock
2. Flop with Synchronous Set : It sets the flop with respect to condition of the clock
3. Flop with Asynchronous Reset : It resets the flop irrespect of the condition of the clock
4. Flop with Asynchronous Set : It sets the flop irrespect of the condition of the clock
5. Flop with both Synchronous and Asynchronous Reset : It resets the flop both with respect to condition of the clock and irrespective of it.

### 3.3.2 SKY130RTL D2SK3 L3 lab Flop Synthesis Simulation 
1. Flop With Asynchronous Reset:
![async_res1](https://user-images.githubusercontent.com/62461290/183967538-d4767a79-b2c6-4d38-9057-6260326c9e6b.png)
![async_rst_s](https://user-images.githubusercontent.com/62461290/183967543-dee9ee1f-2a16-4b0d-b2f3-95afaaaf597e.png)

2. Flop with Asynchronous Set:

![async_set1](https://user-images.githubusercontent.com/62461290/183967503-82bd4084-009a-47e1-95c1-84b37495006f.png)
![async_set_s](https://user-images.githubusercontent.com/62461290/183967547-b4942d5d-bda0-41a7-a7fd-9e47c9f93104.png)

3. Flop with Synchronous Reset:
![sync_reset](https://user-images.githubusercontent.com/62461290/183967522-8384696f-d61f-46f1-8353-5c5a490ae380.png)
![syncres_s](https://user-images.githubusercontent.com/62461290/183967526-0bcc6a59-56c1-4dc8-bbbd-ffc8d5399443.png)

4. Flop with Synchronous and Asynchronous Reset
![asyncres_syncres](https://user-images.githubusercontent.com/62461290/183967514-db3b05f6-9034-44f4-af35-195b9ca20613.png)
![as_sy_rst_s](https://user-images.githubusercontent.com/62461290/183967533-78fc961a-7160-4985-bde5-6709861fa819.png)



### 3.3.3 SKY130RTL D2SK3 L5 Interesting Optimisations 

There is no hardware needed for the following codes <br>

```
module mul2 (input [2:0] a, output [3:0] y);
	assign y = a * 2;
endmodule
```
<b> Synthesis of the above design </b>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183961911-8fb9a923-5b4a-4d1f-be09-c62bc7fea83c.png"> <br>
<img src="https://user-images.githubusercontent.com/62461290/183961935-19838f94-46b4-4fb7-b978-59346b57f66b.png"> <br>
</p>

```
module mult8 (input [2:0] a , output [5:0] y);
	assign y = a * 9
endmodule
```
<b> Synthesis of the above design </b>
<p align="center">
<img src="https://user-images.githubusercontent.com/62461290/183961970-f6423bde-b56d-45f6-a11b-5d7c38126030.png"> <br>
<img src="https://user-images.githubusercontent.com/62461290/183961984-9547d168-687a-46f9-ae6a-766d35763c8a.png"> <br>
</p>

# 4. DAY 3 - Combinational and Sequential Optimizations

## 4.1 SKY130RTL D3SK2 - Combinational Logic Optimizations
The following codes are optimised and the synthesis circuits are generated automatically.

```
module opt_check (input a , input b , output y);
	assign y = a?b:0;
endmodule
```
![opt_check](https://user-images.githubusercontent.com/62461290/183973366-a36a706a-4d52-4415-8d64-36ea54cfa991.png)
<br>

```
module opt_check2 (input a , input b , output y);
	assign y = a?1:b;
endmodule
```
![opt_check2](https://user-images.githubusercontent.com/62461290/183973369-ce115848-f256-43eb-a41b-2ddadcf0a33d.png)
<br>

```
module opt_check3 (input a , input b, input c , output y);
	assign y = a?(c?b:0):0;
endmodule
```
![opt_check3](https://user-images.githubusercontent.com/62461290/183973359-965b8469-9460-4bb1-b3e0-565c1e21177b.png)
<br>

```
module opt_check4 (input a , input b , input c , output y);
 assign y = a?(b?(a & c ):c):(!c);
endmodule
```
![opt_check4](https://user-images.githubusercontent.com/62461290/183973363-110141ea-6b82-4473-a193-9c8f00f49fd7.png)

## 4.2 SKY130RTL D3SK3 - Sequential Logic Optimizations
The following codes are optimised and the synthesis circuits are generated automatically. <br>
```
module dff_const1(input clk, input reset, output reg q);
always @(posedge clk, posedge reset)
begin
	if(reset)
		q <= 1'b0;
	else
		q <= 1'b1;
end
endmodule
```
![dff_const1](https://user-images.githubusercontent.com/62461290/183976477-dc39a704-4b05-4036-976c-3aabe3709ebe.png)
<br>
```
module dff_const2(input clk, input reset, output reg q);
always @(posedge clk, posedge reset)
begin
	if(reset)
		q <= 1'b1;
	else
		q <= 1'b1;
end
endmodule
```
![dff_const2](https://user-images.githubusercontent.com/62461290/183976479-3f659072-740d-4628-a8f2-3a7aba077f20.png)
<br>
```
module dff_const3(input clk, input reset, output reg q);
reg q1;
always @(posedge clk, posedge reset)
begin
	if(reset)
	begin
		q <= 1'b1;
		q1 <= 1'b0;
	end
	else
	begin
		q1 <= 1'b1;
		q <= q1;
	end
end
endmodule
```
![dff_const3](https://user-images.githubusercontent.com/62461290/183976482-41a79595-ecfc-424e-b00d-4c7ef1ab5c44.png)
<br>
```
module dff_const4(input clk, input reset, output reg q);
reg q1;
always @(posedge clk, posedge reset)
begin
	if(reset)
	begin
		q <= 1'b1;
		q1 <= 1'b1;
	end
	else
	begin
		q1 <= 1'b1;
		q <= q1;
	end
end
endmodule
```
![dff_const4](https://user-images.githubusercontent.com/62461290/183976465-1bf36653-40ee-40d1-acf6-ee6717d7dfc1.png)
<br>
```
module dff_const5(input clk, input reset, output reg q);
reg q1;
always @(posedge clk, posedge reset)
begin
	if(reset)
	begin
		q <= 1'b0;
		q1 <= 1'b0;
	end
	else
	begin
		q1 <= 1'b1;
		q <= q1;
	end
end
endmodule
```
![dff_const5](https://user-images.githubusercontent.com/62461290/183976473-7f0d7366-d4a9-4431-a9a9-fa912324e33c.png)
<br>



## 4.3 SKY130RTL D3SK3 - Sequential Logic Optimizations for unused outputs
```
module counter_opt (input clk , input reset , output q);
reg [2:0] count
assign q = count[0];
always @(posedge clk ,posedge reset)
begin
	if(reset)
		count <= 3'b000;
	else
		count <= count + 1;
end
endmodule
```
![counter_opt](https://user-images.githubusercontent.com/62461290/183979828-c9e51415-c1ce-4074-aa71-d5b686a98975.png)


# 5. DAY 4 - GLS, Blocking VS Non-blocking and Synthesis-Simulation mismatch
## 5.1 SKY130RTL D4SK1 - GLS, Synthesis-Simulation mismatch and Blocking/Non-blocking Statements
### 5.1.1 SKY130RTL D4SK1 L1 GLS Concepts and Flow Using iVerilog
- GLS stands for Gate level simulation.<br>
- It is used to verify the logical correctness of design after synthesis.<br>
- It also ensures the timing of the design is met. The GLS needs to be run with delay annotation.<br>

![Screenshot 2022-08-10 231242](https://user-images.githubusercontent.com/62461290/183980525-0f3e6f6c-fbaf-44d7-b27d-bb716e60602c.png)

### 5.1.2 SKY130RTL D4SK1 L2 Synthesis and Simulation Mismatch

Synthesis Simulation Mismatch(SSM) is mainly due to two reasons.<br>
1. Missing sensititivity list <br>
2. Blocking and non blocking statements <br>

### 5.1.3 SKY130RTL D4SK1 L3 Blocking and Non-Blocking Statements in Verilog
In a verilog code, blocking statements are in sequential order, where as non blocking statements are executed in concurrent fashion.<br>


### 5.1.4 SKY130RTL D4SK1 L4 Caveats with Blocking Statements
## 5.2 SKY130RTL D4SK2 - Labs on GLS and Synthesis-Simulation Mismatch
### 5.2.1 SKY130RTL D4SK2 L1 Lab GLS and Synthesis-Simulation Mismatch part1
### 5.2.2 SKY130RTL D4SK2 L2 Lab GLS and Synthesis-Simulation Mismatch part2
## 5.3 SKY130RTL D4SK3 - Labs on Synthesis-Simulation mismatch for blocking statements
### 5.3.1 SKY130RTL D4SK3 L1 Lab Synthesis-Simulation mismatch for blocking statements part1
### 5.3.2 SKY130RTL D4SK3 L2 Lab Synthesis-Simulation mismatch for blocking statements part2
  
# 6. DAY 5 - If, case, for loop and for generate 
## 6.1 SKY130RTL D5SK1 - If Case constructs
### 6.1.1 SKY130RTL D5SK1 L1 If Case Constructs part1
### 6.1.2 SKY130RTL D5SK1 L2 If Case Constructs part2
### 6.1.3 SKY130RTL D5SK1 L3 If Case Constructs part3
## 6.2 SKY130RTL D5SK2 - Labs on "Incomplete If Case"
### 6.2.1 SKY130RTL D5SK2 L1 Lab Incomplete If part1
### 6.2.2 SKY130RTL D5SK2 L2 Lab Incomplete If part2
## 6.3 SKY130RTL D5SK3 - Labs on "Incomplete and Overlapping Case"
### 6.3.1 SKY130RTL D5SK3 L1 Lab Incomplete and Overlapping Case part1
### 6.3.2 SKY130RTL D5SK3 L2 Lab Incomplete and Overlapping Case part2
### 6.3.3 SKY130RTL D5SK3 L3 Lab Incomplete and Overlapping Case part3
### 6.3.4 SKY130RTL D5SK3 L4 Lab Incomplete and Overlapping Case part4
## 6.4 SKY130RTL D5SK4 - For Loop and For Generate
### 6.4.1 SKY130RTL D5SK4 L1 For Loop and For Generate part1
### 6.4.2 SKY130RTL D5SK4 L2 For Loop and For Generate part2
### 6.4.3 SKY130RTL D5SK4 L3 For Loop and For Generate part3
## 6.5 SKY130RTL D5SK5 - Labs on "For loop" and "For Generate"
### 6.5.1 SKY130RTL D5SK5 L1 Lab For and For Generate part1
### 6.5.2 SKY130RTL D5SK5 L2 Lab For and For Generate part2
### 6.5.3 SKY130RTL D5SK5 L3 Lab For and For Generate part3
### 6.5.4 SKY130RTL D5SK5 L4 Lab For and For Generate part4

