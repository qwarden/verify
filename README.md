# verify
## A verifier for uvm cs202 compilers
verify compares the output of the online compiler provided by the instructor to the output of your local compiler on a given test case(s).
## Setup
Put this script in your cs202-assignments directory and run `python verify.py --help` for usage.
Use the `-d` flag to show the strings that were extracted from both compilers. If the local compiler string is not an AST, there is probably an issue
with your compiler. Run your compiler on a test case like `python compiler.py tests/test1.py` to determine what the error is.
