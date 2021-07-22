# A Systematic Review of Accessibility Papers
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/HEAD)

This repo contains the data and code for our CHI2021 accessibility literature survey paper entitled *["What Do We Mean by 'Accessibility Research'? A Systematic Review of Accessibility Papers in CHI and ASSETS from 1994 to 2019"](https://doi.org/10.1145/3411764.3445412)* by [Kelly Mack](https://kmack3.github.io/), Emma McDonnell, [Dhruv Jain](https://homes.cs.washington.edu/~djain/), [Lucy Lu Wang](https://www.llwang.net/), [Jon E. Froehlich](https://jonfroehlich.github.io/), and [Leah Findlater](https://www.hcde.washington.edu/findlater). You can find the repo to our follow-up Late-Breaking Work bibliometric analysis [here](https://github.com/makeabilitylab/accessibility-bibliometric-analysis).

Please cite this dataset as:

> Kelly Mack, Emma McDonnell, Dhruv Jain, Lucy Lu Wang, Jon E. Froehlich, and Leah Findlater. 2021. What Do We Mean by “Accessibility Research”? A Literature Survey of Accessibility Papers in CHI and ASSETS from 1994 to 2019. Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems. Association for Computing Machinery, New York, NY, USA, Article 371, 1–18. DOI:https://doi.org/10.1145/3411764.3445412

You can run the analysis notebooks live in your browser using [binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/HEAD) or run them locally using [Jupyter Notebook](https://jupyter.org/) and the [Anaconda](https://www.anaconda.com/) environment.

## Analyses and Datasets
The Mack paper presents analyses of two accessibility paper datasets drawn from CHI and ASSETS:

1. **Study 1**: A qualitative analysis of accessibility papers from 2010-2019 (N=506 papers).
2. **Study 2**: A larger programmatic analysis of the last 26-years of accessibility papers—since the founding of ASSETS (N=836 papers)

### Study 1
To analyze the 506 accessibility papers from 2010-2019 at CHI and ASSETS, we used an iterative process to develop and apply a codebook. See Sections 3.1.1 and 3.2.1 and Sections 4.1, 4.2, and 4.3 of the Mack et al. paper.

- **[Dataset1_QualitativeCodebook.docx](/datasets/Dataset1_QualitativeCodebook.docx)**: The codebook includes deductive codes based on our research questions, such as user communities of focus, technologies, and study methods as well as codes that were inductively added as we pursue our analysis. See Section 3.2.1 in the CHI'21 paper for details.

- **[Dataset1_QualitativelyCodedData_ASSETSandCHI_2010-2019.csv](/datasets/Dataset1_QualitativelyCodedData_ASSETSandCHI_2010-2019.csv)**: The results of our qualitative analysis using the above codebook

- **[Dataset1_TotalPaperCountsPerYear_ASSETSandCHI_2010-2019.csv](/datasets/Dataset1_TotalPaperCountsPerYear_ASSETSandCHI_2010-2019.csv)**: The total number of papers at ASSETS and CHI from 2010-2019.

- **[Study1_QualitativeAnalysis.ipynb](/src/Study1_QualitativeAnalysis.ipynb)**: The analysis scripts for Study 1. You can open up this notebook live in your browser using [binder](https://mybinder.org/v2/gh/makeabilitylab/accessibility-literature-survey/HEAD) or run it locally using Jupyter Notebook and Anaconda. See [src/README.md](/src).

### Study 2
For the second analysis, we built on the 506 papers above by adding all 285 ASSETS papers and 45 CHI accessibility papers that appeared in 1994-2009, for a total of 836 papers over the 26-year period. See Sections 3.1.2, 3.2.2, and 4.4 for details.

- **[Dataset2_KeywordMappings.csv](/datasets/Dataset2_KeywordMappings.csv)**: contains a list of the author keywords used in the papers in our quantitative dataset and the labels we manually assigned to them for our quantitative analysis (see section 4.4.2 of the paper).

- **[Dataset2_PaperMetadata_ASSETSandCHI_1994-2019.csv](/datasets/Dataset2_PaperMetadata_ASSETSandCHI_1994-2019.csv)**: contains the metadata of 836 accessibility papers from 1994-2019 used in our quantitative analysis.

- **[Dataset2_PaperMetadata_AllCHI.csv](/datasets/Dataset2_PaperMetadata_AllCHI.csv)**: contains the metadata of all CHI papers from ACM.

- **[Study2_QuantitativeAnalysis.ipynb](/src/Study2_QuantitativeAnalysis.ipynb)**: The analysis scripts for Study 2.
