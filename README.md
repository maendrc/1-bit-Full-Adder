• Design a 1-bit static CMOS full adder circuit

• Measure delay and power

• Perform the corner / monte-carlo simulations to verify mismatch

• Design layout and perform post-layout simulation. Compare pre- and post- layout simulation and briefly 
analyze the results.


Specifications
• Global power supply (VDD) = 1.2 V
• Define the minimum Pmos width (Wp) when Wn=200nm to equalize the 
propagation delays (tpLH = tpHL) of an Inverter (when the output load = 10fF)
• The fastest input frequency : 1 GHz @ TT 27°C
• Use a buffer after each voltage source in testbench
• Voltage source rise/fall time: 100ps each
• Output load : 10 fF
• All transistor channel lengths = 60 nm
• There is a input buffer (2-stage inverter with Wp/Wn) The power consumption of the second inverter should be included 
in the full adder power calculation

THE STRUCTURE OF THE REPORT
1. Introduction
2. Circuit design and transistor sizing
3. Simulation results and analysis
1. Functional waveforms
2. Worst-case input-transition combination
3. Power, Delay, PDP Global & Local mis-match
4. Layout & Post-layout Simulation 
5. Conclusion
