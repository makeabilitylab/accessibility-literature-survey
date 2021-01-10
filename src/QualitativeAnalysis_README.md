The `QualitativeAnalysis.ipynb` notebook must be run with the `QualitativeAnalysis_Environment.yml` Anaconda environment. 

Follow the instructions below and consult the [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) section in the conda docs for more details. There is also a nice conda cheetsheet [here](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).

## Step 1: create an environment from the environment.yml file

```
> conda env create -f QualitativeAnalysis_Environment.yml
```

## Step 2: activate the environment

```
> conda activate qualitativeanalysis
```

## Step 3: open jupyter notebook
Now you should see the command line prompt prefixed by the current environment: `(qualitativeanalysis)`. So, your command prompt should look like the following or something similar:

```
(qualitativeanalysis)$
```

Then type in the same directory as `QualitativeAnalysis.ipynb`:

```
(qualitativeanalysis)$ jupyter notebook
```

