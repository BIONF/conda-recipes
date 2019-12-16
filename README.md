# Conda recipes
Building conda package

```
conda-build recipes/<tool_name>
```

Upload package into anaconda cloud
```
anaconda upload /path/to/<tool>-<version>.tar.bz2
```

Install tool within a conda env
```
conda install -c <conda.org account name> <tool name>
```

Alternatively, you can build a package file for a tool, then create your own channel and install your tool from there.
```
mkdir my_channel
cp /path/to/<tool>-<version>.tar.bz2 my_channel
conda index my_channel
```
Then, modify `~/.condarc` file to add `my_channel` 
```
channels:
  - file:/path/to/my_channel/
  - conda.org_account_name
  - defaults
```
After that, you can easily install your tool with the command
```
conda install <tool name>
```

# Current tools that have recipes
1. [HaMStR](https://github.com/BIONF/HaMStR)
2. [FAS](https://github.com/BIONF/FAS)
