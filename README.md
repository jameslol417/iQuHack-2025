# Quantum Rings Challenge - iQuHack 2025

## Overview
This repository contains our submission for the **Quantum Rings Challenge** at **MIT iQuHack 2025**. Our implementation leverages pure quantum algorithms to factor large semiprime integers using the **Quantum Rings Simulator**, demonstrating the power of quantum computing in the realm of cryptography and computational theory.

## Challenge Background
Shor’s algorithm has shown that quantum computers can factor large integers exponentially faster than classical computers. This challenge focuses on applying quantum algorithms to factor increasingly larger semiprimes using the Quantum Rings Simulator, which allows for the simulation of circuits with hundreds of qubits and millions of gate operations.

## Implementation Details

### Our Approach
Our solution:
- Implements **Shor’s algorithm** and variations designed to optimize execution on the **Quantum Rings Simulator**.
- Focuses on **scalability** by ensuring the ability to factor multiple semiprimes of at least the same bit size.
- Uses only **quantum operations**, avoiding classical optimizations to comply with challenge requirements.
- Provides detailed **documentation** on execution results, including the number of qubits used, gate operations, and performance metrics.

### Results

Our implementation has successfully factored semiprime numbers of increasing bit sizes.    
We have used 6895 gate operations and 54 qubits using the Quantum Rings Simulator to succesfully find the factor of a 18 bit semiprime.   
<!-- we just found 18 bits semiprime -->
<!-- The runtime for the search took about 637 seconds. -->


Acknowledgments

We extend our gratitude to MIT iQuHack, Quantum Rings, and the broader quantum computing community for organizing this challenge and providing cutting-edge simulation tools.

Authors: K-Quantum Tigers(@jameslol417, @jjmain, @jinholeetopology)
