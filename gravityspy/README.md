### Welcome to `gw_learn starter-pack`, a  GW data analysis tutorial

For questions related to the material, please contact Melissa Lopez (m.lopez@uu.nl)

**Pre-requisites**: (Jupyter, conda)

**Instructions before running** For this tutorial is _highly_ recommended to install a new conda environment. `environment.yaml` file contains all the specifications. You can install the new environment simply by running `conda env create -f environment.yml -gravityspy_env`. Once this is done you can add your environment as a kernel to Jupyter running `python -m ipykernel install --name gravityspy_env`.

To run `Gravity Spy` please, clone my forked repository:

```
git clone git@github.com:MelissaLP/GravitySpy.git
```

Take not where this repository is as it will be used in the tutorials.

- Tutorial 1: in this tutorial we learn to characterize noise transient burst noise from LIGO detectors using `Gravity Spy`, a glitch classification tool.
  
- Tutorial 2: in this tutorial we simulate our own glitch using `gengli`, a generative AI algorithm to simulate Blip glitches, and then we characterize it with `Gravity Spy`.