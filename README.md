


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

[Zoom link]() <br />


**Wednesday 21st: Getting started with BEAST 2** <br />

11:30 - 12:20: *Lecture Julia, M: Nicola:* Introduction Into Bayesian Phylogenetics and BEAST<br />
                Slides: <br />
                Video: 

12:35 - 2:30  *Lecture Nídia + Tutorial Joëlle, M: Joëlle:*  Getting BEAST2 to run with SARS2 <br />
                Slides: [Introduction to BEAST 2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_IntroductionToBEAST2_NT.pdf)<br />
                Video: <br />
                Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />
                Video: 

2:40 - 3:10: Phylo chat office hours. 

In preparation for Thursday, please install [R](https://www.r-project.org). We will use the follwing packages: ape (R cran), [phylodyn](https://github.com/mdkarcher/phylodyn), and [bdskytools](https://github.com/laduplessis/bdskytools). Needed?

**Thursday 22nd: Sequence evolution and Estimation of population level trends using phylogenetic trees**

8:00 - 8:50 *Lecture Nicola, M: Julia:* Modelling the evolution of genomes through time<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_sismid_evol_nfm.pptx?raw=true)<br />
                Videos: 

9:05 - 9:55 *Tutorial Nicola:* BModelTest Tutorial with Influenza <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-27_BModelTest.zip?raw=true)<br />
                Videos: 

10:10 - 11:00: *Lecture Julia, M: Joëlle:* Lecture: tree priors (coalescent+birth death) <br />
                Slides: <br />
                Video: 

11:30 - 12:20: *Tutorial Julia:* Estimation of effective population size trajectories <br />
                Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true).<br />
                Video: 
               
12:35 - 1:25: Priors and convergence
*Short Lecture Prior (Nicola) + Tutorial Joëlle + Small Lecture Joëlle on Convergence, M: Nicola:* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: <br />
                Videos: <br />
                Slides: <br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />

1:40 - 2:30
*Lecture + Tutorials: Julia & Nídia, M: Joëlle* Tree distances and tree convergence <br />
                Slides1: <br />
                Slides2: <br />
                Data: [here](https://juliapalacios.github.io/SISMID_EvolutionaryDynamics/Datasets/h3n2-bdmm.h3n2_2deme.MCC_2005.668.tre)<br />
                Video: 


2:40 - 3:10: Phylo chat office hours

Day 2 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/)

**Friday 23rd: Analyzing structured populattions and whole genomes**

8:00 - 8:50 *Lecture Nicola + Joëlle:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_sismid_structured_nfm.pptx?raw=true)<br />
                Video: 

9:05 - 10:40 *Tutorial Nicola + Joëlle:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [Mascot](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-28_Mascot.zip?raw=true), [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true).<br />
                Video: 
                
10:40 - 11:00 *Lecture Nídia:*  how to visualize and interpret trees <br />
                Slides: [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Video: 

11:30 - 12:20: *Lecture Nicola, M: Nídia:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_sismid_network_nfm.pptx?raw=true)<br />
                Video: 

12:35 - 2:00: *Tutorial Nicola:* Inferring reassortment and recombination patterns <br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-29_Reassortment.zip?raw=true), [Coalescent with Recombination](https://github.com/nicfel/Recombination-tutorial)<br />
                Video: 
                
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
