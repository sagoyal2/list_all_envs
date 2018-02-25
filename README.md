# list_all_envs
## About
A tool for printing a list of enviornments and their packages

It is possible to produce a list of enviornments in Python by 
```Python
conda env list
```
however finding which packages are available within the enviornment can only be discovered once the user activates the enviornment by
```Python
conda list
```

This command is useful as it prints the list of the all Python enviornments and thier packages without having to individual activate all of them
```Python
conda list-all-envs
```

## How to use:
1. Download / Clone repo
2. Excute `Python python setup.py`
3. From now on, you can run conda list-all-envs
