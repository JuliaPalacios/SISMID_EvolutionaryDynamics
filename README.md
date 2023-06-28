


<p>  </p>

<p>  </p>

Instructor(s):
Palacios, Julia; Müller, Nicola.

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time, and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.7.4) of  [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts.
BEAST2 is coded in java and does require java to be installed to work.
The tutorials covered here work with the newest version of BEAST2 (which is developped largely independent from BEAST1).
If there are any issues with the installation, please post the error in the SISMID slack channel mod04_evolutionary_dynamics_molecular_epidemiology_2023.
Please also install [Tracer 1.7.2](https://github.com/beast-dev/tracer/releases/tag/v1.7.2) to visualize MCMC traces.

## Schedule (Times in Pacific Time)


**Wednesday, July 12: Introduction** <br />
1:30-2:30: *Lecture Julia* Introduction Into Bayesian Phylogenetics and BEAST<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_Introduction.pdf?raw=true)<br />


2:50-5:00:  *Lecture Julia + Tutorial Nicola*  Getting BEAST2 to run with SARS2 <br />
                Slides: [Introduction to BEAST 2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_IntroductionToBEAST2_NT.pdf)<br />
Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />

**Thursday, July 13: Modeling evolution**

8:30 - 9:20 *Lecture Nicola* Modelling the evolution of genomes through time<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_evol_nfm.pptx?raw=true)<br />


9:20-10:00 *Tutorial Nicola:* BModelTest Tutorial with Influenza <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2021-07-22_BModelTest.zip?raw=true)<br />

10:00-10:30 *Break*<br/>

10:30 - 11:20: *Lecture Julia:* Lecture: tree priors (coalescent+birth death) <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_tree_priors.pdf?raw=true)<br />               
11:20 - 12:10: *Tutorial Julia:* Estimation of effective population size trajectories <br />
                Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true).<br />

12:10-13:10:  Lunch break

13:10 - 14:00: Priors and convergence
*Short Lecture Prior (Nicola):* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_priors_nfm.pptx?raw=true)<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true)<br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />

14:00 - 15:00 *Lecture Julia:*  how to visualize and interpret trees <br />
                Slides: [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658864130000)


13:40 -14:30
*Lecture + Tutorials: Julia* Tree distances and tree convergence <br />
                Slides1: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_Summary_Trees.pdf?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658865696000)


Day 1 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/)


**Tuesday 26th: Estimation of population level trends from phylogenetic trees**




10:10 -11:00 *Lecture Nicola:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_structured_nfm.pptx?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/1jUL8bot-o1R6S2-Uo8nMBT6ab_rhYyZpLFu93KOT9WlwhjhQzuwHfaHzWZQbOQ.ft0YgjPvZTfNXmf_?startTime=1658855466000)

11:00-11:30 lunch break


11:30 - 12:20 *Tutorial Nicola:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [Mascot](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Mascot-Tutorial.zip?raw=true), [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true).<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658860320000)<br/>
                [here2](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658862912000)





2:40 - 3:10: Phylo chat office hours

Day 2 additional tutorial suggestions: [Discrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/), [Mascot-GLM](https://github.com/nicfel/GLM-Tutorial)

**Wednesday 27th: Recombination and phylogenetic networks**


8:00 - 8:50: *Lecture Nicola:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-27-sismid_network_nfm.pptx?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/P1vyeWhX03_vwSJ0zE_99S-5tsG6WOIlKsWmgVrkOyUcm17D4idjYDes7zI_sOjH.Y8kIyGdYh7iJ5csh?startTime=1658934128000)

9:05 - 10:30: *Tutorial Nicola:* Inferring reassortment and recombination patterns <br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Reassortment-Tutorial.zip?raw=true), [Coalescent with Recombination](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Recombination-Tutorial.zip?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/P1vyeWhX03_vwSJ0zE_99S-5tsG6WOIlKsWmgVrkOyUcm17D4idjYDes7zI_sOjH.Y8kIyGdYh7iJ5csh?startTime=1658938078000) [here2](https://stanford.zoom.us/rec/share/P1vyeWhX03_vwSJ0zE_99S-5tsG6WOIlKsWmgVrkOyUcm17D4idjYDes7zI_sOjH.Y8kIyGdYh7iJ5csh?startTime=1658942206000)

10:30-11:00 Closing Remarks and Q&A<br />
                Video:[here](https://stanford.zoom.us/rec/share/P1vyeWhX03_vwSJ0zE_99S-5tsG6WOIlKsWmgVrkOyUcm17D4idjYDes7zI_sOjH.Y8kIyGdYh7iJ5csh?startTime=1658942911000)

11:00 - 11:20: Phylo chat office hours

Day 3 additional tutorial suggestions: [Bacter](https://taming-the-beast.org/tutorials/Bacter-Tutorial/), [SCoRe](https://github.com/jugne/SCoRe-tutorial)

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
