# A Systematic Review of Accessibility Papers
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/HEAD)

This repo contains the data and code for our CHI2021 accessibility literature survey paper entitled *"What Do We Mean by 'Accessibility Research'? A Systematic Review of Accessibility Papers in CHI and ASSETS from 1994 to 2019"* by Kelly Mack, Emma McDonnell, Dhruv Jain, Lucy Lu Wang, [Jon E. Froehlich](https://jonfroehlich.github.io/), and [Leah Findlater](https://www.hcde.washington.edu/findlater).

You can run the analysis notebooks live in your browser using [binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/HEAD) or run them locally using [Jupyter Notebook](https://jupyter.org/) and the [Anaconda](https://www.anaconda.com/) environment.

## Analyses and Datasets
The Mack paper presents analyses of two accessibility paper datasets drawn from CHI and ASSETS:

1. **Study 1**: A qualitative analysis of accessibility papers from 2010-2019 (N=506 papers).
2. **Study 2**: A larger programmatic analysis of the last 26-years of accessibility papers—since the founding of ASSETS (N=836 papers)

### Study 1
To analyze the 506 accessibility papers from 2010-2019 at CHI and ASSETS, we used an iterative process to develop and apply a codebook. See Sections 3.1.1 and 3.2.1 and Sections 4.1, 4.2, and 4.3 of the Mack et al. paper.

- **[Dataset1_QualitativeCodebook.docx](/datasets/Dataset1_QualitativeCodebook.docx)**: The codebook includes deductive codes based on our research questions, such as user communities of focus, technologies, and study methods as well as codes that were inductively added as we pursue our analysis. See Section 3.2.1 in the CHI'21 paper for details.

- **[Dataset1_QualitativelyCodedData_ASSETSandCHI_2010-2019.csv](/datasets/Dataset1_QualitativelyCodedData_ASSETSandCHI_2010-2019.csv)**: The results of our qualitative analysis using the above codebook

- **[QualitativeAnalysis.ipynb](/src/QualitativeAnalysis.ipynb)**: The analysis scripts for Study 1. You can open up this notebook live in your browser using [binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/8427cee3d61113ed5305fdc9051fd2cca5b8841a?filepath=src%2FQualitativeAnalysis.ipynb) or run it locally using Jupyter Notebook and Anaconda. See [src/README.md](/src).

### Study 2 Datasets
For the second analysis, we built on the 506 papers above by adding all 285 ASSETS papers and 45 CHI accessibility papers that appeared in 1994-2009, for a total of 836 papers over the 26-year period. See Sections 3.1.2, 3.2.2, and 4.4 for details.

- **Dataset2_KeywordMappings.csv**: <Need a definition for this file>

- **Dataset2_PaperMetadata_ASSETSandCHI_1994-2019.csv**: <need a definition for this file>
