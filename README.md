# Assembly-Interpreter-AQA
An unofficial interpreter for AQA assembly code


for AQA instruction set:
http://filestore.aqa.org.uk/resources/computing/AQA-75162-75172-ALI.PDF


Notes for this interpreter:
- // can be used for comments.
- HALT isn't necessary at the bottom of the file as it terminates automatically.
- Memory locations may be accessed with #n or registers with Rn
- To change the memory size or number of registers, change the constants at the top of interpreter.py
- Labels need ':' at the end
- Labels must be unique

This is a basic interpreter using the instruction set of the AQA exam.
Two tests are currently available as a demonstration.
There is minimal syntax checking, but the debug info gives information will usually raise an error if something is wrong.
If you do find any issues, you can create an issue on Github, or email me directly.

To run your code, run src/interpreter.py and type your filename (the file needs to be in the src folder)

Jack Parsons
7/6/17
