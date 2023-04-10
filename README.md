# windturbineSim

<p align="center"><a href="http://www.labcontrol.xyz/dokuwiki" target="_blank" rel="noopener"><img src="images/logo.png"></a></p>

# [Labcontrol, Brazil](http://www.labcontrol.xyz/dokuwiki)

[**Labcontrol**](http://www.labcontrol.xyz/dokuwiki)  is a research laboratory located at Universidade Tecnológica Federal do Paraná (UTFPR), Brazil. UTFPR is a Brazilian public university located in the Paraná state, Brazil. [**Labcontrol**](http://www.labcontrol.xyz/dokuwiki)  develops research on Control Systems and Automation. The Scientific Director of Labcontrol is [Prof. Dr. Alessandro N. Vargas](http://www.anvargas.com). The projects hosted in [**Labcontrol**](http://www.labcontrol.xyz/dokuwiki)  are [described in this link (click here).](http://www.anvargas.com/blog)

About
============

This page provides information about the project developed at 
LISTI, National School of Applied Sciences, Ibn Zohr University, and at Labcontrol called ["Integral-backstepping sliding-mode control for maximizing the power production of wind turbines."](http://www.anvargas.com/blog/studying.html)  Simulations were performed in a model of wind turbines, and the data contained in this Github repository were collected from those simulations. 

[![DOI](https://zenodo.org/badge/330236633.svg)](https://zenodo.org/badge/latestdoi/330236633)

**Please check more details about this project in the page detailing the ["Integral-backstepping sliding-mode control for maximizing the power production of wind turbines."](http://www.anvargas.com/blog/studying.html)**

For more details about the simulation data, as long as the corresponding academic publications, please visit [the project page](http://www.anvargas.com/blog).


Installation
============

1. Extract the ZIP file (or clone the git repository) in your computer.
2. Add the folder `data/` to your path in MATLAB/Octave: e.g. 
    - using the "Set Path" dialog in MATLAB, or 
    - by running the `addpath` function from your command window or `startup` script.

Make sure that you are running Matlab 2017a (or a newer version). Older versions may work, but it is uncertain.

Usage
=====

Typical usage of data consists of running `load xxx-maindata.mat` in your MATLAB. Replace `xxx-maindata.mat` by the correct name. The load command will import the data to your Matlab space.

MATLAB
------
  1. Run `load xxx-maindata.mat`.

More information
================

* For more information about the data, visit the author's page: [Prof. Alessandro N. Vargas](http://www.anvargas.com). You are welcome to help improving the code.
* You are free to use the data in your research. If you do so, please contact the author [Prof. Alessandro N. Vargas](http://www.anvargas.com) 
and let him know about your project. Depending on your research area, the author can help you interpret the data according to your application. 
The author works in cooperation with the team members of LISTI, National School of Applied Sciences, Ibn Zohr University, and all the members will do their best to help you.

[![DOI](https://zenodo.org/badge/330236633.svg)](https://zenodo.org/badge/latestdoi/330236633)

Citation
------
How to cite the data of this repository:

```
@misc{vargasGithub2023,
    author       = {A. N. Vargas},
    title        = {Data for modeling and simulation of wind turbines},
    month        = {Apr},
    year         = 2023,
    doi          = {10.5281/zenodo.4445334},
    version      = {1.0.1},
    publisher    = {Zenodo},
    url          = {https://zenodo.org/badge/latestdoi/330236633}
};
```



