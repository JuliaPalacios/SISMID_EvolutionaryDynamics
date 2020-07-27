


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
If there are any issues with the installation, please post the error in the SISMID slack channel mod14evoldynamics.

## Schedule (Times in Pacific Time)

**Monday 27th: Getting started with BEAST**
[Zoom link here](https://us02web.zoom.us/j/86947202957?pwd=QUtxSFRPTWx0QXVlYUx6d0VxaEJmZz09)

8:00 - 8:50: *Lecture Julia, M: Nicola:* Introduction <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Lectures/2020-07-27_Introduction.pdf)
                [Video](https://drive.google.com/drive/folders/1sPierJjRgTxGnXS0axvtn3jgcnPYTegm?usp=sharing)

9:05 - 11:00  *Lecture Nídia + Tutorial Joëlle, M: Joëlle:*  Getting BEAST2 to run with SARS2 <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Lectures/2020-07-27_IntroductionToBEAST2_NT.pdf) <br />
                Tutorial: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)

11:30 - 12:20 *Lecture Nicola, M: Julia:* clock and site models <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_evol_nfm.pptx?raw=true)

12:35 - 13:15 *Tutorial Nicola:* BModelTest Tutorial with Influenza <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-27_BModelTest.zip?raw=true)

13:30 - 14:20: *Short Lecture Prior (Nicola) + Tutorial Joëlle + Small Lecture Joëlle on Convergence, M: Nicola:* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [Selecting priors](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_priors_nfm.pptx?raw=true) <br />
                Slides: [Convergence and troubleshooting](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true) <br />
                Tutorials: [Prior-selection](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)

15:00 - 15:30: Happy half-hour!

15:00 - 16:00: Phylo chat office hours

Day 1 additional tutorial suggestions: [molecular dating](https://taming-the-beast.org/tutorials/Molecular-Dating-Tutorial/), [clock and substitution model adequacy](https://taming-the-beast.org/tutorials/adequacy_tutorial/).

In preparation for Tuesday, please install [R](https://www.r-project.org) 



**Tuesday 28th: Estimating population level trends using phylogenetic trees**

8:00 - 8:50: *Lecture Julia, M: Joëlle:* Lecture: tree priors (coalescent+birth death) <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Lectures/2020-07-28_tree_priors.pdf)

9:05 - 10:30: *Tutorial Julia:* Estimation of effective population size trajectories <br />
                Tutorial: TBA

10:30 - 11:00 *Lecture Nicola + Joëlle:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-28_structured_nfm.pptx?raw=true)

11:30 - 13:00 *Tutorial Nicola + Joëlle:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [Mascot](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-28_Mascot.zip?raw=true), [BDMM](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true).

13:00 - 14:20 *Lecture + Tutorials: Julia & Nídia, M: Joëlle* Tree distances, tree convergence, how to visualize and interpret trees  Julia & Nídia<br />
                Slides: TBA<br />
                Data: TBA<br />
                Tutorials: TBA
                
Day 2 additional tutorial suggestions: [Descrete trait analysis (using BEAST1)](http://beast.community/workshop_discrete_diffusion), [MultiType tree](https://taming-the-beast.org/tutorials/Structured-coalescent/)


15:00 - 16:00: Phylo chat office hours

**Wednesday 29th: My tree is not a tree, help!**

8:00 - 8:50: *Lecture Nicola, M: Nídia:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-29_network_nfm.pptx?raw=true)

9:05 - 10:30: *Tutorial Nicola:* The coalescent with reassortment <br />
                Tutorials: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/2020-07-29_Reassortment.zip?raw=true)

10:30 - 11:00 *Closing Remarks and Q&A Everyone*

13:00 - 14:00: Phylo chat office hours

Day 3 additional tutorial suggestions: [Bacter](https://taming-the-beast.org/tutorials/Bacter-Tutorial/)


Prerequisites: This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module.

# Some Reading Material

- Provides an overview of packages in BEAST2 with explanations on the different models: [https://doi.org/10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)

- Paper showing site model over-fitting is ok: [https://www.nature.com/articles/s41467-019-08822-w](https://www.nature.com/articles/s41467-019-08822-w)

- Paper showing how to see if there is temporal signal in data using tip-randomizations: [https://academic.oup.com/mbe/article/32/7/1895/1016979](https://academic.oup.com/mbe/article/32/7/1895/1016979)

- Paper introducing the coalescent with reassortment: [https://doi.org/10.1073/pnas.1918304117](https://doi.org/10.1073/pnas.1918304117)

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
