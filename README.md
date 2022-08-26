# Mass-Spectrometry-Chemical-Formula-Assigner
Script to perform various mass spectrometry-related routines including prediction of possible formulae from accurate masses and simulated spectrum generation

# Overview
Assignment of formulae to peaks of a given mass-to-charge (m/z) ratio is integral to many workflows in mass spectrometry and is often conducted using vendor-specific software. This script offers an alternative, python-based option for prediction of formulae for given m/z values, as well as an implementation of the brainpy algorithm for prediction of isotope distributions in simulated mass spectra (brainpy docs http://mobiusklein.github.io/brainpy).

# Dependencies
This script was written using the following packages and respective version numbers: matplotlib 3.2.2, seaborn 0.10.1, numpy 1.22.4, re 2.2.1, pandas 1.2.1, and brain-isotopic-distribution 1.5.9 in a python 3.8.3 environment.

# Accepted limitations
This script has been provided as a useful tool and, whilst the base functionality works as intended, has not been extensively tested. It is also noted that there are some minor discrepancies in exact masses of isotopes between the data table constructed from the mendeleev library (used for formula assignment) and the data used by the brainpy library (for spectrum simulation). 
