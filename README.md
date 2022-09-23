# Linkers and Loaders
A two pass direct linking loader was implemented in C. The input to the first pass of the system was the object file containing 
the various control sections of the programs to be linked. The output of the first pass, an external symbol table containing the 
addresses of external symbols, was input to the second to the second pass along with the object file. The output of the second pass 
was the object program loaded into the memory locations specified.
