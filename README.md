# Cython_modules_cygno

A Cython implementation for some modules used in CYGNO Experiment

## Dependencies

+ Cython

## How to compile and use

To compile the cython library you execute this command:

```
python setup.py build_ext --inplace
```

 it will compile the C libraries so you could use in your code. After compilation you import the functions to your code with:

```
from cython_cygno import nred_cython
from cython_cygno import sim3d_cython
```

## Images

The time comparison between both processes:

+ For Noise_reductor:

![GitHub Logo](/img/nred.png)

+ For the 3D_simulation:

![GitHub Logo](/img/3d.png)

