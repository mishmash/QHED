# QuantumHallED

A Julia code for performing exact diagonalization of quantum Hall systems, i.e., interacting electrons moving in two dimensions in the presence of strong perpendicular magnetic field. Currently the code supports only the spherical geometry, as introduced in the classic paper by Haldane \[[PRL **51**, 605 (1983)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.51.605)\].

Included are a few [notebooks](https://github.com/mishmash/QuantumHallED/tree/master/notebooks) demonstrating usage:
* [sphere-ED.ipynb](https://github.com/mishmash/QuantumHallED/blob/master/notebooks/sphere-ED.ipynb): various examples of basic usage.
* [Rezayi-Read_sphere-CFL.ipynb](https://github.com/mishmash/QuantumHallED/blob/master/notebooks/Rezayi-Read_sphere-CFL.ipynb): calculate energy spectra and (density-density) pair correlation function for the compressible composite Fermi liquid state realized for Coulomb interactions in the half-filled lowest Landau level \[see [Rezayi and Read, PRL **72**, 900 (1994)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.72.900)\].
* [Li-Haldane_entanglement-spectrum.ipynb](https://github.com/mishmash/QuantumHallED/blob/master/notebooks/Li-Haldane_entanglement-spectrum.ipynb): calculate (orbital partition) entanglement spectra for the Coulomb interaction projected into the first excited ("second") Landau level, believed to realize the Moore-Read Pfaffian state \[see [Li and Haldane, PRL **101**, 010504 (2008)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.101.010504)\].
