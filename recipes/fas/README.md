# Conda recipe for FAS
Building conda package

```
conda-build conda_recipe
```

Upload package into anaconda cloud
```
anaconda upload path_to_fas-version.tar.bz2
```

Install hamstr within a conda env
```
conda install -c BIONF fas
```
*Note: change `BIONF` to channel name that hosts hamstr conda package*
