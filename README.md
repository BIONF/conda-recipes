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
