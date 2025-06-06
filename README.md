# spatialdata-learning
GitHub Repository for the hands-on SpatialData learning session at the MannLabs Group Retreat 2025


We will learn

- about spatialdata and its basic underlying data structures
- about the transformation of elements between coordinate systems 
- how we can interactively explore our data 
- how we can interface with different downstream packages
- troubleshooting


## Google Colab

This tutorial is also available in a [Google Colab Cloud Environment](https://colab.research.google.com/github/lucas-diedrich/spatialdata-learning/blob/main/notebooks/scdvp.ipynb)


## Installation 

1. Using the command line, go into your favorite directory (`cd /path/to/my/favorite/directory`)

2. Clone this repository 

```shell 
git clone https://github.com/lucas-diedrich/spatialdata-learning.git
```

(or download it via `Code > Download ZIP`, and unzip it locally)

3. Go into the directory

```shell 
cd spatialdata-learning
```

4. Create a `conda`/`mamba` environment with snakemake based on the `environment.yaml` file and activate it

```shell 
mamba create -n spatialdata-env --file environment.yaml && mamba activate spatialdata-env

# OR conda env create -f environment.yaml && conda activate spatialdata-env
```


## Tutorial

See the notebook `notebooks/scdvp.ipynb` or [Google Colab Cloud Environment](https://colab.research.google.com/github/lucas-diedrich/spatialdata-learning/blob/main/notebooks/scdvp.ipynb)

## References

### About spatialdata

**SpatialData homepage + Documentation** [spatialdata.scverse.org](https://spatialdata.scverse.org/en/stable/)

**scPortrait homepage + Documentation** [MannLabs/scPortrait](https://mannlabs.github.io/scPortrait/)

**dvpio** [dvp-io.readthedocs](https://dvp-io.readthedocs.io/en/latest/)


**Publication** Marconato, L., Palla, G., Yamauchi, K.A. et al. SpatialData: an open and universal data framework for spatial omics. Nat Methods 22, 58–62 (2025). https://doi.org/10.1038/s41592-024-02212-x

### Data

**Rosenberger2023** Rosenberger, F. A. et al. Spatial single-cell mass spectrometry defines zonation of the hepatocyte proteome. Nat Methods 20, 1530–1536 (2023).
