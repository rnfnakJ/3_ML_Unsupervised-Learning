# Unsupervised Learning & Dimensionality Reduction

## Pre-requisites
  * GT GitHub account
  * See [this document](README.md) on [jcha64/CS-7641_Unsupervised-Learning](https://github.gatech.edu/jcha64/CS-7641_Unsupervised-Learning/) repository
  * miniconda installed
  * Download refined data files (optionally you can find their original data files.)

### Install minicoda & make an environment to run this project.
  1. To run this project, you need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) based on your OS environment.
  2. After installing miniconda, you need to make a new environment via _**`conda env create --file environment.yaml`**_ command with [environment.yaml](environment.yaml) file.
  3. Then activate the named `AI` environment through _**`conda activate AI`**_ command.

### Processed data file
  1. You can find the revised file whcih was fined on [the previous work](https://github.gatech.edu/jcha64/CS-7641_Supervised-Learning/).
     * [default of credit card clients.xls](default&#32;of&#32;credit&#32;card&#32;clients.xls) => refined csv file ([credit.csv](credit.csv))
     * [wine.csv](wine.csv)

## Run various ML jobs

### Run a jupyter notebook session.
  1. Just simply run a jupyter lab session through _**`jupyter-lab`**_ command.
  2. You can run whole cells or one by one cell to follow up each ML method after loading each jupyter notebook file.
     * [1-Clusters and DR.ipynb](1-Clusters%20and%20DR.ipynb): to run clustering algorithims & dimensionality reduction.
     * [2-PCA-clustering.ipynb](2-PCA-clustering.ipynb): to run PCA clustering algorithims.
     * [3-ICA-clustering.ipynb](3-ICA-clustering.ipynb): to run ICA clustering algorithims.
     * [4-Randomized projection-clustering.ipynb](4-Randomized%20projection-clustering.ipynb): to run randomized projection clustering algorithims.
     * [5-Recursive feature elimination-clustering.ipynb](5-Recursive%20feature%20elimination-clustering.ipynb): to run recursive feature elimination clustering algorithims.
     * [6-DR-NN.ipynb](6-DR-NN.ipynb): to run dimensionality reduction with neural network algorithims.
     * [7-Cluster-NN.ipynb](7-Cluster-NN.ipynb): to run clustering with neural network algorithims.
