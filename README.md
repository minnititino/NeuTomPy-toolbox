# NeuTomPy toolbox
![NeuTomPy logo](https://github.com/dmici/NeuTomPy-toolbox/blob/master/img/logo_neutompy.png)
**NeuTomPy toolbox** is a Python package for tomographic data processing and reconstruction.
Such toolbox includes pre-processing algorithms, artifacts removal and a wide range of iterative
reconstruction methods as well as the Filtered Back Projection algorithm.
The NeuTomPy toolbox was conceived primarily for Neutron Tomography and developed to support
the need of users and researchers to compare state-of-the-art reconstruction methods and choose the optimal data-processing workflow for their data.

# Features
* Readers and writers for TIFF and FITS files and stack of images
* Data normalization with dose correction, correction of the rotation axis tilt, ring-filters, outlier removals
* A wide range of reconstruction algorithms powered by [ASTRA toolbox](https://www.astra-toolbox.com/): FBP, SIRT, SART, ART, CGLS, NN-FBP, MR-FBP
* Image quality assessment with several metrics

# Installation

NeuTomPy toolbox supports **Linux** and **Windows** 64-bit operating system.

First of all install a [conda](https://www.anaconda.com/download/) python environment, with  **Python >=3.4**. 

It is required to install some dependencies, hence run the following inside a conda environment:
```  console
$ conda install -c simpleitk simpleitk
$ conda install -c astra-toolbox astra-toolbox
$ conda install -c conda-forge numexpr matplotlib astropy tifffile opencv scikit-image read-roi tqdm pywavelets
``` 

Then install NeuTomPy toolbox:

``` 
pip install neutompy
``` 

# Documentation
Complete documentation can be found on Read the Docs: <https://neutompy-toolbox.readthedocs.io>.

Tutorials and code examples of typical usage can be found in the folder [examples](https://github.com/dmici/NeuTomPy-toolbox/blob/master/examples).


# Contact
If you want to contact us for any reasons, please send an email to: neutompy@gmail.com


License
=======

The project is licensed under the [GPLv3](https://github.com/dmici/NeuTomPy-toolbox/blob/master/LICENSE) license.
