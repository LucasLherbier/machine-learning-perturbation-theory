# Machine Learning Perturbation Theory

This repository completes the report of my final-year project at [Ecole des Mines de Nancy](https://mines-nancy.univ-lorraine.fr/formation/ingenieur-civil-mines-icm/).

In science materials, solving quantum equations comes at a very high cost. The final goal of this project is to use and test three machine learning algorithms instead of solving Schrodinger equations in order to considerably reduce calculation time.

## Description of this repository

I recommend reading the report before reading the notebooks, as most explanations are not duplicated in the notebooks.
* **report**: explanation of the entire project 
* **data**: access to the project resources such as the pritimive cell data studied here
* **models**: presentation of the machine learning models. The Jupyter notebooks are divided in three parts :
  * the `MLPT_position.ipynb`: it creates the dataset whose features are the relative positions to an atom of reference.
  * the `MLPT_Distance.ipynb`: it creates the dataset whose features are the distances of the neighbors from an atom of reference. For each configuration, all the atoms in the primitive cell are atoms of reference.
  * the `MLPT_MachineLearning.ipynb`: it applies machine learning algorithms to the datasets.

