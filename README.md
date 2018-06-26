# GCC BOSC 2018
# Setting up for Success: Everything you need to know when planning for an RNA-seq analysis

| Audience | Computational Skills | Prerequisites | Duration |
:----------|:----------|:----------|:----------|
| Novice to Experienced Researchers | None | None | 2 sessions (2.5 hour and 3 hour)|

This two-part workshop is geared towards researchers who are thinking about conducting an RNA-seq experiment and are interested in knowing more about what is involved. The planning process requires taking a step back to evaluate various factors and ultimately assess the feasibility of the experiment, including thinking about potential pitfalls and how to avoid them. The workshop will go into detail about the different strategies for working with RNA-seq data depending on the biological question being addressed. Specific topics include:

* Best practice guidelines for experimental design (Biological replicates, Paired-end vs Single-end, Sequencing depth).
* Data storage and computational requirements.
* Overview of commonly used workflows for differential gene expression, de-novo assembly, isoform quantification and other uses of RNA sequencing.

The focus of this workshop is to outline current standards and required resources for the analysis of RNA sequencing data. This workshop will not provide an exhaustive list of software tools or pipelines available; rather it aims to provide a fruitful discussion on how best to prepare for performing RNA-seq data analysis from the lab to manuscript preparation.

***We are excited to be teaching this workshop with [Chris Fields](https://github.com/cjfields) from [HPCBio](https://hpcbio.illinois.edu/) at University of Illinois in Urbana-Champaign, [cjfields@illinois.edu](mailto:cjfields@illinois.edu).***

### Learning Objectives

* Describe the resources needed to perform an experiment to identify differentially expressed genes using RNA sequencing, including in the laboratory and computationally.
* Describe key experimental design considerations.
* Explain the analysis workflow (including QC) starting with raw data and finishing with a list of differentially expressed genes. 
* List tools and computational skills necessary to implement the various steps in the above-mentioned workflow.

### Contents/Schedule


| Lessons            | Duration | Presenter | 
|:------------------------|:----------|:----------|
| [Introduction](https://hbctraining.github.io/GCC-BOSC-2018/slides/Intro_to_workshop.pdf) | 15 mins | Radhika Khetani |
| [Library Prep](https://hbctraining.github.io/GCC-BOSC-2018/slides/library_prep.pdf) | 30 mins | Radhika Khetani |
| [Sequencing steps & sequencers](https://hbctraining.github.io/GCC-BOSC-2018/slides/sequencing_technologies_mm.pdf) | 25 mins | Meeta Mistry |
| [Experimental planning considerations](lessons/experimental_planning_considerations.md) | 35 mins | Mary Piper |
| [Strategies for bulk RNA-seq analysis](https://hbctraining.github.io/GCC-BOSC-2018/slides/RNAseq-strategies_mm.pdf) | 30 mins | Meeta Mistry |
| [Data management](https://hbctraining.github.io/GCC-BOSC-2018/slides/data_management.pdf) | 15 mins | Radhika Khetani |
| Break | 30 mins |  |
| [Raw data QC](https://hbctraining.github.io/GCC-BOSC-2018/slides/QC_rawdata_mp.pdf) | 30 mins | Mary Piper |
| [Mapping/quantification](https://hbctraining.github.io/GCC-BOSC-2018/slides/alignment_quantification.pdf)| 25 mins | Radhika Khetani |
| [Sample-level assessment](https://hbctraining.github.io/GCC-BOSC-2018/lessons/sample_level_QC.html) | 30 mins | Mary Piper |
| [Count modeling and hypothesis testing](lessons/count_modeling.md) | 30 mins | Meeta Mistry |
| [Visualization of results](lessons/data_visualization.md)| 15 mins | Radhika Khetani |
| [Functional analysis](https://hbctraining.github.io/GCC-BOSC-2018/slides/functional_analysis_mp.pdf) | 20 mins | Mary Piper |

### Resources

* [Information about RIN number from Agilent](https://www.agilent.com/cs/library/applications/5989-1165EN.pdf)
