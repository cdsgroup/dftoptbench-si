
Assessment of Density Functional Methods for Geometry Optimization of
Bimolecular Complexes
===

<p  align="center">
<br>
<a href="http://pubs.acs.org/doi/full/10.1021/acs.jctc.6b00797"><img src="https://img.shields.io/badge/DOI-%2010.1021%2Facs.jctc.6b00797-blue.svg"/></a>
<a href="https://mybinder.org/v2/gh/dsirianni/dftoptbench-si/master"><img src="https://mybinder.org/badge.svg"/></a>
<a href="mailto:sherrill@chemistry.gatech.edu"><img src="https://img.shields.io/badge/email-authors-yellowgreen.svg"/></a>
<a href="https://opensource.org/licenses/BSD-3-Clause"><img src="https://img.shields.io/badge/License-BSD%203--Clause-red.svg"/></a>
<br>
</p>

---

### Overview

The purpose of this repository is to make accessible the raw data associated
with the publication [citation]() for the interested reader, to supplement the
published [manuscript]() and [supplementary information]() (SI).  To this end,
we provide a self-contained environment within which to view, manipulate, and
interact with these raw and post-processed data in a highly interactive format
based on the Jupyter Notebook integrated development environment, in order to
increase the visibility and reproducibility of the work.  

Additionally, we provide discussion and executable code addressing the
point-set registration problem, implementing Algorithms 1 and 2 from the
[SI](), to illustrate the methods used in this work to assess the quality of
optimized geometries.  

### Getting Started

To run all of the included Jupyter notebooks using the cloud-based, Jupyter
Hub--hosted binder image, simply click on the pink badge above which reads
"launch binder".  A new tab will open containing a file browser, from which
each of the included notebooks can be launched and run over an Internet
connection.

**NOTE:** Launching the binder image the first time may take up to five
minutes, as several packages must be collected, linked, and installed in the
image before launch.

### Repository Organization

This repository contains Jupyter notebooks and compressed, binary data files.
For the raw data in CSV format, please refer to the publication's
[Supplementary Information](). Provided here are:

1. Jupyter notebooks for data analysis and visualization
    * `basics.ipynb`: Basic overview of Jupyter notebooks and the Pandas
python library
    * `analysis.ipynb`: Generates all relevant figures and tables from the
manuscript and supplementary information
2. `registration.ipynb`: Discusses the point-set registration problem, as well
as provides implementations of Algorithms 1 & 2 from the SI
3. Data Files
    * `pickles/A21_LRMSD-dCOM.pkl`: Contains all LRMSD and dCOM data and 
summary statistics for optimizations of A21 complexes
    * `pickles/HBC6-NBC7x_pes-scans.pkl`: Contains raw interaction energy 
scans for HBC6 and NBC7x complexes
    * `pickles/HBC6-NBC7x_pes-minima.pkl`: Contains interpolated minima of and 
summary statistics for interaction energy scans of HBC6 and NBC7x complexes
    * `example-geoms/`: Contains example XYZ files on which the code in 
`registration.ipynb` can be tested.

### Citing this Repository

All future work using the code, data, and/or tools contained herein should cite
the following:

1. [D. A. Sirianni, A. Alenaizan, T. M. Parker, D. L. Cheney, and C. D. Sherrill.
*J. Chem. Theory Comput.* **VV**, pp (yyyy)]()



