### Fluctuations of Energy-Relaxation Times in Superconducting Qubits
P. V. Klimov, J. Kelly, Z. Chen, M. Neeley, A. Megrant, B. Burkett, R. Barends, K. Arya, B. Chiaro, Yu Chen, A. Dunsworth, A. Fowler, B. Foxen, C. Gidney, M. Giustina, R. Graff, T. Huang, E. Jeffrey, Erik Lucero, J. Y. Mutus, O. Naaman, C. Neill, C. Quintana, P. Roushan, Daniel Sank, A. Vainsencher, J. Wenner, T. C. White, S. Boixo, R. Babbush, V. N. Smelyanskiy, H. Neven, John M. Martinis

[Phys Rev Letters 121, 090502 (2018)](https://storage.googleapis.com/gweb-research2023-media/pubtools/pdf/5dc59b7f00e2338d1888ab52df771a7cf72fd5b6.pdf)

[arXiv:1809.01043 (2018)](https://arxiv.org/pdf/1809.01043.pdf)

### Contents:
- Energy-relaxation time versus qubit frequency versus time data for 5 qubits
  - Each qubit's data is in a directory labelled `qA_B` and is packaged as three `.csv` files:
    - `freqs_GHz_mesh.csv` - Two-dimensional mesh of qubit operating frequencies, in GHz.
    - `times_min_mesh.csv` - Two-dimensional mesh of times over which each qubit was measured, in minutes.
    - `T1s_us_mesh.csv` - Two-dimensional mesh of energy-relaxation times (T1s) corresponding to the frequencies and times above.
- Script `data_visualizer.ipynb` for loading and visualizing the data corresponding to Supplementary Figure S1.
