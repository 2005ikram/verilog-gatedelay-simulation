# Verilog Gate Delay Simulation

Gate-level Verilog simulation with propagation delays and waveform analysis.

## What does this circuit do?

The circuit is defined as a netlist, which means it describes the building blocks (logic gates) and their interconnections. The Verilog code is written using structural modeling at the gate level. The main objective of this project is to study propagation delays and learn how to analyze simulation waveforms.

## Logic Equations (Behavioral Description)

t1 = ~(A & B)  → Output of Gate 1 (delay = 1)

t2 = C & ~B & D  → Output of Gate 2 (delay = 2)

t3 = ~(E | F)  → Output of Gate 3 (delay = 1)

Y = ~(t1 & t2 & t3)  → Final circuit output (delay = 1)

## Simulation Setup

* EDA Playground
* EPWave
* $dumpfile
* $dumpvars
* $monitor

## What I Learned

* Writing simple Verilog code using structural modeling.
* Writing testbenches for simulation in EDA Playground.
* Learning how to create a VCD (Value Change Dump) file.
* Using the `$dumpfile` and `$dumpvars` commands in a testbench.
* Learning how to analyze waveforms in EPWave.
* Verifying that simulation results match the expected output.
* Understanding the effect of propagation delays on circuit behavior.

## Waveform
![Waveform](timingdiagram.png)

