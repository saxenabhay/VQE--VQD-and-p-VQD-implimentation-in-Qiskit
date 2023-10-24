The structure of this folder is pretty straight forward with names suggesting what respective files provide.
Following wiles are made in VSCode.

install first, preferably in seperate virtual enviroment:
qiskit_nature
Psi4 Library

Images folder contains image files used in markups in various jupyter notebook files.

pVQD
pvqd.ipynb contains the fedility vs time plot

VQD
vqd.ipynb contains basic vqd plot for 4 state with error convergence
vqd_molecule.ipynb contains a H2 molecule simulation of VQD along with various plots
vqd_concurrency.ipynb contains concurrency plots for 1st state of H2 atom at optimal distance

VQE
vqe.ipynb contains basic vqd plot for 4 state with error convergence, sd, purity, and concurrency plots
vqe_molecule.ipynb contains a H2 molecule simulation of VQD along with various plots
vqe_molecule_simulator.ipynb is same as vqe_molecule.ipynb except run locally than on cloud quantum computer
vqe_noisy.ipynb is basic noisy aer simulator to replicate cloud original quantum computer
vqe_runtime.ipynb is custom vqe program, data of which along with explanation is in the report for original quantum computer ibm quito
vqe_concurrency.ipynb contains concurrency plots for 1st state of H2 atom at optimal distance