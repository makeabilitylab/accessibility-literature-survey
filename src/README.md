

## Study 1 Qualitative Analysis Notebook
You can run the Study 1 qualitative analysis notebook (`Study1_QualitativeAnalysis.ipynb`) live in your web browser using [binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/54f371e7d1d16cf624e4606e5454072bed91fc58) or locally using the [Anaconda](https://www.anaconda.com/) environment.  

### Running the notebook using binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/14c718abe764770b20519780eca68a8370400ff2?filepath=src%2FStudy1_QualitativeAnalysis.ipynb)

[Binder](https://mybinder.org/) lets you run Git repos as interactive notebooks. Click [here to run `Study1_QualitativeAnalysis.ipynb` in binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/14c718abe764770b20519780eca68a8370400ff2?filepath=src%2FStudy1_QualitativeAnalysis.ipynb).

### Running the notebook locally using Anaconda 

Follow the instructions below and consult the [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) section in the conda docs for more details. There is also a nice conda cheetsheet [here](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).

#### Step 1: Open your Anaconda terminal and go to the src dir
On **Mac**, this should be as simple as opening `terminal` (or, for example, use [`iterm2`](https://iterm2.com/)—my preferred terminal program).

On **Windows**, open the `Anaconda Powershell Prompt`.

Make sure you are in the root directory of this project. For example, for me (on my Mac), this is:

```
> pwd
/Users/jonf/Git/accessibility-literature-survey
```

#### Step 2: create an environment from the environment.yml file

```
> conda env create -f environment.yml
```

Optionally, if you'd like to list the active conda environments on your system and verify that the `a11y-qual-analysis` environment was created:

```
> conda env list
```

#### Step 3: activate the environment

```
> conda activate a11y-qual-analysis
```

### Step 4: open jupyter notebook
Now you should see the command line prompt prefixed by the current environment: `(a11y-qual-analysis)`. So, your command prompt should look like the following or something similar:

```
(a11y-qual-analysis)$
```

Now you can type in `jupyter notebook` and find `Study1_QualitativeAnalysis.ipynb`. It's easiest to do this from the root dir (e.g., `\accessibility-literature-survey\` or the src directory `\accessibility-literature-survey\src`).

```
(a11y-qual-analysis)$ jupyter notebook
```

In Jupyter Notebook environment, navigate to the `Study1_QualitativeAnalysis.ipynb` file and open it.
