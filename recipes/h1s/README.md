# Conda recipe for h1s (HaMStR-oneSeq)
Building conda package

```
conda-build conda_recipe
```

Upload package into anaconda cloud
```
anaconda upload path_to_h1s-version.tar.bz2
```

Install h1s within a conda env
```
conda install -c BIONF h1s
```
*Note: change `BIONF` to channel name that hosts h1s conda package*
