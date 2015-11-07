## Hacking Structural Biology with Python and pandas
### PyCon Canada 2015, November 7th 2015

### Abstract

The dynamic motions of biomolecules like DNA, RNA, and proteins are integral to our understanding of drugs, disease, and human health. By performing large-scale supercomputer simulations, one can model the motion of proteins in ways impractical or impossible using traditional lab bench experiments.

While data science approaches are ubiquitous in the field of genomics, commonly dealing with massive genetic sequence and expression datasets, the application of ""big data"" methodology is infrequently used in the field of structural biology due to the high computational expense of running simulations. However, advances in high-performance computing are resulting in increased dataset sizes and data analysis is emerging as the primary bottleneck to scientific discovery.

In this talk, I present the use of Python and Pandas to accelerate analysis of time series data extracted from molecular dynamics trajectories. The application of this approach is directed at the study of the voltage-gated sodium channel, a protein found in human neurons that is responsible for propagating nerve impulses. Using a Jupyter notebook, I perform exploratory analysis on a large dataset of trajectories and arrive at a mechanistic model for the function of this protein. This model may then be used to quantify how genetic diseases and drugs might alter the function of the protein in subsequent research.

### Addendum

A mechanistic model of sodium permeation will be presented in a follow-up notebook. Note that the full dataset presented in "HackingStructBiology-ProductionData.ipynb" is not distributed in assets but the embedded plots in that notebook reflect the full dataset. The "HackingStructBiology.ipynb" version of this talk references a subset of production data in assets, so all cells of the notebook will run but the plots are much more sparse. Also note that the Github previews of each notebook do not render the protein viewer widget.

### Dependencies

* numpy (for some math)
* pandas (for data analysis)
* matplotlib (for plotting)
* openmm (for simulations)
* mdtraj (for simulation analysis)
* ipywidgets (for embedded protein viewer)
