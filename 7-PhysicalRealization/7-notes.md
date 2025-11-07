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

## 7.3 | Harmonic oscillator quantum computer
- Qubit representation: Energy levels $|0\rangle$, $|1\rangle$, . . ., $|2n\rangle$ of a single quantum oscillator give n qubits.
- Unitary evolution: Arbitrary transforms $U$ are realized by matching their eigenvalue spectrums to that given by the Hamiltonian H = a† a.
- Initial state preparation: Not considered.
- Readout: Not considered.
- Drawbacks: Not a digital representation! Also, matching eigenvalues to realize transformations is not feasible for arbitrary U , which generally have unknown
eigenvalues.

## 7.4 | Optical photon quantum computer
- Qubit representation: Location of single photon between two modes, $|01\rangle$ and $|10\rangle$, or polarization.
- Unitary evolution: Arbitrary transforms are constructed from phase shifters (Rz rotations), beamsplitters (Ry rotations), and nonlinear Kerr media, which allow
two single photons to cross phase modulate, performing $exp[iχL|11\rangle\langle 11|]$ .
- Initial state preparation: Create single photon states (e.g. by attenuating laser light).
- Readout: Detect single photons (e.g. using a photomultipler tube).
- Drawbacks: Nonlinear Kerr media with large ratio of cross phase modulation strength to absorption loss are difﬁcult to realize.