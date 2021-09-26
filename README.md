# Turing-Machine-Emulator

usage: ./main [MACHINE DEFINITION] [AUTOMATA INPUT] [MAX TRANSITIONS]"

Example: ./main p1_machine_t1.txt aabaacaac 100

Using the automata machine defined in file "p1_machine_t1.txt", return the tape after the input aabaacaac, with a maximum transition amount of 100.

States are in the form of: state, id, accept/reject

Transitions are in the form of: current_state, read, goto_state, write, direction


Sample Machine Definition File:


state	9	reject

state	1

state	41

state	3	accept

transition	657	,	661	$	R

transition	657	a	658	$	R


