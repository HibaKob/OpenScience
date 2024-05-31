# Open Science — our attempt to follow best practices

## Table of Contents
* [Introduction](#introduction)
* [Our Contributions](#contributions)
* [Recommendations and Resources](#recomends)
* [Case Study](#case)
* [Additional Resources](#resources)
* [Contact Information](#contact)


## Introduction <a name="introduction"></a>
According to [Science.gov](https://open.science.gov/), "open science is the principle and practice of making research products and processes available to all, while respecting diverse cultures, maintaining security and privacy, and fostering collaborations, reproducibility, and equity."

In general, the main features of the concept of open science can be identified as being: `1)` accessible, `2)` reproducible, and `3)` inclusive, as shown in the schematic below adapted from [Ramachandran, et al.](https://doi.org/10.1029/2020EA001562).

<p align = "center">
<img alt="overview" src="/Resources/figures/OpenScience_Eco.png" width="80%" />

In this repository, we compile a list of guidelines and resources to aid researchers aiming to contribute to open science. These guidelines and resources include recommended practices for sharing datasets, software tools or code, experimental protocols, and research preprints or papers.

## Our Contributions <a name="contributions"></a>
In the [LejeuneLab](https://sites.bu.edu/lejeunelab/) at Boston University, we have generated, curated, and disseminated a number of datasets relevant to two main applications: 

`1)` machine learning methods in mechanics

`2)` high-throughput analysis methods for image-based data in cardiac tissue engineering

Our main goal is to provide benchmark datasets for both applications where the number of publicly available datasets is limited. Furthermore, with this endeavor, we aim to make data-driven problems in mechanics and in cardiac tissue engineering more accessible to the broad research community.

For the first application, we have compiled a list of [open-access mechanics datasets](https://elejeune11.github.io/) generated by our group and by others. In addition to the host link, we include links to the codes used to generate and implement the dataset by the developing group, as well as the manuscript describing the work in more details. Finally, we include a "recommended challenge" for most datasets as a starting point for novice users to start exploring the dataset.  

For the second application, we have published 3 datasets relevant to cardiac tissue engineering based on time-lapse microscopy images generated by our collaborators at Boston University and at the University of Michigan. We chose [Dryad](https://datadryad.org/stash) as the hosting site.

* [Engineered cardiac microbundle time-lapse microscopy image dataset](https://doi.org/10.5061/dryad.5x69p8d8g)

* [Strain gauge platforms: Time-lapse microscopy dataset of engineered cardiac microbundles](https://doi.org/10.5061/dryad.sqv9s4nbg) 

* [FibroTUG platforms: Time-lapse microscopy dataset of engineered cardiac microbundles](https://doi.org/10.5061/dryad.3r2280gqd)

Through this work, we have come across a number of useful resources that serve as a good starting point for anyone who is planning to make their work publicly accessible and likewise, contribute to open science. 


## Recommendations <a name="recomends"></a>
In general, it is advisable to consult [FAIR Guiding Principles](https://www.go-fair.org/fair-principles/), which are guidelines to optimize the `F`indability, `A`ccessibility, `I`nteroperability, and `R`euse of digital assets, for effective curation and dissemination of research products. 
As a rule of thumb, make sure that the online platform through which the work is shared can provide permanent links such as DOI-based links. In addition, it is important to choose permissive licenses for shared data and code to maximize the benefit other researchers will obtain from the published work.

### Recommendations for curating and disseminating datasets <a name="recomends_data"></a>
For sharing datasets in specific, we found it very useful to keep the following in mind when collecting and preparing the dataset for dissemination: 

1) Make sure to keep track of metadata. Include as much information as necessary that would allow other researchers to reproduce the entire dataset if needed. 
2) Be mindful of data organization. It is a good practice to put yourself in place of a potential user and think of an efficient folder structure to receive the data. In other words, present your dataset in a way that makes it readily implementable.
3) Make sure that the data (and labels if available) is saved in file formats suitable for your data type and readable by all operating systems. For example, text `.txt` files, comma-separated value `.csv` files, and Tagged Image File Format `.tiff` images could all be suitable formats. Also, avoiding formats that require licensed software to be read aligns with the notion of open science.
4) Avoid large file and folder sizes. This will make it easier for other researchers to sample your dataset and check if it is suitable for their application. Smaller file sizes are also more convenient for researchers around the world with suboptimal internet speeds.
5) Choose an online platform that best suits the type of data in your dataset, its potential users, and its overall size. Institutional repositories, when available, are always a great choice. Other popular options include [Dryad](https://datadryad.org/stash), [zenodo](https://zenodo.org/), and [figshare](https://figshare.com/).


### Recommendations for publicly sharing software tools or code <a name="recomends_code"></a>
Regarding open-access software or code, there are also a number of practices that make developing computational tools more straightforward to build and share, and, on the other end, easier to download and use. Below are key points to consider:

1) Build your code with a [confessional programming](https://wiki.c2.com/?RubberDucking) mindset. A user who is familiar with any coding language to some extent should be able to understand the main working functions of the code.
2) Keep in mind that the shared code might need to be updated or built on by you or by other users. A good practice is to segment the code into simpler functions where each function has a single purpose. This will also be useful for code testing and coverage (check recommendation #4)
3) Use an open-source programming language. This will make your software more accessible and better aligned with the concept of open science. 
4) Develop code that can be used across different operating systems. A practical way to build and test your code on different operating systems is through [GitHub Actions](https://docs.github.com/en/actions).  
5) Make sure to include detailed installation instructions, extensive documentation, and an easy-to-follow tutorial with your code dissemination. Always assume that the end users have very limited programming experience. To do this, you can take advantage of README files or host the full user guide on a documentation hosting site like [Read the Docs](https://about.readthedocs.com/).
6) Choose an online platform that best fits your preferences. Potential options include [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [SourceForge](https://sourceforge.net/), and [Bitbucket](https://bitbucket.org/).

### Recommendations for publicly sharing experimental protocols <a name="recomends_protocol"></a>
Although our experience with writing and sharing experimental protocols is very limited, we have come across a number of useful as well as secure platforms for sharing detailed methods and protocols, specifically [protocols.io](https://www.protocols.io/), [Addgene Protocols](https://www.addgene.org/protocols/), and [openlabnotebooks.org](https://openlabnotebooks.org/). 

### Recommendations for publicly sharing research preprints or papers <a name="recomends_paper"></a>
In an attempt to make science more and more available, many researchers are either moving towards publishing in open-access journals or making their work available on e-Print archives such as [arXiv](https://arxiv.org/) or [bioRxiv](https://www.biorxiv.org/) when the journal allows it. Ideally, one should aim to publish in open-access and open-review journals as these types of journals become more common (see [The Journal of Open Source Software](https://joss.theoj.org/) for an example). 

To identify relevant open-access journals, [TOP Factor](https://topfactor.org/journals) serves as an excellent resource. 

## Case Study <a name="case"></a>
We include here an example from our recent work to serve as a rough guide for those interested in making their work publicly available. We do not claim, by any means, that our approach is flawless; however, we have established a practical workflow for developing, curating, and disseminating all aspects of our research work. Our ultimate goal is to both, make our work fully available to other researchers and provide the means to fully reproduce our findings. 

This work is comprised of an open-source software, [MicroBundleCompute](https://github.com/HibaKob/MicroBundleCompute), a publicly shared dataset of synthetically generated examples, [SyntheticMicroBundle](https://github.com/HibaKob/SyntheticMicroBundle), a publicly shared dataset of [experimental examples](https://doi.org/10.5061/dryad.5x69p8d8g), and a manuscript published in an open-access journal, [PLOS ONE](https://journals.plos.org/plosone/).

### Code
Following the recommendations listed [above](#recomends_code), we developed our software in Python and shared it under MIT License on GitHub. We adopted a test-driven development approach and employed [pytest](https://docs.pytest.org/en/8.2.x/) for local code testing and [GitHub Actions](https://docs.github.com/en/actions) for automated virtual testing on 3 different operating systems: Ubuntu, macOS, and Windows.  

In addition, we provided a very detailed [README page](https://github.com/HibaKob/MicroBundleCompute/blob/master/README.md) with clear installation instructions targeted towards users with limited experience in programming, and a step-by-step usage tutorial including a comprehensive description of the required inputs to the software as well as all output files. We also included our contact information in case anyone has a question about the installation or usage of the package or has a suggestion on how to further improve it. 

### Dataset
We make all data used in developing our Python package available for further testing and reproducibility. Specifically, we validated [MicroBundleCompute](https://github.com/HibaKob/MicroBundleCompute) against synthetically generated data and showcased the capabilities of the code with real experimental data. 

For our synthetic dataset, aside from sharing the final products, we included all the necessary metadata as well as the steps and scripts to reproduce the entire dataset. Specifically, this dataset was generated by combining the results of Finite Element (FE) simulations and images extracted from real examples. We make the entire pipeline, starting from the meshed geometry shared as an `.xdmf` file, to the finite element code written in Python and implemented in [FEniCS](https://fenicsproject.org/)- an open-source partial differential equations (PDEs) solver with the Finite Element method (FEM), the original images used in generating the synthetic examples, and, finally, the Python script used to warp the original images according to the displacement results extracted from the FE simulations. We also include a brief tutorial demonstrating how to implement the whole pipeline.

As for the real experimental data, we shared the original movies as obtained experimentally as `.tif` files on [Dryad](https://doi.org/10.5061/dryad.5x69p8d8g) and included a brief description of the contents. Additionally, we included all relevant experimental conditions and procedures that are sufficient to generate a similar dataset. We identified these set of parameters as: `1)` data type (relevant to the type of experimental platform used), `2)` example (file number of the shared example), `3)` imaging modality (brightfield or phase contrast), `4)` post-seeding imaging (time at which images were taken following cell seeding), `5)` microscope, `6)` camera, `7)` imaging magnification, `8)` imaging frequency, `9)` pillar stiffness (a parameter relevant to the experimental platform), `10)` tissue preparation protocol, `11)` testbeds fabrication (description of fabricating the experimental platform), and `12)` additional details (details specific to the experimental platform). We summarized this information in a `PDF` file and provided a machine readable `.csv` version as well. Finally, we made sure that the total size of the dataset is reasonable (less than 4GB). Of note, one can divide larger datasets into multiple folders of smaller sizes.

### Manuscript
For publishing our work, we chose [PLOS ONE](https://journals.plos.org/plosone/), an open-access journal that also allows publishing the peer review history although the reviewers are kept anonymous (as opposed to an open-review journal such as [Joss](https://joss.theoj.org/)). 

[PLOS ONE](https://journals.plos.org/plosone/) also encourages publishing preprints. This allowed us to make our work available on [arxiv](https://doi.org/10.48550/arXiv.2308.04610) well before the paper was accepted for publication. This does not only increase the visibility of the work early on, but also makes it available for other researchers to check the work and potentially benefit from it.


## Additional Resources <a name="resources"></a>
* [Center for Open Science](https://www.cos.io/)
* [FOSTER portal](https://www.fosteropenscience.eu)
* [Center for Expanded Data Annotation and Retrieval](https://metadatacenter.org/)
* [Project TIER](https://www.projecttier.org/)
* [REMBI: Recommended Metadata for Biological Images—enabling reuse of microscopy data in biology](https://doi.org/10.1038/s41592-021-01166-8)


## Contact Information <a name="contact"></a>
For additional information, please contact Emma Lejeune `elejeune@bu.edu` or Hiba Kobeissi `hibakob@bu.edu`.