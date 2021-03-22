# Qiskit-Tutorial

![](https://raw.githubusercontent.com/AkashGutha/Qiskit-Snippets/master/assets/qiskit.gif)

### Don't forget to make an [IBM Quantum Experience Account](https://quantum-computing.ibm.com/). account to run the code and try new things with Qiskit.

![alt](../main/readme/IBM_Quan.png)


### I've tried my best to comment most of the parts , some parts maybe repetitive in [Qiskit_Basics](../main/code/Qiskit_Basics.ipynb) as its the introduction, the commenting gets less agressive right after.

### Code Sample:
```python
qc = QuantumCircuit(1, 1) # Initialisation of 1 qubit , 1 classical bit circuit.
qc.x(0) # Adding an Xgate to q1
qc.measure(0, 0) # Measuring q1
qc.draw() # Drawing the quantum circuit
```
### Output:
![alt](../main/readme/xgate.png)

