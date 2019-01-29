# Introduction to Python

This repository contains a basic introduction to Python programming aimed at a non-technical audience.

It was originally created for the “[Introduction to Python](https://senereko.ceres.rub.de/en/hnr-workshop-2015/papers-workshops/introduction-python/)” session at the [Historical Network Research workshop 2015](https://senereko.ceres.rub.de/en/hnr-workshop-2015/).

## Prerequisites

The easiest way to play with the notebooks is online through the service binder. It allows you to run all the code without installing anything, but your changes will not be saved.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/frederik-elwert/HNRWS2015-Intro-Python/master)

Alternatively, you need to install Python. There are two versions of Python: Version 2, which is older, but still used, and the newer Version 3. This introduction uses Python 3.

The easiest way to get Python with all the additional modules that we will use is the Anaconda installer.

1. Go to <https://www.anaconda.com/download/>.
2. Select the “Download” button for the Python 3 version (currently 3.7).
3. If you run into issues, consult the [installation guide](http://docs.anaconda.com/anaconda/install/) for your operating system.

## Running Python

We will use the “Juptyer Notebook” to write Python code. It allows you to run snippets of Python in a web browser and immediately see the results.

### MacOS and Windows

There is a utility called “Anaconda Navigator.” Open it through the application menu and select “Jupyter Notebook” from the window.

### MacOS and Linux

Open a Terminal window and type:

    conda activate
    jupyter notebook

If you want to store your notebooks in a custom directory, then you can change into that directory first:

    cd ~/Documents/MyNotebooks
    jupyter notebook

## Using this repository

This repository will contain the examples from the session. In order to run them locally, follow these steps:

1. Click the “Clone or download” button and select “Download ZIP.”
2. Unpack the downloaded ZIP file.
3. In the Jupyter Notebook, navigate to the files’ location and start the individual sessions.
