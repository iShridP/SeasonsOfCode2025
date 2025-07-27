# SeasonsOfCode2025
Assignments and Report Submissions of Seasons Of Code 2025 - Shridhar Patil

These Assignments/Reports contain concepts and theory I learnt about introductory Quantum Computing. This started with concepts about the mathematical Linear Algebra required for Quantum Mechanics such as inner/outer products, Quantum Operators, state vectors in Hilbert spaces and their Tensor products. Also studied observables and the Quantum measurement formats (Projective/POVM measurements), applications of these properties such as Quantum state teleportation and superdense coding, along with a study of Bell's theorem. 

In the second week I started with Qiskit to implement Superdense coding, a method to send a pair of classical bit information by physically sending only one Quantum qubit. This required setting up a $\vert \beta_{00} \rangle$ Bell state and implementing the superdense coding circuit. This circuit was ran both on the local ideal simulator and real-hardware on IBM Quantum computers to visualise the effects of noise. In the end we also created a circuit to transport sentences and word messages through superdense coding, highlighting an important usage of Quantum Computing for future applications. 

In the third week I studied an important Quantum algorithm, Grover's Algorithm, which is useful for unstructured search of a *key* element given a black box quantum oracle function. We implemented the Oracle and Grover Diffuser circuit for various applications of the algorithm, notably for solving a 3-SAT Boolean problem. We demonstrated how the number of iterations of the oracle-diffuser function can affect the measurement probabilities and how to find the optimal number of iterations.

I later studied the Quantum Fourier Transform circuit and implemented it for functions like $\sin(2x)$ and $\sin(8x)$, giving proper justifications for the results obtained. Some pros and cons of Amplitude encoding and other better implementations like Rotation encoding were studied. With the help of QFT, I implemented a circuit for phase estimation for the identification of the eigenvalue of a given quantum operator. Finally I read about and implemented a form of Shor’s Algorithm for the factorisation of numbers. 

The final assignment dealt with the chemistry simulation applications of Quantum computing through which I learnt about Quantum Error Correction (QEC) by implementing a simple 3-Qubit-repetition QEC code. By formulating the Hamiltonian of a simple $H_2$ molecule I found the ground state energy of the molecule with the help of VQE method and this QEC implementation. 

All Python notebooks and written assignments are added in the repository.
