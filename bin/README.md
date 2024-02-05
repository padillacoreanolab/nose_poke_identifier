# Conda Environment Installation Commands

## SLEAP Environment with Pip from Conda
```
# SLEAP Environment
conda create -y -n nose_poke_env python=3.9

# Installing Jupyter Notebook
conda install -c conda-forge notebook --yes

# Installing Git Library to get root directory of repo
conda install -c conda-forge gitpython --yes

# To label inlines and other plots
conda install -c conda-forge seaborn --yes

# To look at h5 files
conda install -c conda-forge h5py --yes

# To read in excel files
conda install conda-forge::openpyxl --yes

```
