##  Data Processing Tutorial for FieldLine OPM System
##### Made by Xan McPherson, 2026
Here, we will go through the steps required to process OPM data with references to relevant MNE-Python tutorials

#### The Steps:
1. Load and inspect raw data
2. Create and events Data Frame
3. Prprocess the raw data
4. Create Epochs and Evokeds for each event
5. Source localization

This tutorial is designed to give you a general framework for processing OPM-MEG data collected on the FieldLine HEDScan system. Extra steps can easily be added or modified to fit the individual experimental paradigm.

#### Dependencies
MNE Python 
Pandas
Freesurfer is not necessary for this tutorial, but subject anatomy can be found online as described
