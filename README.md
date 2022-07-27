


<p>  </p>

<p>  </p>

Instructor(s):
Palacios, Julia; Müller, Nicola; Trovão, Nídia; Barido-Sottani, Joëlle

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install the newest version (2.6.7) of  [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts.
BEAST2 is coded in java and does require java to be installed to work.
The tutorials covered here work with the newest version of BEAST2 (which is developped largely independent from BEAST1).
If there are any issues with the installation, please post the error in the SISMID slack channel md16_evolutionary_dynamics_molecular_epi_viruses_2022.

## Schedule (Times in Pacific Time)

[Zoom link](https://stanford.zoom.us/j/93968078131?pwd=dDJOejNKZU43clNRN01XN05BWWRsdz09) <br />


**Monday 25th: Getting started with BEAST 2** <br />
8-8:50: *Lecture Julia, M: Nicola:* Introduction Into Bayesian Phylogenetics and BEAST<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_Introduction.pdf?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/66uvMHNM7Heu1mPUzRAYn-iLYe96Poy3F1ikeZVVIqPX792fjCmjT7aravPDiZpl.rJVvJEiUldq_SKOE?startTime=1658761529000)

9:05-11:00:  *Lecture Nídia + Tutorial Joëlle, M: Joëlle:*  Getting BEAST2 to run with SARS2 <br />
                Slides: [Introduction to BEAST 2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-21_IntroductionToBEAST2_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/66uvMHNM7Heu1mPUzRAYn-iLYe96Poy3F1ikeZVVIqPX792fjCmjT7aravPDiZpl.rJVvJEiUldq_SKOE?startTime=1658765295000)<br />
                Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)<br />
                Video2: [part1](https://stanford.zoom.us/rec/share/66uvMHNM7Heu1mPUzRAYn-iLYe96Poy3F1ikeZVVIqPX792fjCmjT7aravPDiZpl.rJVvJEiUldq_SKOE?startTime=1658768741000) [part2](https://stanford.zoom.us/rec/share/66uvMHNM7Heu1mPUzRAYn-iLYe96Poy3F1ikeZVVIqPX792fjCmjT7aravPDiZpl.rJVvJEiUldq_SKOE?startTime=1658771657000)


11:00-11:30 lunch break

11:30 - 12:20 *Lecture Nicola, M: Julia:* Modelling the evolution of genomes through time<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_evol_nfm.pptx?raw=true)<br />
                Videos: [here](https://stanford.zoom.us/rec/share/R5BHj64lU_x4_POZmza78l_I2f7pAf5jTWOdRI4-_2zSLaDut1IoGmTZmEy0RGoX.QDuZkAIJBsbBp32L?startTime=1658773917000) 
                
12:35 - 13:25 *Tutorial Nicola:* BModelTest Tutorial with Influenza <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2021-07-22_BModelTest.zip?raw=true)<br />
                Videos: [part1](https://stanford.zoom.us/rec/share/2tdIOP7l71j-CUouT8_F4JD7S9orvd8qbj7WbnzRWnPuEhtXvXDR0BfLn80BsEgC.q5UW689UuNaFalmU?startTime=1658777814000),[part2](https://stanford.zoom.us/rec/share/2tdIOP7l71j-CUouT8_F4JD7S9orvd8qbj7WbnzRWnPuEhtXvXDR0BfLn80BsEgC.q5UW689UuNaFalmU?startTime=1658780410000)


13:40 - 14:30: Priors and convergence
*Short Lecture Prior (Nicola) + Tutorial Joëlle + Small Lecture Joëlle on Convergence, M: Nicola:* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-25_priors_nfm.pptx?raw=true)<br />
                Videos: [here](https://stanford.zoom.us/rec/share/2tdIOP7l71j-CUouT8_F4JD7S9orvd8qbj7WbnzRWnPuEhtXvXDR0BfLn80BsEgC.q5UW689UuNaFalmU?startTime=1658781675000)<br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true)<br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)<br />
               

2:40 - 3:10: Phylo chat office hours


Day 1 additional tutorial suggestions: [Model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/), [Coupled MCMC](https://taming-the-beast.org/tutorials/CoupledMCMC-Tutorial/) 

              
**Tuesday 26th: Estimation of population level trends from phylogenetic trees**


8:00 - 8:50: *Lecture Julia, M: Joëlle:* Lecture: tree priors (coalescent+birth death) <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_tree_priors.pdf?raw=true)<br />                Video: [here](https://stanford.zoom.us/rec/share/1jUL8bot-o1R6S2-Uo8nMBT6ab_rhYyZpLFu93KOT9WlwhjhQzuwHfaHzWZQbOQ.ft0YgjPvZTfNXmf_?startTime=1658847742000)

9:05 - 9:55: *Tutorial Julia:* Estimation of effective population size trajectories <br />
                Tutorial: [Ne inference](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true).<br />
                Video:[here](https://stanford.zoom.us/rec/share/1jUL8bot-o1R6S2-Uo8nMBT6ab_rhYyZpLFu93KOT9WlwhjhQzuwHfaHzWZQbOQ.ft0YgjPvZTfNXmf_?startTime=1658851593000)
                
10:10 -11:00 *Lecture Nicola + Joëlle:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-26-sismid_structured_nfm.pptx?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/1jUL8bot-o1R6S2-Uo8nMBT6ab_rhYyZpLFu93KOT9WlwhjhQzuwHfaHzWZQbOQ.ft0YgjPvZTfNXmf_?startTime=1658855466000)
                
11:00-11:30 lunch break


11:30 - 12:20 *Tutorial Nicola + Joëlle:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [Mascot](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Mascot-Tutorial.zip?raw=true), [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true).<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658860320000)<br/>
                [here2](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658862912000)
                
12:35 - 13:25 *Lecture Nídia:*  how to visualize and interpret trees <br />
                Slides: [Post-processing of BEAST trees](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-23_FigTreeTutorial_NT.pdf)<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658864130000)
                
                
13:40 -14:30
*Lecture + Tutorials: Julia, M: Joëlle* Tree distances and tree convergence <br />
                Slides1: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2021-07-22_Summary_Trees.pdf?raw=true)<br />
                Video: [here](https://stanford.zoom.us/rec/share/q_U_E-gLrxv-B57u3_WBTxQmJRjm0i3g1j69a5NEhTSN59q9ObSSzgv1JCT5b_Qo.WHp1UMUqs0Zryf2b?startTime=1658865696000)

               

2:40 - 3:10: Phylo chat office hours

Day 2 additional tutorial suggestions: [Discrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/), [Mascot-GLM](https://github.com/nicfel/GLM-Tutorial)

**Wednesday 28th: Recombination and phylogenetic networks**


8:00 - 8:50: *Lecture Nicola, M: Nídia:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2022-07-27-sismid_network_nfm.pptx?raw=true)<br />
                Video: [here]()

9:05 - 10:30: *Tutorial Nicola:* Inferring reassortment and recombination patterns <br />
                Tutorials: [Coalescent with Reassortment](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Reassortment-Tutorial.zip?raw=true), [Coalescent with Recombination](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Recombination-Tutorial.zip?raw=true)<br />
                Video: [here]()
                
10:30-11:30 Closing Remarks and Q&A<br />
                Video:[here]()
                
12:00 - 12:30: Phylo chat office hours

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
