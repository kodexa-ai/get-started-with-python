# Getting Started with Kodexa in Python

Collection of notebooks to interactively demonstrate cool ways to use Kodexa.


## Run on Binder

These notebooks are hosted on Binder and can be accessed & run by clicking the Binder badge below.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kodexa-labs/get-started-with-python/master)


## Run locally

If you'd like to run these notebooks locally, ensure you have Anaconda 3 or greater installed, then run:

    conda env create -f environment.yml --force

Activate the demo conda environment with the command:

    conda activate kodexa_python_demos

Then, install ipykernel in the environment:

    conda install ipykernel

Finally, add the environment to the kernels:

    python -m ipykernel install --user --name kodexa_python_demos --display-name "kodexa_python_demos"

You can now deactivate the conda environment and launch the notebooks:

    conda deactivate

    jupyter lab

Select the kodexa_python_demos kernel to execute the notebooks.
