# Variational Quantum Eigensolver (VQE) from scratch

A Variational Quantum Eigensolver (VQE for short), is a hybrid classical-quantum algorithm for finding eigenvalues of a matrix, first proposed in [[1]](#1). This notebook is a tutorial on how to build a VQE from scratch, and use it so find the lowest eigenvalue of a 4x4 matrix.  
(Sooner or later, I'll publish a blogpost explaining more in detail what is a VQE, I promise :pray:).

> **NOTE**: This notebook was originally created for the screening task of the [Quantum Open Source Foundation](https://qosf.org/) (QOSF) Mentorship Program (second batch, 2020). If you don't know already, QOSF is a fantastic project aiming to support and help with the development of open-source codes for the quantum computing community. For more information, great learning resources, and a list of supported projects, visit https://qosf.org/


<a id="1">[1]</a>
Peruzzo, A., McClean, J., Shadbolt, P. et al. [*A variational eigenvalue solver on a photonic quantum processor*](https://doi.org/10.1038/ncomms5213). Nat Commun 5, 4213 (2014).

---  

### Brief summary

The tutorial is in the form of a Jupyter Notebook.

First there is a more theoretical part discussing the main concepts of the algorithm, and subsequently its actual code implementation properly commented and explained (hope so 😅).

The quantum circuits are built using **[Qiskit](https://qiskit.org/)**. In addition, *Numpy* and *Scipy* are needed for the execution.

If you have any questions, doubts and suggestions, don't hesitate to contact me!  

Have fun! :smile:
