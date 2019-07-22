# qiskit-quantum-algorithms
A collection of basic quantum algorithms implemented under the IBM Q Quantum Information Science Kit (Qiskit), a Python quantum computing framework.

## bell.py - Bell state

This algorithm demonstrates the creation of a Bell state.

In this state, 2 qubits are entangled to create a unified final state
probability distribution between the two.
We then proceed with the execution on the QASM simulator, a quantum
virtual machine.

### The ASCII diagram of the resulting circuit
         ┌───┐     
q0_0: |0>┤ H ├──■──
         └───┘┌─┴─┐
q0_1: |0>─────┤ X ├
              └───┘
 c0_0: 0 ══════════
                   
 c0_1: 0 ══════════

