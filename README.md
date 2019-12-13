# Conda recipes
Building conda package

```
conda-build recipes/<tool_name>
```

Upload package into anaconda cloud
```
anaconda upload path_to_<tool>-<version>.tar.bz2
```

Install tool within a conda env
```
conda install -c <conda.org account name> <tool name>
```

# Current tools that have recipes
1. [HaMStR](https://github.com/BIONF/HaMStR)
2. [FAS](https://github.com/BIONF/FAS)
