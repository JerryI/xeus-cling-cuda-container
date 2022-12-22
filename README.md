# Xeus-Cling-Cuda-Container
The repository contains container recipes to build the entire stack of Xeus-Cling and Cling including cuda extension with just a few commands.

# General Information
This is a fork

# xtensor lib
You need to create an overlay with singularity like [this](https://docs.sylabs.io/guides/3.0/user-guide/persistent_overlays.html)
Then run inside the singularity shell
```
conda install -c conda-forge xtensor
```
