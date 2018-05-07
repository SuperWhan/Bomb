# Bomb
Bomb lab for 2021

# Method:
	This is a lab project for Computer Architecture class (CSCI 2021), we suppose to defused the bomb without explosion.

# Applied Skills:
	GDB, Assembly coding skills, memory checking, convert assembly code to C. knowledge of pipeline, high level cache.
# Hardest part:
	Last three phases are very hard, with prediction, translation and guess to defused the bomb. First need to set the breakpoint (in gdb)
at correct phase, otherwise, once you give wrong passcode, it will explode, then take out it's assembly code, check all register's value and 
memory address, find the compare stage, or find the structure it defined. give futher guess and set breakpoint2 to take futher actions. in the
last three phases, it is very easy to explode once set breakpoint at incorrect memory address.
