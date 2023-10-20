[![DOI](https://zenodo.org/badge/{32358151}.svg)](https://zenodo.org/badge/latestdoi/{32358151})
# Introduction
This notebook was used to create Figure 1 of the 'Do You Catch My Drift' short paper submission to the 2023 K-CAP conference (doi: https://doi.org/10.1145/3587259.3627555). While properly commented, the project remains a work in progress, meaning that some redundancies and inefficiencies are still present within the notebook. However, all code necessary to recreate a figure showing the implicit structure of the used embeddings is present. Note that the used t-SNE implementation is stochastic, meaning that each time the notebook is run, the resulting visualisation will slightly differ. This could be solved by setting the seed, but this has not been implemented yet.

## Running instructions
- Open a terminal and navigate to the directory in which this notebook is stored.
- Ensure you have a working Latex installing (run `tex --version`). If not installed, the labels and titles within the figure will not be rendered properly.
- (optional) Initialise a new python environment and activate this environment.
- Run `pip install -r requirements.txt`
- Run `jupyter-notebook`

Note 1: This notebook has been tested on python version 3.10.4

Note 2: The pickled files were pickled using protocol version 4.
