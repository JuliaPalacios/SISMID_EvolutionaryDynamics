


<p>  </p>

<p>  </p>

Instructor(s):
Palacios, Julia; Müller, Nicola; Trovão, Nídia; Barido-Sottani, Joëlle

## General

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees 2 (BEAST2). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

## Before the course

Please install [BEAST2](https://www.beast2.org/) on the computer that you will be using before the workshop starts. 
If there are any issue with the installation that occur, please post the error in the SISMID slack channel mod14evoldynamics.

## Schedule

Monday 27th: Getting started with BEAST

8:00 - 8:50: *Lecture Julia, M: Nicola:* Intro Bayesian Phylogenetics <br />
                Slides: TBA

9:05 - 11:00  *Lecture Nídia + Tutorial Joelle, M: Joelle:*  Getting BEAST2 to run with SARS2 <br />
                Slides: TBA <br />
                Tutorial: [Introduction-to-BEAST2](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.pdf?raw=true)

11:30 - 12:20 *Lecture Nicola, M: Julia:* clock and site models <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_evol_nfm.pptx?raw=true)

12:35 - 13:15 *Tutorial Nicola:* clock and site models with Influenza <br />
                Tutorials: [https://taming-the-beast.org/tutorials/Substitution-model-averaging/](https://taming-the-beast.org/tutorials/Substitution-model-averaging/)

13:30 - 14:20: *Short Lecture Prior (Nicola) + Tutorial Joelle + Small Lecture Joelle on Convergence, M: Nicola:* Priors and convergence issues and how to solve them with SARS2 <br />
                Slides: [Convergence and troubleshooting](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-27_troubleshooting.pptx?raw=true) <br />
                Tutorials: [https://taming-the-beast.org/tutorials/Troubleshooting/](https://taming-the-beast.org/tutorials/Troubleshooting/), [https://taming-the-beast.org/tutorials/Prior-selection/](https://taming-the-beast.org/tutorials/Prior-selection/)

15:00 - 16:00: Phylo chat office hours


Tuesday 28th: Estimating population level trends using phylogenetic trees

8:00 - 8:50: *Lecture Julia, M: Joelle:* Lecture tree priors (coalescent+birth death) <br />
                Slides: TBA

9:05 - 10:30: *Tutorial Julia:* skyline tutorials <br />
                Tutorial: [https://taming-the-beast.org/tutorials/Skyline-plots/](https://taming-the-beast.org/tutorials/Skyline-plots/)

10:30 - 11:00 *Lecture Nicola + Joelle:* Structured populations <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-28_structured_nfm.pptx?raw=true)

11:30 - 13:00 *Tutorial Nicola + Joelle:* Structured Coalescent, Multi-Type Birth Death <br />
                Tutorials: [https://taming-the-beast.org/tutorials/Mascot-Tutorial/](https://taming-the-beast.org/tutorials/Mascot-Tutorial/), [https://taming-the-beast.org/tutorials/Structured-birth-death-model/](https://taming-the-beast.org/tutorials/Structured-birth-death-model/).

13:00 - 14:20 *Lecture + Tutorials: Julia & Nídia, M: Joelle* Tree distances, tree convergence, how to visualize and interpret trees  Julia & Nídia
                Slides: TBA
                Tutorials: TBA

15:00 - 16:00: Phylo chat office hours

Wednesday 29th: My tree is not a tree, help!

8:00 - 8:50: *Lecture Nicola, M: Nídia:* Recombination and Reassortment <br />
                Slides: [here](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2020-07-29_network_nfm.pptx?raw=true)

9:05 - 10:30: *Tutorial Nicola:* The coalescent with reassortment <br />
                Tutorials: [https://taming-the-beast.org/tutorials/Reassortment-Tutorial/](https://taming-the-beast.org/tutorials/Reassortment-Tutorial/)

10:30 - 11:00 *Closing Remarks and Q&A Everyone*

13:00 - 14:00: Phylo chat office hours



Prerequisites: This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module.

# Some Reading Material

- Provides an overview of packages in BEAST2 with explanations on the different models: [https://doi.org/10.1371/journal.pcbi.1006650](https://doi.org/10.1371/journal.pcbi.1006650)

- Paper showing site model over-fitting is ok: [https://www.nature.com/articles/s41467-019-08822-w](https://www.nature.com/articles/s41467-019-08822-w)

- Paper showing how to see if there is temporal signal in data using tip-randomizations: [https://academic.oup.com/mbe/article/32/7/1895/1016979](https://academic.oup.com/mbe/article/32/7/1895/1016979)

- Paper introducing the coalescent with reassortment: [https://doi.org/10.1073/pnas.1918304117](https://doi.org/10.1073/pnas.1918304117)
