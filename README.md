


<p>  </p>

<p>  </p>

Instructor(s):
Palacios, Julia; Müller, Nicola; Trovão, Nídia; Barido-Sottani, Joëlle

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts.
BEAST2 is coded in java and does require java to be installed to work.
The tutorials covered here work with the newest version of BEAST2 (which is developped largely independent from BEAST1).
If there are any issues with the installation, please post the error in the SISMID slack channel md14_evolutionary_dynamics_molecular_epi_viruses_2021.

## Schedule (Times in Pacific Time)

[Zoom link](https://stanford.zoom.us/j/95863616151?pwd=Tis3UXBLNmNYdUxvRHFZcTRKbmNiUT09) <br />


**Wednesday 21st: Getting started with BEAST 2** <br />

11:30 - 12:20: *Lecture Julia, M: Nicola:* Introduction Into Bayesian Phylogenetics and BEAST<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_Introduction.pdf?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/-6aDehBWYZJA10j5507y5FJBAIyvZml480nLzj1ZX7rd48Qk3PLKn-UY2GtWcduj.WZTY4r-L9d9m5uXh?startTime=1626892546000)

12:35 - 2:30  *Lecture Nídia + Tutorial Joëlle, M: Joëlle:*  Getting BEAST2 to run with SARS2 <br />
                Slides: [Introduction to BEAST 2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_IntroductionToBEAST2_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/lp3Ei2GGrl_45cKDS7YB6teHqGxVjjUSoLfNpH1OUtWTcZZfGP1Q0GqexSusrD60.mZkLg1SZEPQkJo6T?startTime=1626896252000)<br />
                Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/-PLZn93I2KFgdC-SJrXTMA6kO0XJ_wP8cdA7_ocwjqXW4CXDiN2o71GLQsudWQ94.CI7-bny7r0Mp9cHu?startTime=1626899468000)

2:40 - 3:10: Phylo chat office hours. 

In preparation for Thursday, please install [R](https://www.r-project.org). We will use the follwing packages: ape (R cran), [phylodyn](https://github.com/mdkarcher/phylodyn), and [bdskytools](https://github.com/laduplessis/bdskytools). Needed?

**Thursday 22nd: Sequence evolution and Estimation of population level trends using phylogenetic trees**

8:00 - 8:50 *Lecture Nicola, M: Julia:* Modelling the evolution of genomes through time<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_sismid_evol_nfm.pptx?raw=true)<br />
                Videos: [here](https://stanford.zoom.us/rec/share/lreja8-Cf6rvbjcnWhI1EkdJ3lQpxSdfTfrMRImgzkapfiZ55r7xynrKoyGaNwpJ.h5B_hX9Jpzxl8TzG?startTime=1626966297000) 

9:05 - 9:55 *Tutorial Nicola:* BModelTest Tutorial with Influenza <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2021-07-22_BModelTest.zip?raw=true)<br />
                Videos: [part1](https://stanford.zoom.us/rec/share/lreja8-Cf6rvbjcnWhI1EkdJ3lQpxSdfTfrMRImgzkapfiZ55r7xynrKoyGaNwpJ.h5B_hX9Jpzxl8TzG?startTime=1626969978000),[part2](https://stanford.zoom.us/rec/share/lreja8-Cf6rvbjcnWhI1EkdJ3lQpxSdfTfrMRImgzkapfiZ55r7xynrKoyGaNwpJ.h5B_hX9Jpzxl8TzG?startTime=1626972729000)

10:10 - 11:00: *Lecture Julia, M: Joëlle:* Lecture: tree priors (coalescent+birth death) <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_tree_priors.pdf?raw=true)<br />                Video: [here](https://stanford.zoom.us/rec/share/lreja8-Cf6rvbjcnWhI1EkdJ3lQpxSdfTfrMRImgzkapfiZ55r7xynrKoyGaNwpJ.h5B_hX9Jpzxl8TzG?startTime=1626973935000)

11:30 - 12:20: *Tutorial Julia:* Estimation of effective population size trajectories <br />
                Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true).<br />
                Video:[here](https://stanford.zoom.us/rec/share/MEOYYY_970d3dX2UYLIG03mNHHiCc7VMk1IMn2XgRWO1bn7VojtnDi0yX1ZwthpM.IRgdmLN4S5JgJOkf?startTime=1626978761000)</b> 
               
12:35 - 1:25: Priors and convergence
*Short Lecture Prior (Nicola) + Tutorial Joëlle + Small Lecture Joëlle on Convergence, M: Nicola:* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_priors_nfm.pptx?raw=true)<br />
                Videos: [here](https://stanford.zoom.us/rec/share/MEOYYY_970d3dX2UYLIG03mNHHiCc7VMk1IMn2XgRWO1bn7VojtnDi0yX1ZwthpM.IRgdmLN4S5JgJOkf?startTime=1626982601000)<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true)<br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />
                Videos:[here](https://stanford.zoom.us/rec/share/MEOYYY_970d3dX2UYLIG03mNHHiCc7VMk1IMn2XgRWO1bn7VojtnDi0yX1ZwthpM.IRgdmLN4S5JgJOkf?startTime=1626983104000)
                [here2](https://stanford.zoom.us/rec/share/MEOYYY_970d3dX2UYLIG03mNHHiCc7VMk1IMn2XgRWO1bn7VojtnDi0yX1ZwthpM.IRgdmLN4S5JgJOkf?startTime=1626986554000)

1:40 - 2:30
*Lecture + Tutorials: Julia, M: Joëlle* Tree distances and tree convergence <br />
                Slides1: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_Summary_Trees.pdf?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/MEOYYY_970d3dX2UYLIG03mNHHiCc7VMk1IMn2XgRWO1bn7VojtnDi0yX1ZwthpM.IRgdmLN4S5JgJOkf?startTime=1626986888000)


2:40 - 3:10: Phylo chat office hours

Day 2 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/)

**Friday 23rd: Analyzing structured populattions and whole genomes**

8:00 - 8:50 *Lecture Nicola + Joëlle:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_sismid_structured_nfm.pptx?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/7AsGkB1qDz0_qoNIpMvGyf6uKVHvmO2Dg7NwtaNQYla7pQq_qoSNz1mJnLrGHFPl.FJzJFuCQbGTJz0B9?startTime=1627052560000)

9:05 - 10:40 *Tutorial Nicola + Joëlle:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [Mascot](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Mascot-Tutorial.zip?raw=true), [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true).<br />
                Video: [here](https://stanford.zoom.us/rec/share/7AsGkB1qDz0_qoNIpMvGyf6uKVHvmO2Dg7NwtaNQYla7pQq_qoSNz1mJnLrGHFPl.FJzJFuCQbGTJz0B9?startTime=1627056463000)<br/>
                [here2](https://stanford.zoom.us/rec/share/7AsGkB1qDz0_qoNIpMvGyf6uKVHvmO2Dg7NwtaNQYla7pQq_qoSNz1mJnLrGHFPl.FJzJFuCQbGTJz0B9?startTime=1627061499000)
                
10:40 - 11:00 *Lecture Nídia:*  how to visualize and interpret trees <br />
                Slides: [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/7AsGkB1qDz0_qoNIpMvGyf6uKVHvmO2Dg7NwtaNQYla7pQq_qoSNz1mJnLrGHFPl.FJzJFuCQbGTJz0B9?startTime=1627061930000)

11:30 - 12:20: *Lecture Nicola, M: Nídia:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_sismid_network_nfm.pptx?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/ehfWIl10xUkweRCVBKR043Md6tkCDmLwn5iROiNfUhsfyUW31alT-sQzn3M7t18.-_HsanlGaMPXB8Zf?startTime=1627065166000)

12:35 - 2:00: *Tutorial Nicola:* Inferring reassortment and recombination patterns <br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Reassortment-Tutorial.zip?raw=true), [Coalescent with Recombination](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Recombination-Tutorial.zip?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/HWnly0KWFhASGoOwG8G0e6yU6es05HBPkPxgF6eMnMnBW75A1CHN23wcSeg2Zcxn.vp9842wYBbnCJO0-?startTime=1627073434000)
                
2:00-2:30 Closing Remarks and Q&A            
                
2:30 - 3:00: Phylo chat office hours

Day 3 additional tutorial suggestions: [Discrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/), [Mascot-GLM](https://github.com/nicfel/GLM-Tutorial), [Bacter](https://taming-the-beast.org/tutorials/Bacter-Tutorial/)
         
Prerequisites: This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module.

# Some Reading Material

- Overview of most BEAST2 packages: [https://doi.org/10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)

- Review of phylodynamics (with a focus on the coalescent): [https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002947](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002947)

- Review of phylodynamics in livestock: [https://www.sciencedirect.com/science/article/pii/S0169534721001300](https://www.sciencedirect.com/science/article/pii/S0169534721001300)

- Review for phylodynamics for cell biologists: [https://science.sciencemag.org/content/371/6526/eaah6266.abstract](https://science.sciencemag.org/content/371/6526/eaah6266.abstract)

- Review on combining phylogenetics with other data sources: [https://doi.org/10.1093/sysbio/syw054](https://doi.org/10.1093/sysbio/syw054)

# Acknowledgements

The tutorials we covered in this module were adapated tutorials from [https://taming-the-beast.org/](https://taming-the-beast.org/) (publication [here](https://academic.oup.com/sysbio/article/67/1/170/3897660)) and from past SISMID tutorials. 
Other than us, these tutorials and the lectures used here are partly based on work by:

- Louis du Plessis 

- Veronika Boskova

- David Rasmussen

- Carsten Magnus

- Sebastian Duchene

- Timothy G. Vaughan

- Denise Kühnert

- Julia Pecerska

- Marc Suchard

- Philippe Lemey
