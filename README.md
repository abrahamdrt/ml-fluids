# ml-fluids
# Machine Learning in Fluid Dynamics: Cylinder Wake Analysis

**Current Status: Initial Data & ML Baseline Established** This repository contains my initial setup to prove our OpenFOAM cylinder wake data can be successfully piped into a machine learning workflow. I've uploaded this Jupyter Notebook to share the baseline feature extraction and classification methods I tested, ensuring the data is clean and ready for us to use.

### What's in this Notebook:
* **Feature Extraction:** Used linear SVD/POD to compress the spatial grid, and ran a quick Dynamic Mode Decomposition (DMD) test to isolate the Strouhal shedding frequency.
* **Baseline Models:** Trained an SVM and Random Forest on the POD features.
* **Deep Learning:** Ran a quick proof-of-concept PyTorch Neural Network directly on the raw grid.
