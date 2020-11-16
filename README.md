Eccentricity reduction
----------------------

Python script based on method described in Ramos-Buades et al. Phys. Rev. D 99,
023003 (2019) to reduce eccentricity in compact binary simulations.


## Usage

Either use as a script from the command line

```
./EccRed.py --tmin X --tmax X --input-parfile "input_parameter_file" \
            --output-parfile "output_parameter_file" "output_glob"
```

or a Python module

```
python
>>> import EccRed
>>> EccRed.ComputeCorrections("output_glob", MinTime=X, MaxTime=Y)
```
Please cite our paper if you found this script useful.

Authors: Sarah Habib, Antoni Ramos-Buades, Eliu A. Huerta, Sascha Husa, Roland
         Haas,  Zachariah Etienne

License: NCSA
Copyright: (c) 2020 The Board of Trustees of the University of Illinois
