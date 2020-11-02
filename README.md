[![DOI](https://zenodo.org/badge/DOI/10.1063/1.5142084.svg)](https://doi.org/10.1063/1.5142084)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/relativistic_mirrors/master?urlpath=lab/tree/data_analysis.ipynb)

# Recoil Effects on Reflection from Relativistic Mirrors in Laser Plasmas

This repository contains the supplemental material for the work entitled "*Recoil Effects on Reflection from Relativistic Mirrors in Laser Plasmas*" that has been published in **Physics of Plasmas** (https://doi.org/10.1063/1.5142084).

The supplemental material consists of the raw data that has been computed by the **[EPOCH](https://cfsa-pmw.warwick.ac.uk/EPOCH)** (v4.17.3) particle-in-cell code (https://doi.org/10.1088/0741-3335/57/11/113001) and the Jupyter notebook with the set of commands that have been used for developing the analytical model and generating the figures.

The code is written in Python 3 programming language and relies on several Python packages: [numpy](https://github.com/numpy/numpy), [scipy](https://github.com/scipy/scipy), [matplotlib](https://github.com/matplotlib/matplotlib), [sympy](https://github.com/sympy/sympy), and [sdf](https://github.com/keithbennett/SDF).

### How to obtain the data:

Due to its size (480.3 MB), the raw data used in this work is stored on **Zenodo** (https://zenodo.org/record/3707924#.XmpGHag2pPY). You may download them as a .zip archive.

### How to obtain the notebook:

The notebook `data_analysis.ipynb` is stored in this GitHub repository. You may either download the whole repository as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/numerical_methods.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebook:

If you have downloaded the notebook and the data and have all the requirements installed on your computer, you may launch the notebook locally.

Alternatively, if you do not have installed all the requirements, you may launch the notebooks on-line using
* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/relativistic_mirrors/blob/master/data_analysis.ipynb
* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/relativistic_mirrors/master?urlpath=lab/tree/data_analysis.ipynb

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
