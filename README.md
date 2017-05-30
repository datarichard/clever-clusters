# clever-clusters
Determining psychiatric group from grey matter probability maps

This project explores clustering and classification methods of brain images with different diagnostic classes from the DSM-IV (healthy control, schizophrenia, bipolar disorder, depression). The brain images are grey matter probability maps generated from T1-weighted MRI images, preprocessed in SPM12 using John Ashburner's DARTEL pipeline for VBM, and rolled out into 1D-vectors.

We begin with some dimensionality reduction techniques using scikit-learn to explore 2D representations of the data and illustrate the problem clearly.
