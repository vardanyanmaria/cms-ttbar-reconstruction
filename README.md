This repository contains code developed as part of my undergraduate research with the CMS experiment at CERN, focusing on the reconstruction and analysis of top quark pair events.

The analysis uses CERN ROOT and PyROOT to process CMS datasets, apply event selection criteria, identify leptons and jets, perform b-tagging, and reconstruct both hadronically and leptonically decaying top quarks. A neutrino reconstruction solver is used to estimate neutrino kinematics and improve leptonic top quark reconstruction.

The neutrino reconstruction component is based on the analytic neutrino solver: https://github.com/arangb/analytic-nu 

Repository structure:

“HEP-Tutorial” branch
This branch is based on the CMS HEP Tutorial:
https://github.com/handeaygenli/CMS-HEP-Tutorial 

The relevant portions of the tutorial were adapted from C++ into Python to create a workflow suitable for future CMS event reconstruction studies.

“ttbar-reconstruction” branch
This branch contains my analysis code built from the adapted Python framework. It processes CMS ROOT datasets and performs:
- Event selection
- Lepton and jet reconstruction
- b-tagging
- Neutrino reconstruction
- Hadronic and leptonic top quark reconstruction
- Mass distribution studies

The goal of this project is to develop a complete workflow for reconstructing top quark pair events and studying the performance of reconstruction techniques using CMS collision data.

This work is part of my undergraduate research in experimental particle physics.
