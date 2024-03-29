# qiskit-quantum-algorithms
A collection of basic quantum algorithms implemented under the **IBM Q** Quantum Information Science Kit (**Qiskit**), a Python quantum computing framework.

## bell.py - Bell state

This algorithm demonstrates the creation of a Bell state.

In this state, 2 qubits are **entangled** to create a link between their final and intermediate states.
Let X and Y be the entangled qubits.
When qubit X collapses into the state 0, Y then must be in the state 1.
Through this concept, we create a unified final state probability distribution between
the two and proceed with the execution on the **QASM** simulator, a quantum virtual
machine.

### The plaintext diagram of the resulting circuit
```  
         ┌───┐   
q0_0: |0>┤ H ├──■──
         └───┘┌─┴─┐
q0_1: |0>─────┤ X ├
              └───┘
 c0_0: 0 ══════════
                   
 c0_1: 0 ══════════

```
