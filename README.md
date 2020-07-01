# Getting Started with Kodexa in Python

Collection of notebooks to interactively demonstrate the fundamentals of Kodexa and cool ways to use the platform.


## Run on Binder

These notebooks are hosted on Binder and can be accessed & run by clicking the Binder badge below.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kodexa-labs/get-started-with-python/master)


## Run locally

If you'd like to run these notebooks locally, ensure you have Anaconda 3 or greater installed, then run:

    conda env create -f environment.yml --force

Activate the demo conda environment with the command:

    conda activate kodexa_python_quickstart

Then, install ipykernel in the environment:

    conda install ipykernel

Finally, add the environment to the kernels:

    python -m ipykernel install --user --name kodexa_python_quickstart --display-name "kodexa_python_quickstart"

You can now deactivate the conda environment and launch the notebooks:

    conda deactivate

    jupyter lab

Select the "kodexa_python_quickstart" kernel in the notebook when executing the example code.



## Overview

These notebooks will walk you through the concepts of Kodexa and demonstrate how these concepts can be combinded to build solutions for your own applications.  The topics have divided into three sections, progressing from basic Kodexa components to real-world examples.

In order to run these notebooks, you'll need to have a platform account with a valid access token.

### 1. Getting Started
Start here if you're new to Kodexa.  Major topics covered:
* Overview of the structure of various features of a Kodexa document
* Connecting data to pipelines
* Parsing documents
* Tagging documents
* Using data sinks and stores
* Extracting data to stores
* Saving documents to files

### 2. Examples by Source Type
These notebooks provide working examples of parsing, tagging, and extracting data from several common file types (Excel, HTML, PDF, and Text)

### 3. Advanced Examples
These notebooks illustrate more complex examples and can be used as springboards for your own applications.
A few of the topics covered:
* Processing bank statements
* Summarizing the news (using online sources)