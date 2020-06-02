# SISMID

Instructor(s):
Palacios, Julia; Müller, Nicola; Trovao, Nidia

Prerequisites: This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module.

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees (BEAST). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

Topics:
1. Introduction to molecular epidemiology and infectious disease phylodynamics

2. Phylogenetic Inference: Sequence Alignment

3. Phylogenetic Inference: Building Trees

4. Alignment and tree reconstruction using Seaview: A hands-on practical

5. Bayesian phylogenetics

6. <del> Advanced Bayesian Phylogenetics: Phyloalignment </del>

7. Advanced Bayesian Phylogenetics: Recombination and Reassortment *Nicola*

8. Estimating Evolutionary Rates and Divergence times: Is there clock signal.

9. Estimating rates and dates from time-stamped sequences: A hands-on practical

10. Viral epidemiology and the Coalescent

11. Non-Parametric Bayesian Population Dynamics Inference *Julia

12. Revealing the evolutionary dynamics of influenza

13. Accounting for population structure

14. Phylogeographic inference in discrete space: A hands-on practical

15. Phylogeographic inference in continuous space: A hands-on practical

16. Learning to Count:Tests for Evolutionary Innovation and Robust Sequence Distance
Estimation  [Potential change: Julia to testing different tree distributions  https://juliapalacios.github.io/research/publications/2019.12.23.887125v1.full.pdf]

17. Research Acknowledgments

## Schedule
The tutorials will all follow the same overall workflow, which will naturally lead to a lot of repetition. 

1st Day: What are tree and how to get them, what is Bayesian Phylogenetics and how to run a Bayesian Phylogenetics analysis

9:00: Introduction to Phylogenetics,including how to get from viruses to sequences to trees *Julia*

10:30: Break

10:45: From databases to sequences alignment *Nidia*

11:45: Intro to Beast *Nidia*

- Running a basic BEAST analysis. Suggested SARS-CoV-2 tutorial: [https://taming-the-beast.org/tutorials/Introduction-to-BEAST2/](https://taming-the-beast.org/tutorials/Introduction-to-BEAST2/)

12:30: Lunch

13:30: Evolutionary Models (clock and site models) *Nicola*

- Running different clock models, estimate. Suggested Influenza tutorials: [https://taming-the-beast.org/tutorials/Molecular-Dating-Tutorial/](https://taming-the-beast.org/tutorials/Molecular-Dating-Tutorial/), [https://taming-the-beast.org/tutorials/Substitution-model-averaging/](https://taming-the-beast.org/tutorials/Substitution-model-averaging/)

- TempEst SARS-CoV-2 tutoral *Nidia*

15:30: Break
    
15:45: Convergence, other MCMC related stuff, typical issues with beast runs and how to fix them + What are priors *Nicola*

- A few shorter tutorials on convergence etc. Suggested SARS-CoV-2 Tutorials: [https://taming-the-beast.org/tutorials/Troubleshooting/](https://taming-the-beast.org/tutorials/Troubleshooting/), [https://taming-the-beast.org/tutorials/Prior-selection/](https://taming-the-beast.org/tutorials/Prior-selection/)

17:30 End official programm -> Q&A

2nd Day: How to deal with different evolutionary and population processes and maybe how to present your analyses

9:00: Tree Priors/Population models (Coalescent + birth death models), skyline dynamics *Julia*

10:45 Break

11:00: Running a skyline analysis. Suggested SARS-CoV-2 tutorial: [https://taming-the-beast.org/tutorials/Skyline-plots/](https://taming-the-beast.org/tutorials/Skyline-plots/)

12:30: Lunch   

13:00: Accounting for population structure: Neutral trait models (DTA) and structured population models (struct coal + multitype birth death) *Nicola*

- Tutorial on one of these models. Suggested Influenza Tutorials: [https://taming-the-beast.org/tutorials/Mascot-Tutorial/](https://taming-the-beast.org/tutorials/Mascot-Tutorial/), [https://taming-the-beast.org/tutorials/Structured-birth-death-model/](https://taming-the-beast.org/tutorials/Structured-birth-death-model/).

15:00: Break

15:15: How to visulize and interpret SARS-CoV-2 trees, including phylogenetic uncertainty. *Nidia*

16:15: Distances on trees, comparison of tree distributions and convergence of tree distribution *Julia*
    
17:30 End official programm -> Q&A

3rd Day: More complex topics

9:00: Selection, fitness, recombination, Reassortment. *Nicola*

- Inferring Reassortment networks. Suggested Influenza Tutorial: [https://taming-the-beast.org/tutorials/Reassortment-Tutorial/](https://taming-the-beast.org/tutorials/Reassortment-Tutorial/)
   
12:30 End official program -> Q&A



  
