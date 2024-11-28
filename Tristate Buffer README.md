
Tristate Buffer in Verilog
Project Overview
This project implements a Tristate Buffer in Verilog, a crucial component in digital systems for controlling bidirectional data flow. The buffer allows data to pass through when enabled and isolates the output when disabled. This behavior is essential for bus systems or situations where multiple devices share a single data line.

Key Features:
Bidirectional data control: Allows data to be driven onto the output only when the output enable (OE) is active.
High impedance state: When the output enable is inactive, the output is in a high-impedance state, effectively disconnecting the buffer from the output bus.
Technologies/Tools Used:
Verilog: For the implementation of the Tristate Buffer.
Testbenches: Verilog-based testbenches for simulating and verifying functionality.
Functionality
Input Signal (input_x): The data to be output when enabled.
Enable Signal (enable): Controls whether the buffer output is active or in a high-impedance state.
Output Signal (output_x): The data driven onto the output when enabled.
Logic
When enable is 1, output_x follows the value of input_x.
When enable is 0, output_x is in a high-impedance state ('bz).
