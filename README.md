# Intro to Quantum Computing - ECE 550/650

© Robert Niffenegger (2025)

rniffenegger@umass.edu

### Quantum Optics →  Qubits → Quantum Algorithms

Introduction to Quantum Computing begins with a foundation in quantum optics, studying the Mach-Zehnder interferometer. We then explore atomic physics and quantum mechanics in the context of various qubit technologies, such as trapped ions.

Throughout the semester, students engage in weekly Python labs based on QuTiP where they program simulations of single-qubit operations, including Rabi oscillations and Ramsey pulse sequences, as well as generating two-qubit from first principles with Hamiltonians for generating entanglement (Bell states). These exercises enable construction of quantum circuits based on fundamental quantum mechanical interactions via Hamiltonians.

In the second half of the semester, these labs culminate in a survey and simulation of multiple quantum algorithms, such as Grover’s and Shor’s algorithms, as well as rudimentary error correction, using quantum computing libraries like Qiskit. Students also gain hands-on experience by executing their programs on real quantum computers.

#### Discord: https://discord.gg/zwXMNDdDN5 

## Labs
Labs will start with simulations in QuTiP of single qubit operations such as Rabi and Ramsey pulse sequences and then entanglement of two qubits and bell state generation. This will allow us to construct quantum circuits from fundamental quantum mechanical interactions, effectively seeing into the ‘black box’ of quantum circuits. 
In the second half of the course we will program simulations of quantum algorithms by Grover and Shor using the Qiskit and QuTIP python libraries.

1. [Lab_01_Quantum_states_and_the_Bloch_sphere.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_01_Quantum_states_and_the_Bloch_sphere.ipynb)
1. [Lab_02_Measurement_Basis,_Spatial_quantization_and_the_Stern_Gerlach_Exp.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_02_Measurement_Basis%2C_Spatial_quantization_and_the_Stern_Gerlach_Exp_.ipynb)
1. [Lab_03 - Time_Dep_Schr%C3%B6dinger_Eq_and_Rabi_Oscillations.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_03A_Time_Dep_Schr%C3%B6dinger_Eq_and_Rabi_Oscillations.ipynb)
1. [Lab_04_RWA_Rabi_oscillations_and_detuning.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_04_RWA_Rabi_oscillations_and_detuning.ipynb)
1. [Lab_05 - Part A -_X_vs_Y_pulses.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_05a_X_vs_Y_pulses.ipynb)
1. [Lab_05 - Part B -_Ramsey.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_05b_Ramsey.ipynb)
1. [Lab_05_Noise_and_composite_pulses.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_05_Noise_and_composite_pulses.ipynb)
1. [Lab_06_- Two Qubit Gates and Entanglement.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_06_2_Qubit_gates.ipynb)
1. [Lab_07_- Lab_07_Quantum_circuits_quantum_adder.ipynb](https://colab.research.google.com/github/UMassIonTrappers/quantum-computing-labs/blob/main/labs/Lab_07_Quantum_circuits_quantum_adder.ipynb)


Rotating Wave Approximation animation from Lab 4:

<img src="https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/animations/EXACT_resonance_rotating.gif?raw=true" height="250"> <img src="https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/animations/Rabi_oscillation_2D_vs_time_detuning_w_bloch.gif?raw=true" height="250">

<img src="https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/animations/RWA_with_drive_phase_X_vs_Y.gif?raw=true" height="200"> <img src="https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/animations/OddEvenParityOscillationsDensityMatrix.gif?raw=true" height="200">



## Lecture Notes:
* [Quantum-Computing-ECE-550.pdf](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)

<a href="https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0">
  <img src="https://github.com/user-attachments/assets/aaec4e89-cbae-414f-bc8d-8618a6c14703" width="600"/>
</a>


## Lecture recordings:
1. [Lecture 1 (Jan 31) - Introduction.mp4](https://echo360.org/media/429f82d9-5ae3-47b0-b9b0-78e48ced89a8/public)
1. [Lecture 2 (Feb 3) - Intro and feeble light.mp4](https://echo360.org/media/86572df4-21ed-4bd9-9a94-608b08bc80df/public)
1. [Lecture 3 (Feb 5) - Mach Zehnder Interferometer.mp4](https://echo360.org/media/d6befcf8-462c-4bcd-9168-47031aafae69/public)
1. [Lecture 4 (Feb 7) - MZI with phase shift + quantum circuits.mp4](https://echo360.org/media/48ffbcf1-3f8b-4ad7-ae15-27fbe0373762/public)
1. [Lecture 5 (Feb 10) - BraKet Notation and Bloch Sphere.mp4](https://echo360.org/media/57cdb837-0aa9-447f-89ba-2562d0822c4e/public)
1. [Lecture 6 (Feb 12) - Rotations on the Bloch Sphere and Intro to Stern Gerlach.mp4](https://echo360.org/media/1a0999db-5f07-46ed-97c6-a9cac090ac99/public)
1. [Lecture 7 (Feb 14) - Stern Gerlach and projection/measurement in X,Y Basis states.mp4](https://echo360.org/media/42eca949-cbd3-46e7-95e3-e97c8d4f661c/public)
1. [Lecture 8 (Feb 19) - Projection review and the Schrodinger Equation.mp4](https://echo360.org/media/6c1e4f20-3c71-4a59-83c8-5603704c0be1/public)
1. [Lecture 9 (Feb 20) -  MSFT's search for Majorana and more Time Dependent Schrodinger Equation.mp4](https://echo360.org/media/9f6f4f16-953b-4484-9396-857d0bdac4dd/public)
1. [Lecture 10 (Feb 21) - Rabi Oscillations and Infinite Square Well.mp4](https://echo360.org/media/860ab198-ce27-41b1-9f2b-defcbfda0771/public)
1. [Lecture 11 (Feb 24) - Rotating Wave Approximation part 1 - resonance.mp4](https://echo360.org/media/02c291df-1e80-4991-bc24-0288ed0f32e3/public)
1. [Lecture 12 (Feb 26) - Rotating Wave Approximation part 2 - rotating frames.mp4](https://echo360.org/media/fdbc771b-68d4-45ef-835d-2e19d06f4552/public)
1. [Lecture 13 (Feb 28) - Rotating Wave Approximation part 3 - detuned rotating frames.mp4](https://echo360.org/media/f8dc5b4a-177a-4f37-abd6-1e00b300f016/public)
1. [Lecture 14 (Mar 3) - RWA review - X vs. Y drives from phase of drive.mp4](https://echo360.org/media/260e74b8-a5ec-4ce4-b49d-f806cae0c975/public)
1. [Lecture 15 (Mar 5) - Composite Pulse Sequences and Ramsey.mp4](https://echo360.org/media/4116e1ad-cc11-47da-b9fe-dafd98a2156c/public)
1. [Lecture 16 (Mar 7) - Ramsey and intro to 2Q.mp4](https://echo360.org/media/b41cc01e-44d3-4b70-a49a-d30066ccc803/public)
1. [Lecture 17 (Mar 10) - Two Qubit Gates.mp4](https://echo360.org/media/688eedcd-f871-4350-b377-01242d3cf33c/public) 
1. [Lecture 18 (Mar 12) - Verifying Entanglement - odd even basis.mp4](https://echo360.org/media/1a6652a8-ca38-493d-ab52-4d220d7332df/public) 
1. [Lecture 19 (Mar 24) - Midterm exam review.mp4](https://echo360.org/media/93c15d75-8328-4bec-9981-f476882feb54/public) 
1. [Lecture 20 (Mar 26) - Quantum Adder.mp4](https://echo360.org/media/dcbf89b4-e51b-44e3-9d78-54b2da3dd32a/public) 
1. [Lecture 21 (Mar 28) - Transpiling quantum circuits for IBM Cloud QPUs.mp4](https://echo360.org/media/c27ecad8-03be-47be-a512-3e1fd5b2fef1/public) 


## Lecture Slides: 
1. [Lecture 1 - Introductions.pdf](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW05%20-%20Lecture%2001%20-%20Introductions.pdf)
1. [Lecture 2 - Intro and feeble light.pdf](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW06%20-%20Lecture%2002%20-%20Intro%20and%20feeble%20light.pdf)
1. [Lecture 3 - Mach Zehnder Interferometer (pg1-9)](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)
1. [Lecture 4 - MZI with phase shift + quantum circuits (pg 11-17)](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)
1. [Lecture 5 - BraKet Notation and Bloch Sphere.pdf](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW07%20-%20Lecture%2005%20-%20BraKet%20notation%20and%20the%20Bloch%20Sphere.pdf)
1. [Lecture 6 - Rotations on the Bloch Sphere.pdf](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW07%20-%20Lecture%2006%20-%20Rotations%20on%20the%20Bloch%20Sphere.pdf)
1. [Lecture 7 - Stern Gerlach and projection/measurement in X,Y Basis states.pdf](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW07%20-%20Lecture%2007%20-%20Stern%20Gerlach.pdf)
1. [Lecture 8 - Projection review and the Schrodinger Equation (pg 36-46)](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)
1. [Lecture 9 - Time Dependent Schrodinger Equation (pg 41-46)](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)
1. [Lecture 10 - Rabi Oscillations and Infinite Square Well (also Lab 3 and notes pg 45-48)](https://www.dropbox.com/scl/fi/uc33ums197igwtgcoo27s/Quantum-Computing-ECE-550.pdf?rlkey=ofzlqgl3oyb3wf6jr42blohxu&dl=0)
1. [Lecture 11-13 - Rotating Wave Approximation (also Lab 4 and notes pg 49-56](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW09%20-%20Lab%204%20-%20Rotating%20Wave%20Approximation.pdf)
1. [Lecture 14-16 - Noise and Composite Pulse Sequences (Lab 5)](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW10%20-%20Lab%205%20-%20Noise%20and%20Composite%20Pulse%20Sequences.pdf)
1. [Lecture 17-18 - Noise and Composite Pulse Sequences (Lab 6)](https://github.com/UMassIonTrappers/Introduction-to-Quantum-Computing/blob/main/lectures/WW11%20-%20Lab%206%20-%20two%20qubit%20gates.pdf)
1. [Lecture 20 - Quantum Adder (Lab 7)](https://www.dropbox.com/scl/fi/v2e534i2bmq0l9obmzwhb/WW13-Lab-7-Quantum-Adder-Toffoli-gate.pdf?rlkey=2jcdlqi2aptdr8wrd4qcy8i3y&dl=0)

### Schedule:

| Date  | - |
| ------------- | ------------- |
| 2/17   | HW 1 Due |
| 2/24   | HW 2 Due  |
| 3/3  | Lab 3 Due  |
| 3/10 | Lab 4 Due |  
| 3/17 |Lab 5 Due |
| 3/21  |650 Projects - 1st draft of code |
| 3/24  |Lab 6 Due|
| 3/25  |Midterm - ILC-S140 - 7-9PM |
| 3/27 | (midterm make-up)  Marston 220 7-9PM|
| 3/31  |Lab 7 Due |
| 4/7  |Lab 8 Due|



### Supporting Materials:
#### Quantum Optics:
  * Ivan H. Deutsch’s Notes - http://info.phys.unm.edu/~ideutsch/Classes/Phys566F21/
  * Mark Fox - [Quantum Optics: An Introduction](https://global.oup.com/academic/product/quantum-optics-9780198566731?cc=gb&lang=en&)

#### Quantum Optics & Atomic Physics:
  * Daniel Steck’s Notes - https://atomoptics.uoregon.edu/~dsteck/teaching/quantum-optics/

#### Quantum Computation:
* Thomas Wong’s Textbook: [order hard copy (~15$)](https://www.amazon.com/Introduction-Classical-Quantum-Computing-Thomas-dp-B09QP2MYYM/dp/B09QP2MYYM/) [download pdf](http://www.thomaswong.net/introduction-to-classical-and-quantum-computing-1e4p.pdf)

* IBM’s Qiskit Textbook - https://qiskit.org/textbook-beta

* Scott Aaronson - https://www.scottaaronson.com/qclec.pdf

* John Preskill - http://theory.caltech.edu/~preskill/ph219/chap6_20_6A.pdf

#### Mike & Ike:
  * [Quantum Computation and Quantum Information](https://www.cambridge.org/highereducation/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE#overview) by: Michael A. Nielsen & Isaac L. Chuang


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
