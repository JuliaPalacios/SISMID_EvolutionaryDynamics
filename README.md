


<p>  </p>

<p>  </p>

Instructor(s):
Juli A. Palacios and Nicola Müller.

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time, and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.7.5) of  [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts.
BEAST2 is coded in java and does require java to be installed to work.
The tutorials covered here work with the newest version of BEAST2 (which is developed largely independent from BEAST1).
If there are any issues with the installation, please post the error in the SISMID slack channel mod04_evolutionary_dynamics_molecular_epidemiology_2023.
Please also install [Tracer 1.7.2](https://github.com/beast-dev/tracer/releases/tag/v1.7.2) to visualize MCMC traces.

## Schedule (Times in Pacific Time)

Lecture room: Fishery Sciences Building (FSH) Room 107 located at 1122 NE Boat Street, Seattle, WA 98195. 


**Wednesday, July 12: Introduction** <br />
12:30-1:30: Registration at the Portage Bay Area located on the second floor of the South Campus Center (SCC), 1601 NE Columbia Rd, Seattle WA 98195 (Columbia Road entrance is on the third floor so head downstairs). </br>

1:30-3:00: Lecturer: Julia. *Introduction Into Bayesian Phylogenetics and BEAST* <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_Introduction.pdf?raw=true)<br />

3:30-5:00:  *Short lecture + Tutorial, Nicola*  Getting BEAST2 to run with SARS2 <br />
Slides: [Introduction to BEAST 2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_IntroductionToBEAST2_NT.pdf)<br />
Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />

**Thursday, July 13: Modeling evolution**

8:30 - 10:00 *Lecture + Tutorial, Nicola* Modelling the evolution of genomes through time<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_evol_nfm.pptx?raw=true)<br />
                Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2021-07-22_BModelTest.zip?raw=true)<br />


10:30 - 12:00: *Lecture +Tutorial, Julia:* Lecture: coalescent tree priors  <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_tree_priors.pdf?raw=true)<br />               
                Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true).<br />
                
1:30-3:00 *Lecture + Turotiral, Julia: Birth death tree priors <br/>

3:30-5:00pm *Lecture Priors, convergence and troubleshooting
*Short Lecture Prior (Nicola):* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_priors_nfm.pptx?raw=true)<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true)<br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />

*Lecture + Tutorials: Julia* Tree distances, summaries and tree convergence <br />
                Slides1: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_Summary_Trees.pdf?raw=true)<br />
                





**Friday, July 14: Modeling evolution II**

8:30-10:00pm: *Lecture and Tutorial Nicola:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_structured_nfm.pptx?raw=true)<br />
           
10:30 - 11:15: *Lecture Nicola Multi-type birth-death models and visualizations </br>
11:15 - 12:00: *Lecture Julia:*  how to visualize and interpret trees and phylogenetic mapping <br />
                Slides: [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658864130000)


1:30-3:00pm: *Lecture Nicola:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-27-sismid_network_nfm.pptx?raw=true)<br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Reassortment-Tutorial.zip?raw=true), [Coalescent with Recombination](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Recombination-Tutorial.zip?raw=true)<br />
               
                
3:30pm-5:00pm: XML structure and simulation with MASTER



1:30 -3:00pm

[Discrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/), [Mascot-GLM](https://github.com/nicfel/GLM-Tutorial)

3:30-5:00pm

Day 1 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/)


Additional tutorial suggestions: [Bacter](https://taming-the-beast.org/tutorials/Bacter-Tutorial/), [SCoRe](https://github.com/jugne/SCoRe-tutorial)

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
