[![DOI](https://zenodo.org/badge/DOI/10.1063/1.5142084.svg)](https://doi.org/10.1063/1.5142084)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/relativistic_mirrors/master?urlpath=lab/tree/relativistic_mirrors.ipynb)

# Recoil Effects on Reflection from Relativistic Mirrors in Laser Plasmas

This repository contains the supplemental material for the work entitled "*Recoil Effects on Reflection from Relativistic Mirrors in Laser Plasmas*" that has been published in AIP **Physics of Plasmas** (https://doi.org/10.1063/1.5142084).

The supplemental material consists of the raw data computed by the **[EPOCH](https://cfsa-pmw.warwick.ac.uk/EPOCH)** code (v4.17.3) and the **[Jupyter](https://jupyter.org/)** notebook with the set of commands that have been used for developing the analytical model and generating the figures.

The analysis is performed using Python 3 programming language and relies on several Python packages: [numpy](https://github.com/numpy/numpy), [scipy](https://github.com/scipy/scipy), [matplotlib](https://github.com/matplotlib/matplotlib), [sympy](https://github.com/sympy/sympy), and [sdf](https://github.com/keithbennett/SDF).

### How to obtain the data:

Due to its size (480.3 MB), the raw data used in this work is stored on **Zenodo**. You may download the data as a .zip archive on the following link: https://zenodo.org/record/3707924#.XmpGHag2pPY.

### How to obtain the notebook:

The notebook `relativistic_mirrors.ipynb` is stored in this GitHub repository. You may either download the whole repository as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/relativistic_mirrors.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebook:

If you have downloaded the notebook and the data and have all the requirements installed on your computer, you may launch the notebook locally. Alternatively, if you do not have installed all the requirements, you may launch the notebook on-line using
* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/relativistic_mirrors/blob/master/relativistic_mirrors.ipynb

* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/relativistic_mirrors/master?urlpath=lab/tree/relativistic_mirrors.ipynb

### How to cite:

Cite as: P. Valenta et al., *Phys. Plasmas* **27**, 032109 (2020).
```
@article{doi:10.1063/1.5142084,
        author = {Valenta,P.  and Esirkepov,T. Zh.  and Koga,J. K.  and Pirozhkov,A. S.  and Kando,M.  and Kawachi,T.  and Liu,Y.-K.  and Fang,P.  and Chen,P.  and Mu,J.  and Korn,G.  and Klimo,O.  and Bulanov,S. V. },
        title = {Recoil effects on reflection from relativistic mirrors in laser plasmas},
        journal = {Physics of Plasmas},
        volume = {27},
        number = {3},
        pages = {032109},
        year = {2020},
        doi = {10.1063/1.5142084},
        URL = {https://doi.org/10.1063/1.5142084}}
```

### Acknowledgements:

This work was supported by ERDF (CZ.02.1.01/0.0/0.0/15_003/0000449), MEYS (LM2015070), JSPS (JP19H00669) and EPSRC (EP/G054950/1, EP/G056803/1, EP/G055165/1, EP/M022463/1).

---

In case of any questions, please contact the corresponding author or submit an **[issue](https://github.com/valenpe7/relativistic_mirrors/issues)** to this GitHub project repository.
