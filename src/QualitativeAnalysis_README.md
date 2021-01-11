The `QualitativeAnalysis.ipynb` notebook must be run with the `QualitativeAnalysis_Environment.yml` Anaconda environment. 

Follow the instructions below and consult the [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) section in the conda docs for more details. There is also a nice conda cheetsheet [here](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).

## Step 0: Open your Anaconda terminal
On Mac, this should be as simple as opening `terminal` (or I use [`iterm2`](https://iterm2.com/)).

On Windows, open the `Anaconda Powershell Prompt`.

## Step 1: create an environment from the environment.yml file

```
> conda env create -f QualitativeAnalysis_Environment.yml
```

Optionally, if you'd like to list the active conda environments on your system and verify that the `qualitativeanalysis` environment was created:

```
> conda env list
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

Now you can type in `jupyter notebook` and find `QualitativeAnalysis.ipynb`. It's easiest to do this from the root dir (e.g., `\accessibility-literature-survey\` or the src directory `\accessibility-literature-survey\src`).

```
(qualitativeanalysis)$ jupyter notebook
```

In Jupyter Notebook environment, navigate to the `QualitativeAnalysis.ipynb` file and open it.
