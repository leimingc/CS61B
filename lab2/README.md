The lab is an implementation for a naked recursive linked list of integers. Each IntList has a first and rest variable. The first is the int element contained by the node, and the rest is the next chain in the list (another IntList!).

I added two functions in the class:

dcatenate(IntList A, IntList B): returns a list consisting of all elements of A, followed by all elements of B. May modify A.
catenate(IntList A, IntList B): returns a list consisting of all elements of A, followed by all elements of B. May not modify A.
