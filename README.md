# VHDL Counter Overflow Bug
This repository demonstrates a common error in VHDL:  a counter that lacks proper overflow handling. The `buggy_counter.vhdl` file contains code for a counter that could produce unexpected results if it exceeds its defined range (0 to 15).

The `fixed_counter.vhdl` file provides a corrected version with robust overflow protection. This example highlights the importance of carefully considering boundary conditions when designing VHDL code.