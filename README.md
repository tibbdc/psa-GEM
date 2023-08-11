# psa-GEM: The genome-scale metabolic model of _Pseudomonas stutzeri_ A1501


#### Description

This repository contains the latest version of psa-GEM, genome-scale metabolic model of _Pseudomonas stutzeri_ A1501.


#### Model Keywords

**Utilisation:**  experimental data reconstruction; multi-omics integrative analysis;, _in silico_ strain design   
**Field:** metabolic-network reconstruction  
**Type of model:** reconstruction; curated     
**Omic source:** genomics; metabolomics   
**Taxonomy:**  _Pseudomonas stutzeri_   
**Metabolic system:** general metabolism  
**Tissue:**  
**Bioreactor:**    
**Cell type:**  
**Cell line:**  
**Strain:** A1501  
**Condition:** generic metabolism 


### Model Overview

|Taxonomy  | Reactions | Metabolites| Genes |
| ------------- |:-------------:|:-------------:|:-----:|
|_Pseudomonas stutzeri_ |  1420  | 1203 | 1108 |


### Installation

To create a stand-alone environment named psaGEM with Python 3 and all the required package versions (especially for cobrapy is also available), run the following code:

```shell
$ conda create -n psaGEM python=3
```
```shell
$ conda activate psaGEM
```
```shell
$ pip install ipykernel  
$ python -m ipykernel install --user --name psaGEM --display-name "psaGEM"  
$ pip install pandas
$ pip install cobra
```
  You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation. 


### Usage

#### 1.calculate growth rate.ipynb

#### 2.substrate utilization biolog.ipynb


### Contributing

Contributions are always welcome! Please read the [contributing guideline](.github/CONTRIBUTING.md) to get started.
