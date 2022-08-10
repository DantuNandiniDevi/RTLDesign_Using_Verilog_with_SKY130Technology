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
  - [2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux part1](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#241-sky130rtl-d1sk4-l1-lab3-yosys-1-good-mux-part1) <br>
  - [2.4.2 SKY130RTL D1SK4 L2 lab3 Yosys 1 good mux part2](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#242-sky130rtl-d1sk4-l2-lab3-yosys-1-good-mux-part2) <br>
  - [2.4.3 SKY130RTL D1SK4 L3 lab3 Yosys 1 good mux part3](https://github.com/DantuNandiniDevi/RTLDesign_Using_Verilog_with_SKY130Technology/blob/main/README.md#243-sky130rtl-d1sk4-l3-lab3-yosys-1-good-mux-part3) <br>

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
### 2.3.2 SKY130RTL D1SK3 L2 Introduction to logic synthesis part1
### 2.3.3 SKY130RTL D1SK3 L3 Introduction to logic synthesis part2
## 2.4 SKY130RTL D1SK4 - Labs Using Yosys and SKY130 PDKs
### 2.4.1 SKY130RTL D1SK4 L1 lab3 Yosys 1 good mux part1
### 2.4.2 SKY130RTL D1SK4 L2 lab3 Yosys 1 good mux part2
### 2.4.3 SKY130RTL D1SK4 L3 lab3 Yosys 1 good mux part3

# 3. DAY 2 - Timing libs, hierarchical vs flat synthesis and efficient flop coding styles
## 3.1 SKY130RTL D2SK1 - Introduction to timing dot libs
### 3.1.1 SKY130RTL D2SK1 L1 Lab4 Introduction to dot lib part1
### 3.1.2 SKY130RTL D2SK1 L2 Lab4 Introduction to dot lib part2
### 3.1.3 SKY130RTL D2SK1 L3 Lab4 Introduction to dot lib part3
## 3.2 SKY130RTL D2SK2 - Hierarchical vs Flat Synthesis
### 3.2.1 SKY130RTL D2SK2 L1 Lab 5 Hierarchical vs Flat Synthesis part1
### 3.2.2 SKY130RTL D2SK2 L2 Lab 5 Hierarchical vs Flat Synthesis part2
## 3.3 SKY130RTL D2SK3 - Various Flop Coding Styles and Optimization
### 3.3.1 SKY130RTL D2SK3 L1 Why Flops and Flop coding styles part1
### 3.3.2 SKY130RTL D2SK3 L2 Why Flops and Flop coding styles part2
### 3.3.3 SKY130RTL D2SK3 L3 lab Flop Synthesis Simulation part1
### 3.3.4 SKY130RTL D2SK3 L4 lab Flop Synthesis Simulation part2
### 3.3.5 SKY130RTL D2SK3 L5 Interesting Optimisations part1
### 3.3.6 SKY130RTL D2SK3 L6 Interesting Optimisations part2

# 4. DAY 3 - Combinational and Sequential Optimizations
## 4.1 SKY130RTL D3SK1 - Introduction to Optimizations
### 4.1.1 SKY130RTL D3SK1 L1 Introduction Optimizations Part1
### 4.1.2 SKY130RTL D3SK2 L2 Introduction Optimizations Part2
### 4.1.3 SKY130RTL D3SK3 L3 Introduction Optimizations Part3
## 4.2 SKY130RTL D3SK2 - Combinational Logic Optimizations
### 4.2.1 SKY130RTL D3SK2 L1 Lab 6 Combinational Logic Optimizations part1
### 4.2.2 SKY130RTL D3SK2 L2 Lab 6 Combinational Logic Optimizations part2
## 4.3 SKY130RTL D3SK3 - Sequential Logic Optimizations
### 4.3.1 SKY130RTL D3SK3 L1 Lab 7 Sequential Logic Optimizations part1
### 4.3.2 SKY130RTL D3SK3 L2 Lab 7 Sequential Logic Optimizations part2
### 4.3.3 SKY130RTL D3SK3 L3 Lab 7 Sequential Logic Optimizations part3
## 4.4 SKY130RTL D3SK3 - Sequential Logic Optimizations for unused outputs
### 4.4.1 SKY130RTL D3SK4 L1 Sequential Logic Optimizations for unused outputs part1
### 4.4.2 SKY130RTL D3SK4 L2 Sequential Logic Optimizations for unused outputs part2


# 5. DAY 4 - GLS, Blocking VS Non-blocking and Synthesis-Simulation mismatch
## 5.1 SKY130RTL D4SK1 - GLS, Synthesis-Simulation mismatch and Blocking/Non-blocking Statements
### 5.1.1 SKY130RTL D4SK1 L1 GLS Concepts and Flow Using iVerilog
### 5.1.2 SKY130RTL D4SK1 L2 Synthesis and Simulation Mismatch
### 5.1.3 SKY130RTL D4SK1 L3 Blocking and Non-Blocking Statements in Verilog
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

