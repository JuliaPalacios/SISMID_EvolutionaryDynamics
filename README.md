


<p>  </p>

<p>  </p>

Instructor(s):
Julia A. Palacios and Nicola F. Müller.

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time, and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.7.7) of  [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts.
BEAST2 is coded in java and does require java to be installed to work.
The tutorials covered here work with the newest version of BEAST2 (which is developed largely independent from BEAST1).
If there are any issues with the installation, please post the error in the SISMID slack channel module-evolution-and-molecular-epi-of-viruses.
Please also install [Tracer 1.7.2](https://github.com/beast-dev/tracer/releases/tag/v1.7.2) to visualize MCMC traces and [Figtree 1.4.4](https://github.com/rambaut/figtree/releases/tag/v1.4.4). 
**If you get a java error when trying to open Figtree 1.4.4, try [Figtree 1.4.5_pre](https://github.com/rambaut/figtree/releases/tag/v1.4.5pre) instead.**

## Schedule (Times in Eastern Daylight Time)

The workshop will take place in the Randall Rollins Building (RR 201)


**Wednesday, July 24: Introduction** <br />

1:30pm - 3:00pm: Lecturer: Julia. *Introduction to Bayesian Phylogenetics and BEAST* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-24_Introduction.pptx?raw=true)<br />

3:30pm - 5:00pm:  Lecturer: Nicola. *Getting BEAST2 to run with SARS2* <br />
Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-24_beast_introduction.pptx?raw=true)<br />
Tutorial: [Intro to BEAST2 tutorial](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />

**Thursday, July 25: Modeling evolution and tree priors**

8:30am - 10:00am Lecturer: Nicola  *Modelling the evolution of genomes through time*<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25-sismid_evol_nfm.pptx?raw=true)<br />
                [pdf](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25-sismid_evol_nfm.pdf?raw=true)<br />
                Tutorial: [BModelTest](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/BModelTest.zip?raw=true)<br />

10:30am - 12:00am: Lecturer: Julia *Coalescent and Birth death tree priors*  <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25_tree_priors.pptx?raw=true)<br />               
1:30pm - 3:00pm Lecturer: Julia <br/>
                 Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true)<br />
                
3:30pm - 4:40pm Lecturer: Nicola: *Priors and convergence issues and how to solve them with SARS2* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25_priorstrouble_nfm.pptx?raw=true)<br />
                [pdf](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25_priorstrouble_nfm.pdf?raw=true)<br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />
4:40pm - 5:00pm: Lecturer: Nicola and Julia *How does phylodynamics relate to transmission dynamics?* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-relation_phylodynamics_epidemiology.pptx?raw=true)<br />
                [pdf](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-relation_phylodynamics_epidemiology.pdf?raw=true)<br />

Day 2 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/)


**Friday, July 26: Structured populations, networks, and XML**

8:30am - 10:00am: Lecturer: Nicola *Structured populations* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-structured_nfm.pptx?raw=true)<br />
                                [pdf](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-structured_nfm.pdf?raw=true)<br />
                Tutorial: [MASCOT](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Mascot-Tutorial.zip?raw=true)<br />


10:30am - 11:00am: Lecturer: Nicola *Multi-type birth-death models* <br />
                Tutorial: [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true)<br />

11:00am - 11:40am: Lecturer: Julia: *How to visualize and interpret trees and phylogenetic mapping* <br />
                Slides: [PhylogeneticMapping](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-14_phylo_mapping.pptx) [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Mini Tutorial [ggtree](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/mascot_ggtree.zip?raw=true)

11:40am - 12:00am Lecturer: Julia  *Tree distances, summaries, and tree convergence* <br />
                Slides1: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-13_Summary_Trees.pdf?raw=true)<br />  



1:30pm - 3:00pm: Lecturer: Nicola: *Recombination and Reassortment* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-14-sismid_network_nfm.pptx?raw=true)<br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Reassortment-Tutorial.zip?raw=true)<br />
               
3:30pm - 4:30pm: Lecturer: Nicola  *XML hacking* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-14-xml_nfm.pptx?raw=true)<br />
                Tutorials: [XML-hacking](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/XML-Tutorial.zip?raw=true)<br />
                
4:30pm - 5:00pm: *Q&A and wrap up*  <br />

Additional tutorial suggestions: [Discrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [Continous diffusion model (in BEAST1)](https://beast.community/continuous_traits),[MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/), [Mascot-GLM](https://github.com/nicfel/GLM-Tutorial), [Masoct-Skyline](https://github.com/nicfel/MascotSkyline-Tutorial/), [Bacter](https://taming-the-beast.org/tutorials/Bacter-Tutorial/), [SCoRe](https://github.com/jugne/SCoRe-tutorial), [Coalescent with Recombination](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Recombination-Tutorial.zip?raw=true)


# Some Reading Material (not expected reading)

- Overview of a lot of BEAST2 packages: [https://doi.org/10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)

- Decoding Genomes: [https://decodinggenomes.org/](https://decodinggenomes.org/)

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
