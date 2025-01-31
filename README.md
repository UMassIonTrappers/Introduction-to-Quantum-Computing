# Intro to Quantum Computing - ECE 550/650

### Quantum Optics ->  Qubits -> Quantum Algorithms

Introduction to quantum computing starts with a basis in quantum optics using the Mach Zehnder Interferometer as a foundation. We then survey various qubit technology modalities such as trapped ions, photonics and Transmons as well as sources of decoherence for each.  In weekly Python labs students program simulations of single qubit operations such as Rabi and Ramsey pulse sequences as well as two qubit manipulations for Bell state generation to construct quantum circuits from fundamental quantum mechanical interactions. In the 2nd half of the semester these labs culminate in programming simulations of quantum algorithms by Grover and Shor using quantum computing Python libraries such as Qiskit and QuTiP and executing them on real quantum computers.

# Labs
Labs will be simulations of single qubit operations such as Rabi and Ramsey pulse sequences and then entanglement of two qubits and bell state generation. This will allow us to construct quantum circuits from fundamental quantum mechanical interactions, effectively seeing into the ‘black box’ of quantum circuits. Finally, in the second half of the course we will program simulations of quantum algorithms by Grover and Shor using the Qiskit and QuTIP python libraries.


## Supporting Materials:
### Quantum Optics:
  * Ivan H. Deutsch’s Notes - http://info.phys.unm.edu/~ideutsch/Classes/Phys566F21/

  * Daniel Steck’s Notes - https://atomoptics.uoregon.edu/~dsteck/teaching/quantum-optics/

### Quantum Computation:
  * Thomas Wong’s Textbook: https://www.amazon.com/Introduction-Classical-Quantum-Computing-Thomas-dp-B09QP2MYYM/dp/B09QP2MYYM/
  * http://www.thomaswong.net/introduction-to-classical-and-quantum-computing-1e4p.pdf

* IBM’s Qiskit Textbook - https://qiskit.org/textbook-beta

* Scott Aaronson - https://www.scottaaronson.com/qclec.pdf

* John Preskill - http://theory.caltech.edu/~preskill/ph219/chap6_20_6A.pdf

### Mike & Ike:
  * Quantum Computation and Quantum Information , Authors: Michael A. Nielsen, Isaac L. Chuang


# How to use these Notebooks

1. Create a copy for you to edit and update the filename with your name.
1. Turn on the table of contents
1.  Experiment! These notebooks are just a starting point for you to explore. If you have ideas for things to try start by typing out the pseduo code first then see if you can find help to get the syntax and libraries to make it work.
1. Teamwork. Working in teams will help everyone check their code and debug errors. Please work in groups of up to three people. You may all share code but please maintain your own copy of the notebook to turn in for credit.
1. Hand written paper notebook still recommended. This colab notebook is a supplement to a paper notebook and the textbooks listed above. To test out ideas, check mathematical relations and linear algebra proofs and to complete exercises you will need a real physical paper notebook to do your work. Please have one and a pen/pencil handy.


## Programming Resources:
*   https://colab.research.google.com/notebooks/basic_features_overview.ipynb
*   https://www.dataquest.io/blog/jupyter-notebook-tutorial/
*   https://www.youtube.com/watch?v=inN8seMm7UI
*   https://nbviewer.ipython.org/github/qutip/qutip-notebooks/blob/master/examples/qubit-dynamics.ipynb
* FYI: Colab provides hardware acceleration with GPUs and TPUs if you go to 'Runtime>Change Runtime type'


![image](https://github.com/user-attachments/assets/9fa08c27-c172-47f5-8e45-78d4e00ac5f1)


# Outline of the course:

### Quantum Optics: 
* Mach Zehnder Interferometers
* Superposition states and probabilities
* Bloch Sphere, ⟨Bra||Ket⟩ notation
* Stern Gerlach Experiment (measurement)

### Qubit Technologies: 
* Trapped Ions
* Neutral Atoms 
* Transmons
* Si spin/Quantum dots
* Photonics 

### Qubit Dynamics: 
* Time-Dependent Schrodinger Equation
* Rotating Wave Approximation (QR CODE)
* Rabi Oscillations (single qubit gates)
* Ramsey Interferometry
* Two qubit gates
* Entanglement
* Toffoli multi-qubit gates

### Quantum Algorithms:
* Quantum Adder
* Grover’s Search
* Phase Kickback 
* Deutsch Jozsa
* Bernstein-Vazirani 
* Quantum Fourier Transform 
* Quantum Phase Estimation
* Review of RSA encryption
* Shor’s Algorithm 
