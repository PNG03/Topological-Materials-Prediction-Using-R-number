# Topological-Materials-Prediction-Using-R-number

This repository contains the code and data underlying the machine learning part of the following paper: **"A Machine Learning-Based Classification Approach for Novel Topological Materials"** which was presented at the $2^{nd}$ International Conference on Advanced Materials for Green Chemistry and Sustainable Environment (AMGSE-2025).

If you find this code useful, please cite the above paper.

Data in this repository is taken from multiple sources:
1) The research paper, "Topogivity: A Machine-Learned Chemical Rule for Discovering Topological Materials" ([https://pubs.acs.org/doi/full/10.1021/acs.nanolett.2c03307](https://pubs.acs.org/doi/full/10.1021/acs.nanolett.2c03307)). The original source of the data used in the Topogivity paper is the Topological Materials Arsenal ([https://ccmp.nju.edu.cn/](https://ccmp.nju.edu.cn/)), paper "Comprehensive Search for Topological Materials Using Symmetry Indicators" ([https://www.nature.com/articles/s41586-019-0937-5]([https://www.nature.com/articles/s41586-019-0937-5])).
2) The research paper, "High-throughput screening of Weyl semimetals" ([https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.8.024201](https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.8.024201)).
3) LIterature search for Weyl and Dirac semimetals. The list of these can be found in the file `1 Datasets.ipynb`.
4) Topological Materials Database from the Topological Quantum Chemistry (TQC) website ([https://topologicalquantumchemistry.org/#/](https://topologicalquantumchemistry.org/#/)).

While using the data in this paper, please cite the appropriate papers. Please check the links given for citing other necessary papers as mentioned in the above given sources.

*************

**R-NUMBER VALUES:**

The R-number values of the elements and element pairs for each dataset are given in the directory `results\r_number_values`. They have been arranged alphabetically to facilitate easier access.

*************

**LIST OF ALL POTENTIAL TOPOLOGICAL MATERIALS:**

The list of all potential TMs predicted by our approach are given in the file `List of All Potential TMs`.

*************

CONTENTS IN THIS REPOSITORY:
1) _raw_data_: This folder contains the raw data extracted from the above mentioned sources.
2) _results_: This folder contains all the results from our algorithm. The text file `final_structure_screened_compiled_results.txt` has the compiled results after checking the band structures. R-number values from all datasets are also in this folder.
3) _space_datasets_: Has the Spaced dataset.
4) _1 Datasets.ipynb_: Jupyter code file for making datasets.
5) _2 ML Feature Engineering.ipynb_: Jupyter code file for feature engineering and calculating the R-number values.
6) _3 Final Model and Algo.ipynb_: Jupyter code file for training ML models and making predictions.
7) _Example R-Number Formula Calculation.pdf_: File explaining the calculation of probability from our devised formula using an example.
8) _LICENSE_
9) _List of All Potential TMs_: File for the list of all potential topological materials that are predicted by our approach.
10) _README.md_

Other files are the datasets made for running our algorithm.

The code files are to be run in the order specified by the numbers in their names.

*************
