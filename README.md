


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


### Monday, July 13: Full Day

**9:00 am – 10:30 am**  
**Introduction to Bayesian Phylogenetics and BEAST**  
*Lecturer: Julia A. Palacios*  
- Slides: [2024-07-24_Introduction.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-24_Introduction.pptx?raw=true)

**10:45 am – 12:15 pm**  
**Getting BEAST2 to Run with SARS-CoV-2**  
*Lecturer: Nicola F. Müller*  
- Slides: [2024-07-24_beast_introduction.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-24_beast_introduction.pptx?raw=true)  
- Tutorial: [Introduction-to-BEAST2.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Introduction-to-BEAST2.zip?raw=true)

**1:30 pm – 3:00 pm**  
**Structured Populations**  
*Lecturer: Nicola F. Müller*  
- Slides: [2024-07-26-structured_nfm.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-structured_nfm.pptx?raw=true)  
- Tutorial: [Mascot-Tutorial.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Mascot-Tutorial.zip?raw=true)

**3:30 pm – 5:00 pm**  
**Multi-Type Birth–Death Models**  
*Lecturer: Nicola F. Müller*  
- Tutorial: [Structured-birth-death-model.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Structured-birth-death-model.zip?raw=true)

---

### Tuesday, July 14: Full Day

**8:30 am – 10:00 am**  
**Modeling the Evolution of Genomes through Time**  
*Lecturer: Nicola F. Müller*  
- Slides: [2024-07-25-sismid_evol_nfm.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25-sismid_evol_nfm.pptx?raw=true)  
- Tutorial: [BModelTest.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/BModelTest.zip?raw=true)

**10:30 am – 12:00 pm**  
**Coalescent and Birth–Death Tree Priors**  
*Lecturer: Julia A. Palacios*  
- Slides: [2024-07-25_tree_priors.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25_tree_priors.pptx?raw=true)

**1:30 pm – 3:00 pm**  
**Ne Inference Tutorial**  
*Lecturer: Julia A. Palacios*  
- Tutorial: [Ne_inference.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/raw/master/Tutorials/Ne_inference.zip?raw=true)

**3:30 pm – 4:40 pm**  
**Priors and Convergence Issues (SARS-CoV-2 Examples)**  
*Lecturer: Nicola F. Müller*  
- Slides: [2024-07-25_priorstrouble_nfm.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-25_priorstrouble_nfm.pptx?raw=true)  
- Tutorial: [Prior-selection.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/Prior-selection.zip?raw=true)

**4:40 pm – 5:00 pm**  
**How Phylodynamics Relates to Transmission Dynamics**  
*Lecturers: Nicola F. Müller & Julia A. Palacios*  
- Slides: [2024-07-26-relation_phylodynamics_epidemiology.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2024-07-26-relation_phylodynamics_epidemiology.pptx?raw=true)

---

### Wednesday, July 15: Half Day (ends at noon)

**8:30 am – 10:00 am**  
**Visualizing and Interpreting Trees & Phylogenetic Mapping**  
*Lecturer: Julia A. Palacios*  
- Slides: [2023-07-14_phylo_mapping.pptx](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-14_phylo_mapping.pptx)  
- Tutorial: [mascot_ggtree.zip](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Tutorials/mascot_ggtree.zip?raw=true)

**10:30 am – 12:00 pm**  
**Tree Distances, Summaries, and Convergence**  
*Lecturer: Julia A. Palacios*  
- Slides: [2023-07-13_Summary_Trees.pdf](https://github.com/JuliaPalacios/SISMID_EvolutionaryDynamics/blob/master/Lectures/2023-07-13_Summary_Trees.pdf?raw=true)

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
