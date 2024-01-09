# Quantum Cicruit of Modular Exponentiation in Qiskit
We are constructing a circuit for Modular Exponentiation in Qiskit.

This is based on the paper ["Quantum Networks for Elementary Arithmetic Operations"](https://arxiv.org/pdf/quant-ph/9511018.pdf) by Vlatko Vedral, Adriano Barenco and Artur Ekert in this circuit. 

>We assume that $gcd(a,N)=1$ which is not mentioned in the paper. However, this is infact necessary to preserve the unitarity of certain operations that we perform.

>We also note that $a$ and $x$ used in the modular exponentiation are bounded by the value of $N$. Specifically. since $a\leq N$ and $x\leq N^2$ for the purpose of Shor's algorithms, $a$ is encoded in $\log(N)$ bits and $x$ is encoded in $2\log(N)$ bits.

Computing for $n=4$ and above require a large number of qubits and will have to be run on 'ibmq\_qasm\_simulator'

## Contributers
- Writika Sarkar
- Soham Chatterjee
- Shree Ganesh SJ
