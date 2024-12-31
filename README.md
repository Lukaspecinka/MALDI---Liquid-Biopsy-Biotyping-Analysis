# MALDI liquid biopsy analysis
The presented R workflow has been developed for the analysis of data subsets obtained from MALDI MS data measurements, with subsequent analysis employing multivariate statistical methods and machine learning (ML) methods. The primary aim of these methods is to create predictive models that detect patterns from the mass spectra, facilitating the screening of disease, prediction of response to treatment, and prediction of disease relapse. 
ML methods employed in this study encompass decision trees (DTs), k-nearest neighbours (k-nn) and partial least squares-discriminant analysis (PLS-DA), artificial neural networks (ANNs), and random forests (RFs). 
## DATA
The demonstration of the proposed script is facilitated by data obtained from peripheral blood plasma analysis. The dataset includes: 200 raw mass spectra of 20 patients with multiple myeloma and 20 healthy donors. Data were collected using MALDI-7090™ MALDI TOF-TOF mass spectrometer (Shimadzu, Japan).
Download the data from [Zenodo](https://doi.org/10.5281/zenodo.14561887) and extract all files into directory, which we will refer to as the root data directory.
