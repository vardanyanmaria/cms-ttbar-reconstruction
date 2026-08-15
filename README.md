This repository contains code developed as part of my undergraduate research with the CMS experiment at CERN, focusing on the reconstruction and analysis of top quark pair events.

The analysis uses CERN ROOT and PyROOT to process CMS datasets, apply event selection criteria, identify leptons and jets, perform b-tagging, reconstruct hadronically and leptonically decaying top quarks, and study reconstructed mass distributions. A neutrino reconstruction solver is used to estimate neutrino kinematics and improve leptonic top quark reconstruction.

The neutrino reconstruction component is based on the analytic neutrino solver (https://github.com/arangb/analytic-nu).


Repository Structure:

Most of the analysis notebooks are contained in the notebooks folder.

notebooks/polished
This folder contains the final, cleaned, and usable versions of the analysis code. These are the recommended notebooks to use when running the completed analysis.

notebooks/july-aug
This folder contains more recent work from July–August. The notebooks in this folder are similar to each other and represent the development and testing of the analysis during this period.

notebooks/archive
This folder contains older attempts and useful code from earlier stages of development. These files are kept for reference and may contain approaches that were useful during development but are not necessarily part of the final workflow.

Some of the older notebooks have inconsistent or unclear naming conventions. The following naming conventions can help identify their purpose:
Files containing 2dplots, all plots, or probplot are related to generating the 2D probability/mass distribution plots.
Files containing ttbar, 3jets, 4jets, or similar names generally contain the code for testing and reconstructing different jet permutations.
Files containing bigfile indicate that the code is being run on the larger ROOT dataset containing approximately 200,000 events, rather than the smaller test dataset.
plots
The plots folder contains plots produced directly from the analysis notebooks. These include the reconstructed mass and probability distributions generated during the analysis.

Code and Environment
The analysis code is stored in Jupyter notebooks (.ipynb). I use Jupyter notebooks because this was the most reliable way for me to run CERN ROOT and PyROOT properly during development.
Although the code is stored in notebooks, it is normal Python code using standard Python syntax together with ROOT/PyROOT. The notebooks are run locally on a laptop with CERN ROOT installed.
The notebooks can be opened and executed using Jupyter Notebook/JupyterLab in a local environment where ROOT and the required Python packages are installed.

Analysis
The analysis workflow includes:
CMS ROOT dataset processing
Event selection
Lepton and jet reconstruction
b-tagging
Neutrino reconstruction
Jet permutation studies
Hadronic and leptonic top quark reconstruction
Reconstructed W and top quark mass distributions
2D probability/mass distribution studies

The goal of this project is to develop a complete workflow for reconstructing top quark pair events and studying the performance of different reconstruction techniques using CMS collision data.
This work is part of my undergraduate research in experimental particle physics.

