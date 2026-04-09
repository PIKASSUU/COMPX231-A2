# COMPX231-A2

# Hello ^_^

# Description
This project implements the Readers-Writers Problem using a Monitor in Python.

# Features
1.For thread synchronization,it is a Monitor-based solution. 
2.Multiple readers can read simultaneously when no writer is active.
3.Writers can have exclusive access to the resource.
4.Thread-safe implementation using Python's threading module.

# Rules
1.If no writer is writing,Multiple readers may read together.
2.A writer must have exclusive access.
3.Only use the monitor methods to control access.