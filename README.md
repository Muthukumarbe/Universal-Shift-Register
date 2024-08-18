Explaination:
* clk is the clock signal.
* reset is the reset signal to initialize the register.
* mode is a 2-bit input to control the operation of the shift register:
	* 00: Hold the current value.
	* 01: Shift left.
  * 10: Shift right.
	* 11: Load parallel data.
* parallel_in is the 4-bit parallel data input.
* serial_in_left is the serial data input for left shift.
* serial_in_right is the serial data input for right shift.
* q is the 4-bit register output.
