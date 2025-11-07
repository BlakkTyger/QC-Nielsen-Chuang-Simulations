# Chapter 7: Physical Realizationf of Quantum Computers

## 7.2 | Conditions for quantum computation

1. Robustly represent quantum information
2. Perform a universal family of unitary transformations
3. Prepare a ﬁducial initial state
4. Measure the output result

### 7.2.1 | Representation of Quantum Information
- 2 states of spin-1/2 particle can be used to represent 1 qubit
- 4 states of spin-3/2 particle can be used to represent 2 qubits
- set of accessible states should be ﬁnite. eg: position x of particle has infinite dim Hilbert Space, so it can't be used to construct qubits
- Choice of representation is crucial: Square well which is just deep enough to contain 2 bound energy states is not a good qubit because:
  - transitions from the bound states to the continuum of unbound states would be possible; causing decoherence

**Metrics for determining a 'good' qubit**
1. $T_2$, the (‘transverse’) relaxation time of states such as $(|0\rangle + |1\rangle)/\sqrt{2}$
2. $T_1$ , the (‘longitudinal’) relaxation time of the higher energy $|1\rangle$ state

**Square wells and qubits**
